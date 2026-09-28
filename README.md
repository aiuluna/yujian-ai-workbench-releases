# 隅间 AI 工作台安装包

本仓库只发布隅间 AI 工作台的编译安装包，不包含源代码。

## 下载

前往 [Releases](https://github.com/aiuluna/yujian-ai-workbench-releases/releases) 选择版本。

当前公开构建目标为 macOS Apple Silicon（`darwin-arm64`）。每个版本会提供 DMG、ZIP、blockmap 和 `SHA256SUMS`。下载 DMG 后将应用拖入“应用程序”即可安装。

当前内部预发布包为无签名、未公证构建。首次打开时，macOS 可能要求在“系统设置 > 隐私与安全性”中手动允许打开。它适用于受控内部试用，不代表面向外部用户的正式发行。

## 使用前配置

安装包内不包含个人账号、模型 Token 或 AI 听记凭据。首次启动后需要登录隅间工作台账号，并按工作台提示配置自己的模型和听记凭据。

## 发布边界

- 源代码、插件和 DSH 固定版本保存在私有的 [`yujian-ai-workbench`](https://github.com/aiuluna/yujian-ai-workbench) 仓库。
- 本仓库只作为 GitHub Release 文件存储和下载入口。
- 不要在 Issue、讨论区或 Release 资产中提交账号、Token、证书或其他凭据。
