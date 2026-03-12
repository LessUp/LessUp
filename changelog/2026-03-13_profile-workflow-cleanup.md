# Profile Workflow 清理

日期：2026-03-13

## 变更内容

- 删除 GitHub Profile Repository 中冗余的 `ci.yml`
- 保留已正常运行的 `pages.yml` 与 `snake.yml`
- 避免 `configure-pages` 在未启用对应 Pages site 时继续制造无意义失败信号

## 背景

`LessUp` 仓库本质上是个人 Profile Repository，主价值在 README 展示、Pages 部署与贡献蛇动画。额外的通用 CI 既不提供有效质量门，也会因为 Pages 配置前提不满足而持续失败，因此本次将其移除。
