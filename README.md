# DeepInfer 深度解读（单页）

DeepSeek 于 2026 年 10 月开源的推理框架 **DeepInfer** 的说明页：架构拆解、相对 vLLM 的 8 项改进、硬件门槛、快速上手与选型建议。

- 纯静态单文件，无外部依赖（不加载任何 CDN、字体或脚本）
- 适配桌面与移动端，支持深浅色切换
- 内容基于官方 README、源码与公开报道整理，截至 2026-10-25

## 本地查看

直接用浏览器打开 `index.html` 即可，无需构建或服务器。

## 部署

仓库根目录的 `index.html` 即站点入口。在 **Settings → Pages** 中选择
`Deploy from a branch` → 分支 `main` → 目录 `/ (root)`，保存后等待 1–2 分钟。

访问地址：`https://<你的用户名>.github.io/<仓库名>/`

## 说明

页面中的技术细节以 [deepseek-ai/DeepInfer](https://github.com/deepseek-ai/DeepInfer) 官方仓库为准；
第三方数据（如单集群日处理 token 量）已在页面内单独标注。
