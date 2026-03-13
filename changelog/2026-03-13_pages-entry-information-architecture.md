# 2026-03-13 Pages 入口与 Profile 职责分离

## 变更背景

- `LessUp` 同时承担 GitHub Profile 仓库与 GitHub Pages 站点入口，两者目标不同：README 偏展示，Pages 首页更适合做项目导航。
- 此前 `index.md` 与 `README.md` 都在承担项目总览，但内容风格与链接维护不统一。
- 同时，项目列表中 `Note Sync Now` 仍使用旧仓库链接 `LessUp/sync-notes`，需要与当前仓库名 `LessUp/brave-sync-notes` 对齐。

## 导航与目录调整

- 保留 `README.md` 作为 GitHub Profile 展示页，不破坏其可视化排版与现有 widget 结构。
- 将根目录 `index.md` 收敛为 GitHub Pages 文档入口，只负责项目定位、主题导航、推荐阅读路径与核心入口表。
- 保持 `changelog/CHANGELOG.md` 作为归档入口，记录后续 profile 与 pages 调整。

## 首页调整

- 重写 `index.md`，新增项目定位、适合谁、从哪里开始、推荐阅读路径与核心项目表。
- 首页不再复刻 profile 的视觉展示内容，而是按“算子优化 / 推理引擎 / 应用项目”三类聚合仓库。
- 首页核心入口明确区分 `README.md`（Profile 展示页）与 `index.md`（Pages 导航页）的职责。

## Pages / Workflow 调整

- 保留现有 `.github/workflows/pages.yml` 分支触发设置；当前已覆盖 `main, master`，无需再次修改。
- 保持 `_config.yml` 的 `baseurl: /LessUp` 不变；已通过线上检查确认 `https://lessup.github.io/LessUp/` 可访问，而小写路径不可用。
- 修正 Profile / Pages 中 `Note Sync Now` 的仓库链接到 `https://github.com/LessUp/brave-sync-notes`。

## 验证结果

- 已通过 `curl` 验证 `https://lessup.github.io/LessUp/` 返回 `200`，`https://lessup.github.io/lessup/` 返回 `404`，说明当前大小写路径应保持不变。
- 已人工检查 `README.md` 与 `index.md` 的职责分离：前者继续展示个人资料，后者负责项目导航。
- 已人工检查 `Note Sync Now` 链接已对齐当前仓库命名。
- 本次未运行本地 Jekyll 构建；后续可在具备 Ruby / Jekyll 环境时补充静态构建验证。

## 后续待办

- 后续如继续扩展公开项目，可只更新 `README.md` 展示项与 `index.md` 导航表，不再混用两种页面职责。
- 可在后续单独整理 `changelog/` 索引页，进一步提升 Pages 的归档可浏览性。
