# XuTerm
Free, privacy-first SSH & Mosh terminal for Android, built for DevOps and system administrators.
> ⚠️ Important: XuTerm is an independent Android mobile SSH client, **not related to xterm / xterm.js**.

## ✨ Core Features
### Terminal Connection
- Full SSH & enhanced Mosh support for unstable mobile networks
- Native tmux integration: Visually operate split panes and multi-window sessions, no need to memorize cumbersome keyboard shortcuts
- Multiple concurrent sessions, quick switch, tablet-friendly horizontal layout
- Vertical color strip to visually distinguish input/output logs inside sessions
- Custom shortcut bar above virtual keyboard
- Grouped saved quick commands, one-tap auto insertion
- Quick shell snippet library with smart cursor positioning for fast command assembly

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

### Visual Ops Dashboard
- At-a-glance system summary: ring charts for CPU / memory / disk / swap, plus CPU model, load average and real-time network throughput
- Modular visual management for disks, systemd services, processes, network, Docker containers, firewall, scheduled tasks and rsync
- One-tap or pull-to-refresh to fetch the latest metrics
- Slide gesture to terminate high-load processes directly from the dashboard
- Enter straight from the host list, no terminal commands needed

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

### Handy Dev‑Ops Toolkit
- SSH key generator: Generate RSA / Ed25519 key pairs
- Secure random password generator: Generate high‑strength random passwords
- WHOIS domain lookup: Query public domain registration info
- DNS record lookup: Query various DNS resource records
- SSL/TLS certificate inspector: Check HTTPS certificate status and expiry
- Unix timestamp converter: Convert between timestamp and human‑readable time
- Common Encode‑Decode Tool, supports base64, hex, case conversion, url, unicode and utf8 encoding & decoding
- URL parser: Decompose each component of URL
- JSON pretty formatter: Beautify JSON and detect syntax errors
- TCP Port Test, check connectivity of single host port
- CIDR Subnet Calculator, quickly calculate IP subnet, netmask and address range
- Number base converter: Convert between decimal, hex and octal
- Built‑in QR‑code utility for quick encode/decode operations.
- Added ASCII tools for text conversion and formatting tasks.
- Added regex tester 
- JWT parser & validator

## 📊 Feature Comparison with mainstream Android SSH clients
| Function | XuTerm | JuiceSSH | Termius |
|---|---|---|---|
| SSH + Enhanced Mosh | ✅ | ✅ | ✅ |
| Native visual Tmux split & multi-window control | ✅ | ❌ | ⚠️ Subscription |
| Built-in local TOTP 2FA | ✅ | ❌ | ⚠️ Subscription |
| Sudo password auto-fill | ✅ | ❌ | ⚠️ Subscription |
| Trzsz file transfer with resume | ✅ | ❌ | ❌ |
| In-terminal PDF / image / spreadsheet preview | ✅ | ❌ | ❌ |
| SFTP built-in text editor & file preview | ✅ | ⚠️ Limited | ⚠️ Subscription |
| Remote file hash calculation over SSH | ✅ | ❌ | ❌ |
| Vertical color strip to separate input and output logs | ✅ | ❌ | ❌ |
| Server monitoring + kill processes | ✅ | ❌ | ❌ |
| Visual ops dashboard (CPU / memory / disk / swap rings, disks, services, processes, Docker, Firewall, crontab, rsync) | ✅ | ❌ | ⚠️ Subscription |
| Built-in DevOps toolkit (keygen, password, WHOIS, DNS, SSL check, encode/decode, CIDR, 15+ tools) | ✅ | ❌ | ❌ |
| Encrypted config import/export with custom password | ✅ | ❌ | ⚠️ Subscription |
| All sensitive data stored locally & encrypted | ✅ | Partial | Partial |
| 100% free, all features unlocked, no ads, no subscriptions, no in-app purchases | ✅ | Partial IAP | Pure subscription |

## 📥 Official Download Channels
- Official Website: https://xuterm.vercel.app
- GitHub Releases: https://github.com/LuckyYoungXu/tools/releases/latest
- Huawei AppGallery: https://appgallery.huawei.com/app/C118106679
- APKPure: https://apkpure.com/p/com.yongqing.xuterm
- Uptodown: https://xuterm.en.uptodown.com/android
- Appteka: https://appteka.store/user/566539

