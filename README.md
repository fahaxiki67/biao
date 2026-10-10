# 标镜

标镜安装包下载与版本说明。当前以新的私有源码仓库 **biao-muse** 为唯一开发基线，首版为 **0.1.0 开发预发行版**。后续开发与修复沿此基线继续，公开下载仍在本仓库提供。

## 当前首版下载

[0.1.0-development.20261010 开发预发行版](https://github.com/fahaxiki67/biao/releases/tag/v0.1.0-development.20261010)。

- [macOS ARM64 下载包](https://github.com/fahaxiki67/biao/releases/download/v0.1.0-development.20261010/biaojing-development-0.1.0-macos-arm64.zip)：适用于 Apple 芯片 Mac。
- [Mac 安装说明](https://github.com/fahaxiki67/biao/releases/download/v0.1.0-development.20261010/INSTALL_MAC.md)与 [SHA256 校验值](https://github.com/fahaxiki67/biao/releases/download/v0.1.0-development.20261010/SHA256SUMS.txt)。
- Windows 首版包待实体机独立构建和验证，当前没有 Windows 下载附件。

各发布记录见 [Releases](https://github.com/fahaxiki67/biao/releases)。请以每个版本的附件、支持系统、校验值和已知问题说明为准。

## 开发状态

保留已有业务模块、会员机制和待完善功能。正式会员服务尚未接通，未授权的受保护业务入口保持不可用。开发预发行版不代表全部业务流程或检测方法已通过验收。

PDF 运行依赖已替换为 PDFium、pypdf、pdfplumber 和 PDFminer。公开包保留对应第三方许可与声明。

Mac 包没有 Apple Developer ID 签名或公证，首次打开可能受到 macOS 限制，详见安装说明。

## 源码与资料

源码在私有仓库持续维护。本公开仓库只用于二进制包和说明，不上传源码 ZIP、真实用户资料、测试样本、历史验收底稿或凭据。用户业务资料保存在自己的本地工作区。
