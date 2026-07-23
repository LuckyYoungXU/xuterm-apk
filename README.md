# XuTerm
Free, privacy-first SSH & Mosh terminal for Android, built for DevOps and system administrators.
> ⚠️ Important: XuTerm is an independent Android mobile SSH client, **not related to xterm / xterm.js**.

## ✨ Core Features
### Terminal Connection
- Full SSH & enhanced Mosh support for unstable mobile networks
- Native Tmux support: Visual split panes and multi-window management without memorizing complex shortcuts
- Multiple concurrent sessions, quick switch, tablet-friendly horizontal layout
- Vertical color strip to visually distinguish input/output logs inside sessions
- Custom shortcut bar above virtual keyboard
- Grouped saved quick commands, one-tap auto insertion

### Security & Credential Management
- Built-in locally encrypted TOTP 2FA token manager
- Auto-fill saved credentials for sudo privilege prompts
- Private keys, connection configurations and all sensitive data encrypted locally
- Biometric protection for credential storage

### File Preview & SFTP Manager
- Inline preview for images, PDF and spreadsheets when using `cat` in terminal
- SFTP browser supports upload, download, and preview of images, PDF and spreadsheets
- Built-in syntax-highlighted text editor for remote files
- Direct share remote files within SFTP panel
- Calculate remote file hash over SSH without fully downloading files

### File Transfer
- Native trzsz bidirectional file transfer with resume support

### Server Monitoring
- Real-time server resource status monitoring
- Slide gesture to terminate high-load running processes

### Configuration Sync & Backup
- QR-code cross-device configuration synchronization
- Encrypted import & export of connection profiles, protected by custom password

### Experience Customization
- Multi-language support
- Multiple color themes including full dark mode
- Pinch gesture to adjust terminal font size
- Optimized for mobile phones and horizontal tablet mode

## 📊 Feature Comparison with mainstream Android SSH clients
| Function | XuTerm | JuiceSSH | Termius |
|---|---|---|---|
| SSH + Enhanced Mosh | ✅ | ✅ | ✅ |
| Native tmux support | ✅ | ❌ | ⚠️ Subscription |
| Built-in local TOTP 2FA | ✅ | ❌ | ⚠️ Subscription |
| Trzsz file transfer with resume | ✅ | ❌ | ❌ |
| In-terminal PDF / image / spreadsheet preview | ✅ | ❌ | ❌ |
| SFTP built-in text editor & file preview | ✅ | ⚠️ Limited | ⚠️ Subscription |
| Remote file hash calculation over SSH | ✅ | ❌ | ❌ |
| Sudo password auto-fill | ✅ | ❌ | ⚠️ Subscription |
| Server monitoring + slide-to-kill processes | ✅ | ❌ | ❌ |
| Encrypted config import/export with custom password | ✅ | ❌ | ⚠️ Subscription |
| One-time purchase model | ✅ | Partial IAP | Pure subscription |
| All sensitive data stored locally & encrypted | ✅ | Partial | Partial |

## 📥 Official Download Channels
- Official Website: https://xuterm.vercel.app
- GitHub Releases: https://github.com/LuckyYoungXu/tools/releases/latest
- Huawei AppGallery: https://appgallery.huawei.com/app/C118106679
- APKPure: https://apkpure.com/p/com.yongqing.xuterm
- Appteka: https://appteka.store/user/566539

### File SHA256 Checksum
> 17E93646A6181E92398CE5FD2A017C1F20384CB8891C5FA9AD81A2FEAA35E37F

## 📍 Software Directory Listings
- AlternativeTo: https://alternativeto.net/software/xuterm/
- ProductHunt: https://www.producthunt.com/posts/xuterm/
- Saashub: https://www.saashub.com/u/xuterm

## ❓ Frequently Asked Questions
### Will my connection data, private keys or TOTP codes be uploaded to external servers?
No. All terminal content, private keys, host configurations and TOTP tokens are stored locally on your Android device. No telemetry collection, no data outbound upload.