### File SHA256 Checksum
> v1.0.27: A855572D0CE47B4A6F9DDE14DA2A5BAB00F487B9DEB69F45977EAF029D4D83A3

<details>
<summary>Checksums for older versions (v1.0.20 – v1.0.26)</summary>

> v1.0.26: F035D5B13E4365E18117AA3D7FEF532982EECED49EA44D939BC6BC9FB13B0D9C

> v1.0.25: 7FBB29D885BB405A954469A7D0241E49976D916D221EBCFD046E1DC85B5ED4AA

> v1.0.24: DA45F46223EAECD14580DA899862289855E18B660B30E14BF6004D0BA383F50F

> v1.0.23: 5628EB319F096B8A8D887D19F5F02EFC8DD01B3B194AF7DBF343B75E2E397D7E

> v1.0.22: 5E739CFEF45C7C37107EE1EE9DF4EB5A42FBA187BBF461E6919167604D8D82A3

> v1.0.20: E93FE9AA41BA75BB29A9A6EA2CB150F803BDBA29D8BD0F6BBA7720A5B5E12D42

</details>

### File SHA1 Checksum
> v1.0.27: 8BF8DEDB236B1B7F15E51404A84566417B97CE1E

<details>
<summary>Checksums for older versions (v1.0.20 – v1.0.26)</summary>

> v1.0.26: F9FA398F1E69E66AAF44821B9A0665445214CDDD

> v1.0.25: B4DE881FAA71776F1ABFAC634D1E0BA6AB172A03

> v1.0.24: 5D76A7BC15B10075E6AB770C40758FC4CA101664

> v1.0.23: 1EBB2315FB4B5AC288F0B30D0366413F51451181

> v1.0.22: 79AEB61599031CB7A4DF9228D03D389505EBAAF7

> v1.0.20: 84265AA9A8F623980E834CDF3D44B7DC41489B13

</details>

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

---

# 中文介绍
XuTerm 是面向 Android 的隐私优先 SSH & Mosh 终端，专为运维工程师、服务器管理员打造。
> ⚠️ 重要说明：XuTerm 是独立开发的安卓移动端SSH客户端，**与 xterm、xterm.js 无任何关联**

## ✨ 功能一览
### 终端连接能力
- SSH + 增强版 Mosh，适配手机弱网络环境
- 原生支持 Tmux：可视化操作分窗与多窗口会话，不用记忆繁琐快捷键
- 多会话并行管理，一键快速切换，深度适配平板横屏布局
- 会话竖向彩色条直观区分输入与输出日志
- 虚拟键盘上方可自定义快捷按键栏
- 常用命令分组保存，点击一键自动输入
- 快捷 Shell 片段库，智能光标定位，快速组装命令

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

### 可视化运维仪表盘
- 系统摘要一目了然：CPU / 内存 / 磁盘 / Swap 环形进度图，CPU 型号、负载均值、实时网速
- 模块化可视化管理：磁盘、系统服务、进程、网络、Docker 容器、防火墙、定时任务与rsync
- 一键或下拉刷新，随时获取最新指标
- 仪表盘中滑动手势直接终止高负载进程
- 主机列表一键进入，无需记忆任何终端命令

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

### 实用工具箱
- SSH 密钥生成器：生成 RSA、Ed25519 密钥对
- 安全随机密码生成器：生成高强度随机密码
- WHOIS 域名查询：查询域名公开注册信息
- DNS 记录查询：查询各类域名解析记录
- SSL/TLS 证书检测：检查 HTTPS 证书状态与有效期
- Unix 时间戳转换：时间戳和可读时间互相转换
- 常用编解码，支持 base64、hex、大小写转换、url、unicode、utf8 编码与解码
- URL 解析工具：拆解 URL 各组成部分
- JSON 格式化工具：JSON 文本美化与错误检测
- TCP 端口测试，检测单个主机端口连通性
- CIDR 网段计算，快速计算 IP 网段、掩码、地址范围
- 进制转换：十 / 十六 / 八进制数字互转
- 内置二维码工具，支持快速编码与解码
- ASCII 工具，用于文本转换与格式处理
- 正则表达式测试工具
- JWT 解析验签工具

