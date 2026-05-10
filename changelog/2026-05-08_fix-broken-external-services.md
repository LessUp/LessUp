# 2026-05-08 修复 GitHub Profile 外部服务失效问题

## 问题描述
GitHub Profile README 中多个外部服务引用的图片和组件无法正常显示。

## 根因分析

| 问题 | 根因 | 影响范围 |
|------|------|----------|
| GitHub Readme Stats 卡片显示 "Something went wrong" | 自部署 Vercel 实例 (`github-readme-stats-six-iota-99.vercel.app`) 的 PAT_1 环境变量丢失/过期，官方实例 (`github-readme-stats.vercel.app`) 也已暂停部署 (DEPLOYMENT_PAUSED) | Stats 卡片 + Top Languages 卡片 |
| 大学/公司 Logo 图片加载失败 | Clearbit Logo API (`logo.clearbit.com`) 已停服 (被 HubSpot 收购后关闭) | Xidian University, Mindray, ZEGO, BGI |
| GitHub Trophy 显示为破裂图片 | 自部署 Trophy 实例 (`github-profile-trophy-silk-ten.vercel.app`) 返回 404 | Trophy 展示区 |

## 修复方案

### 1. GitHub Readme Stats (Stats + Top Languages)
- **Before**: `github-readme-stats-six-iota-99.vercel.app` (PAT_1 丢失)
- **After**: `github-readme-stats-sigma-five.vercel.app` (经验证可正常返回 SVG)
- **注**: 官方实例 `github-readme-stats.vercel.app` 也已暂停部署 (503)，无法使用

### 2. 公司/大学 Logo
- **Before**: `logo.clearbit.com/{domain}` (已停服，EOF 错误)
- **After**: `favicon.im/{domain}` (返回 SVG 格式 favicon，质量较高)

### 3. GitHub Profile Trophy
- **Before**: `github-profile-trophy-silk-ten.vercel.app` (返回 404)
- **After**: `github-profile-trophy.vercel.app` (官方公共实例，经验证正常)

## 验证结果 (全部 HTTP 200 ✅)
1. capsule-render (Header) → 200 ✅
2. github-readme-stats-sigma-five (Stats) → 200 ✅  
3. github-readme-stats-sigma-five (Top Langs) → 200 ✅
4. favicon.im/xidian.edu.cn → 200 ✅
5. favicon.im/mindray.com → 200 ✅
6. favicon.im/zego.im → 200 ✅
7. favicon.im/genomics.cn → 200 ✅
8. streak-stats.demolab.com → 200 ✅
9. github-profile-trophy.vercel.app → 200 ✅

## 修改文件
- `README.md`: 更新了 5 处外部服务 URL

## 注意事项
- 公共 Vercel 实例可能有请求限制，如遇限流，建议重新自部署并配置有效的 GitHub PAT
- favicon.im 返回的是网站 favicon 图标，视觉效果比原 Clearbit Logo API 稍简洁