### How are private keys and server configurations protected?
All sensitive data is encrypted locally. You can enable biometric lock to prevent unauthorized access.

### Can I migrate all my saved servers to another Android device?
Yes. You can sync via QR code directly, or export an encrypted configuration archive protected by your custom password.

## 💬 Feedback & Contribution
Report bugs or submit feature requests via GitHub Issues:
https://github.com/LuckyYoungXu/tools/issues
> Note: A GitHub account is required to create new issues.
If you don't have a GitHub account, you can send feedback via email: xuterm@gmail.com

# 中文介绍
XuTerm 是面向 Android 的隐私优先 SSH & Mosh 终端，专为运维工程师、服务器管理员打造。
> ⚠️ 重要说明：XuTerm 是独立开发的安卓移动端SSH客户端，**与 xterm、xterm.js 无任何关联**

## ✨ 功能一览
### 终端连接能力
- SSH + 增强版 Mosh，适配手机弱网络环境
- 原生支持 Tmux：可视化分窗、多窗口操作，无需记忆复杂快捷键
- 多会话并行管理，一键快速切换，深度适配平板横屏布局
- 会话竖向彩色条直观区分输入与输出日志
- 虚拟键盘上方可自定义快捷按键栏
- 常用命令分组保存，点击一键自动输入

### 安全体系
- 内置本地加密 TOTP 双重验证码管理器
- 支持 sudo 密码自动填充
- 私钥、主机配置等敏感信息本地加密存储
- 生物识别锁定保护密钥数据

### 文件预览与SFTP管理
- 终端执行 cat 命令，直接在线预览图片、PDF、表格文档
- SFTP浏览器支持文件上传、下载，同时预览图片、PDF、表格文档
- 远程文本文件内置语法高亮代码编辑器
- SFTP面板支持远程文件直接分享
- 通过SSH远程计算文件哈希，无需完整下载文件

### 文件传输
- 原生 trzsz 双向文件传输，支持断点续传

### 服务器状态监控
- 实时查看服务器资源负载状态
- 滑动手势直接终止高负载进程

### 配置迁移与备份
- 扫码跨设备同步主机配置
- 支持自定义密码保护，加密导入/导出连接配置

### 个性化体验
- 完整多语言支持
- 多款主题，包含纯深色模式
- 双指手势缩放终端字体
- 同时适配手机竖屏、平板横屏场景

## 📥 下载渠道
- 官方网站：https://xuterm.vercel.app
- GitHub发行版：https://github.com/LuckyYoungXu/tools/releases/latest
- 华为应用市场：https://appgallery.huawei.com/app/C118106679
- APKPure：https://apkpure.com/p/com.yongqing.xuterm
- Appteka：https://appteka.store/user/566539

### 安装包 SHA256 校验
> 17E93646A6181E92398CE5FD2A017C1F20384CB8891C5FA9AD81A2FEAA35E37F


## 📍 收录平台
- AlternativeTo：https://alternativeto.net/software/xuterm/
- ProductHunt：https://www.producthunt.com/posts/xuterm/
- Saashub：https://www.saashub.com/u/xuterm

## ❓ 常见问题
### 密钥、会话信息、TOTP令牌会上传到第三方服务器吗？
不会。所有数据仅保存在本机，无遥测收集，不会向外传输任何用户数据。

### 如何保障私钥与服务器配置安全？
全部敏感数据本地加密存储，可以开启生物识别，防止他人访问。

### 如何把主机配置迁移到另一台安卓设备？
支持扫码快速同步；也可以导出受自定义密码保护的加密配置包，跨设备导入。

## 💬 反馈渠道
Bug反馈、功能建议请提交 Issues：
https://github.com/LuckyYoungXu/tools/issues
> 提示：提交反馈需要登录GitHub账号。
若无GitHub账号，可发送邮件反馈：xuterm@gmail.com
