# 远协 · 客户端下载

**当前版本：0.20.8** · [查看最新发布说明与全部附件](https://github.com/youdaoSu/yuanxie-releases/releases/latest)

正式入口：[yuanxie.hengyuan.team](https://yuanxie.hengyuan.team)。新版客户端默认连接此入口，并验证服务器签名。旧客户端如仍连接旧 Pages 地址，请先下载新版；用户主动填写的自定义服务器设置会保留。

| 电脑 | 安装包 | 安装方式 |
| --- | --- | --- |
| Windows x64（Intel / AMD） | [Windows 0.20.8 EXE 安装包](https://github.com/youdaoSu/yuanxie-releases/releases/download/v0.20.8/YuanXie-0.20.8-Windows-x64.exe) | 双击安装；再次运行新版安装包可覆盖升级；系统「已安装的应用」中卸载 |
| Mac Apple Silicon（M 系列） | [macOS 0.20.8 ARM64 PKG 安装包](https://github.com/youdaoSu/yuanxie-releases/releases/download/v0.20.8/YuanXie-0.20.8-macOS-arm64.pkg) · [DMG](https://github.com/youdaoSu/yuanxie-releases/releases/download/v0.20.8/YuanXie-Desktop-0.20.8-macOS-arm64.dmg) | PKG 安装到「应用程序／远协.app」，新版可覆盖升级；退出应用后移至废纸篓卸载 |
| Ubuntu / Debian x64（暂停更新） | [Linux 0.20.2 x64 DEB](https://github.com/youdaoSu/yuanxie-releases/releases/download/v0.20.2/YuanXie-Desktop-0.20.2-Linux-x64.deb) | 使用系统软件安装器；其他附件见 0.20.2 发布页 |

每份安装包提供同名 SHA-256 校验文件。Windows 安装和卸载仅处理程序文件，保留用户设置。Mac PKG 尚无 Apple Installer 签名，应用沿用开发签名，尚未通过 Apple 公证。Linux 在软件管理器安装、更新和卸载。内部兼容更新仍保留 ZIP 与更新块清单，不作为默认人工安装方式。当前不提供 Intel Mac、Linux ARM64 安装包。

校验文件：[Windows EXE SHA-256](https://github.com/youdaoSu/yuanxie-releases/releases/download/v0.20.8/YuanXie-0.20.8-Windows-x64.exe.sha256) · [Mac PKG SHA-256](https://github.com/youdaoSu/yuanxie-releases/releases/download/v0.20.8/YuanXie-0.20.8-macOS-arm64.pkg.sha256) · [Mac DMG SHA-256](https://github.com/youdaoSu/yuanxie-releases/releases/download/v0.20.8/YuanXie-Desktop-0.20.8-macOS-arm64.dmg.sha256)。

## 本版功能与限制

| 功能 | 当前情况 |
| --- | --- |
| 共享面板、文字协作 | 创建时设定开放时间与有效期，支持预约。普通用户可创建 15 分钟试用面板。软件内通过固定 12 位房间号加入。面板到期或创建者主动离开后回收房间号。保留文件管理与字号调整。 |
| 会议与共享 | 提供麦克风、摄像头、屏幕共享及共享声音；由操作系统权限、设备及所选音源支持情况决定是否可用 |
| 设备请求与远程协助 | 可请求成员开启设备；远程键鼠操作须对方同意，保留可见状态与停止入口 |
| 个人语音助手 | 可选择本机麦克风、系统声音或经成员同意的会议音源；支持识别语言、热词及指定成员问答分享 |
| 本场简历与岗位 JD | 每位成员可填写临时材料或导入 PDF／DOCX／ODT／TXT／MD，单份上限 20 MiB；使用他人材料须来源本人确认，修改后需重新同意，可撤回 |
| 文字记录与复盘 | 可导出 Word 面经、复盘，并按管理员配置保存到飞书；原始转写及 AI 内容需要人工核对，不保证识别和回答完全正确 |
| 会议录制 | 可选择系统声音与麦克风，结束时选择本地保存位置 |
| 窗口捕获保护 | 取决于系统及捕获方式，不保证所有录屏中均排除窗口或无黑框；Linux 不支持防录屏 |

语音服务与回答在共享面板顶部「语音问答」统一设置和查看。成员可使用自己的有效模型凭据，也可由创建者明确授权共用本场服务；调用费用计入所选服务账号。临时简历和 JD 不自动保存为长期个人档案；分享回答前请核对其中的个人信息。

## Mac 安装说明

当前 Mac 包使用开发签名，**尚未经过 Apple Developer ID 签名与公证**。系统可能要求手动确认打开，以及重新确认录屏、系统声音、麦克风、摄像头或辅助功能权限。请只针对本应用按系统提示处理，不关闭全局安全检查。新旧签名应用之间不保证自动继承权限。

GitHub 下载受所在网络影响；能够打开官网不表示所有网络均能直接下载 GitHub 附件。

## Linux 维护安排

Linux 桌面保留 0.20.2 下载，暂不继续更新；Windows、macOS 与网页／云端继续维护。保留版如仍连接旧 Pages 地址，请在服务器设置中手动填写 `https://yuanxie.hengyuan.team`，也可使用网页版。Linux 默认快捷键为主窗口 Ctrl＋Shift＋F12、透明 Ctrl＋Shift＋F11、会议 Ctrl＋Shift＋F10、问答 Ctrl＋Shift＋F9，可在设置中调整。全局快捷键是否可用取决于桌面环境。

此仓库仅分发安装包、校验文件和说明，应用源码保持私有。历史安装包的旧服务器不作为推荐入口。

