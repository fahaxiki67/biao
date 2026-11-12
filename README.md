# 标镜

标镜安装包下载与版本说明。开发基线为私有源码仓库 **biao-muse**，公开下载在本仓库提供。

## 当前下载

[0.1.28 开发预发布版](https://github.com/fahaxiki67/biao/releases/tag/v0.1.28-development.20261112)（2026-11-12）：

- [macOS ARM64 下载包](https://github.com/fahaxiki67/biao/releases/download/v0.1.28-development.20261112/biaojing-development-0.1.28-macos-arm64.zip)：仅适用于 Apple 芯片 Mac，不适用于 Intel Mac。
- [SHA256 校验值](https://github.com/fahaxiki67/biao/releases/download/v0.1.28-development.20261112/SHA256SUMS.txt)。下载后请先核对。
- 首次打开受 macOS 限制时，处理方法见 [Mac 安装说明](https://github.com/fahaxiki67/biao/releases/download/v0.1.0-development.20261010/INSTALL_MAC.md)。

本版的新增能力、已验证范围和暂缓事项见该版本的发布说明。

## Windows

0.1.28 没有 Windows 安装包。[0.1.0](https://github.com/fahaxiki67/biao/releases/tag/v0.1.0-development.20261010) 附带的 Windows 64 位包是作者会员版，只开放已批准的作者邮箱登录，公众暂不可用。公众可用的 Windows 版本待实体机独立构建和验证。

## 开发状态

开发预发布版用于受控试用和继续开发，不代表全部业务流程或检测方法已通过验收。保留已有业务模块、会员机制和待完善功能；正式会员服务尚未全面开通，未授权的受保护业务入口保持不可用。

PDF 运行依赖为 PDFium、pypdf、pdfplumber 和 PDFminer。公开包保留对应第三方许可与声明。

Mac 包没有 Apple Developer ID 签名或公证，首次打开可能受到 macOS 限制。不要关闭系统整体安全保护。

各版本记录见 [Releases](https://github.com/fahaxiki67/biao/releases)，以各版本的附件、支持系统、校验值和已知问题说明为准。

## 源码与资料

源码在私有仓库维护。本公开仓库只用于二进制包和说明，不上传源码、源码补丁、真实用户资料、测试样本、历史验收底稿或凭据。用户业务资料保存在自己的本地工作区。