## 📊 主流安卓SSH客户端功能对比
| 功能 | XuTerm | JuiceSSH | Termius |
|---|---|---|---|
| SSH + 增强Mosh | ✅ | ✅ | ✅ |
| Tmux可视化分窗、多窗口操控 | ✅ | ❌ | ⚠️ 需要订阅 |
| 内置本地TOTP二次验证 | ✅ | ❌ | ⚠️ 需要订阅 |
| Sudo密码自动填充 | ✅ | ❌ | ⚠️ 需要订阅 |
| Trzsz断点续传文件传输 | ✅ | ❌ | ❌ |
| 终端内直接预览PDF/图片/表格 | ✅ | ❌ | ❌ |
| SFTP内置代码编辑器与文件预览 | ✅ | ⚠️ 功能受限 | ⚠️ 需要订阅 |
| SSH远程计算文件哈希 | ✅ | ❌ | ❌ |
| 竖向彩色条区分输入输出日志 | ✅ | ❌ | ❌ |
| 服务器监控 + 结束高负载进程 | ✅ | ❌ | ❌ |
| 可视化运维仪表盘（CPU/内存/磁盘/Swap环形图、磁盘、服务、进程、Docker、防火墙、定时任务与rsync） | ✅ | ❌ | ⚠️ 需要订阅 |
| 内置运维工具箱（密钥/密码生成、WHOIS、DNS、SSL检测、编解码、网段计算等15+工具） | ✅ | ❌ | ❌ |
| 带自定义密码的加密配置导入导出 | ✅ | ❌ | ⚠️ 需要订阅 |
| 全部敏感数据本地加密保存 | ✅ | 部分支持 | 部分支持 |
| 完全免费，全部功能开放，无广告、无订阅、无内购 | ✅ | 部分内购 | 纯订阅制 |

## 📥 下载渠道
- 官方网站：https://xuterm.vercel.app
- GitHub发行版：https://github.com/LuckyYoungXu/tools/releases/latest
- 华为应用市场：https://appgallery.huawei.com/app/C118106679
- APKPure：https://apkpure.com/p/com.yongqing.xuterm
- Uptodown: https://xuterm.cn.uptodown.com/android
- Appteka：https://appteka.store/user/566539

### 安装包 SHA256 校验
> v1.0.27: A855572D0CE47B4A6F9DDE14DA2A5BAB00F487B9DEB69F45977EAF029D4D83A3

<details>
<summary>历史版本校验值（v1.0.20 – v1.0.26），点击展开</summary>

> v1.0.26: F035D5B13E4365E18117AA3D7FEF532982EECED49EA44D939BC6BC9FB13B0D9C

> v1.0.25: 7FBB29D885BB405A954469A7D0241E49976D916D221EBCFD046E1DC85B5ED4AA

> v1.0.24: DA45F46223EAECD14580DA899862289855E18B660B30E14BF6004D0BA383F50F

> v1.0.23: 5628EB319F096B8A8D887D19F5F02EFC8DD01B3B194AF7DBF343B75E2E397D7E

> v1.0.22: 5E739CFEF45C7C37107EE1EE9DF4EB5A42FBA187BBF461E6919167604D8D82A3

> v1.0.20: E93FE9AA41BA75BB29A9A6EA2CB150F803BDBA29D8BD0F6BBA7720A5B5E12D42

</details>

### 安装包 SHA1 校验
> v1.0.27: 8BF8DEDB236B1B7F15E51404A84566417B97CE1E

<details>
<summary>历史版本校验值（v1.0.20 – v1.0.26），点击展开</summary>

> v1.0.26: F9FA398F1E69E66AAF44821B9A0665445214CDDD

> v1.0.25: B4DE881FAA71776F1ABFAC634D1E0BA6AB172A03

> v1.0.24: 5D76A7BC15B10075E6AB770C40758FC4CA101664

> v1.0.23: 1EBB2315FB4B5AC288F0B30D0366413F51451181

> v1.0.22: 79AEB61599031CB7A4DF9228D03D389505EBAAF7

> v1.0.20: 84265AA9A8F623980E834CDF3D44B7DC41489B13

</details>

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
