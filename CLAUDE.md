# CLAUDE.md

> 本文件为 Claude Code CLI 提供项目配置。

## 项目定位

**GitHub Profile 主页仓库**（账号 `holtwood`，仓库名 `LessUp`）—— 个人主页与成果展示，呈现 AI Infrastructure / HPC 方向的项目、经历与技术栈。

- 主页：<https://github.com/holtwood>
- Pages 站点：<https://holtwood.github.io/LessUp/>

## 仓库结构

```text
LessUp/
├── README.md              # 主页展示页（GitHub Profile 渲染此文件）
├── index.md               # GitHub Pages 站点入口
├── _config.yml            # Jekyll 配置（cayman 主题 + SEO）
├── CHANGELOG.md           # 变更记录（Keep a Changelog 格式）
├── LICENSE                # MIT
├── CLAUDE.md              # 本文件
└── .github/workflows/
    ├── pages.yml          # Jekyll 构建并部署 GitHub Pages
    └── snake.yml          # 贡献热力图动画（每 6 小时更新至 output 分支）
```

## 关键文件

### README.md

- 主页展示页，**不是代码文件**，而是视觉呈现文档
- 大量使用徽章、统计组件、项目卡片等 GitHub Profile 特性
- 章节：About / Now / Projects / Experience / Tech Stack / Stats / Contact
- 中英双语：以英文为主，关键章节附中文

### CHANGELOG.md

- 遵循 [Keep a Changelog](https://keepachangelog.com/) 格式，日期格式 `YYYY-MM-DD`
- 所有对外可见的改动都应记录

## 工作流

### 更新主页内容

1. 编辑 `README.md`
2. 同步更新 `CHANGELOG.md`
3. 提交推送 —— `pages.yml` 会自动重新构建并部署站点

### 无构建流程，但有 CI/CD

本仓库没有构建、测试与包管理流程（无 `package.json`），但**有两个 workflow**：

| Workflow | 触发 | 作用 |
|----------|------|------|
| `pages.yml` | push（`*.md` / `_config.yml` / `docs/**` 变更） | Jekyll 构建并部署 GitHub Pages |
| `snake.yml` | 每 6 小时 + 手动 | 生成贡献热力图，推送到 `output` 分支 |

## 注意事项

1. **展示名 ≠ 仓库名**：`_config.yml` 的 `title` / `author` 是展示名，`baseurl: /LessUp` 是仓库名。账号已由 `LessUp` 更名为 `holtwood`，`repository` / `url` 字段须与当前账号一致。
2. **workflow 中的账号名必须用当前名**：`snake.yml` 的 `github_user_name` 若写成旧名 `LessUp`，GitHub API 会报 `Could not resolve to a User with the login of 'LessUp'`，导致该 workflow 每次运行都失败。
3. **徽章与统计组件依赖第三方服务**（shields.io、stats 卡片等），展示异常时优先检查服务可用性。
4. **`output` 分支由机器人维护**，不要手动提交。

## 提交规范

使用约定式提交：`feat` / `fix` / `docs` / `chore` / `ci` / `style`
