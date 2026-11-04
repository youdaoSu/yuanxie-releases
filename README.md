# 远协 · 客户端下载

**当前版本：0.20.4** · [查看发布说明与全部附件](https://github.com/youdaoSu/yuanxie-releases/releases/tag/v0.20.4)

正式入口：[yuanxie.hengyuan.team](https://yuanxie.hengyuan.team)。新版客户端默认连接此入口，并验证服务器签名。旧客户端如仍连接旧 Pages 地址，请先下载新版；用户主动填写的自定义服务器设置会保留。

| 电脑 | 安装包 | 安装方式 |
| --- | --- | --- |
| Windows x64（Intel / AMD） | [Windows 0.20.4 ZIP](https://github.com/youdaoSu/yuanxie-releases/releases/download/v0.20.4/YuanXie-Desktop-0.20.4-Windows-x64.zip) | 完整解压后运行 YuanXie.exe，保留包内其他文件 |
| Mac Apple Silicon（M 系列） | [macOS 0.20.4 ARM64 DMG](https://github.com/youdaoSu/yuanxie-releases/releases/download/v0.20.4/YuanXie-Desktop-0.20.4-macOS-arm64.dmg) | 将 YuanXie.app 复制到「应用程序」后打开 |
| Ubuntu / Debian x64（暂停更新） | [Linux 0.20.2 x64 DEB](https://github.com/youdaoSu/yuanxie-releases/releases/download/v0.20.2/YuanXie-Desktop-0.20.2-Linux-x64.deb) | 使用系统软件安装器；其他附件见 0.20.2 发布页 |

每份安装包提供同名 SHA-256 校验文件。Windows 与 Mac ZIP 另附更新块清单。当前不提供 Intel Mac、Linux ARM64 安装包。

官网直连下载：[Windows 0.20.4 ZIP](https://yuanxie.hengyuan.team/downloads/YuanXie-Desktop-0.20.4-Windows-x64.zip) · [Mac 0.20.4 DMG](https://yuanxie.hengyuan.team/downloads/YuanXie-Desktop-0.20.4-macOS-arm64.dmg)。同名校验文件可在下载地址后追加 `.sha256` 获取。

## 本版功能与限制

| 功能 | 当前情况 |
| --- | --- |
| 共享面板、文字协作 | 提供邀请链接／房间号、文件管理、字号按钮与 Ctrl＋滚轮；透明视图沿用字号 |
| 会议与共享 | 提供麦克风、摄像头、屏幕共享及共享声音；由操作系统权限、设备及所选音源支持情况决定是否可用 |
| 设备请求与远程协助 | 可请求成员开启设备；远程键鼠操作须对方同意，保留可见状态与停止入口 |
| 个人语音助手 | 可选择本机麦克风、系统声音或经成员同意的会议音源；支持识别语言、热词及指定成员问答分享 |
| 本场简历与岗位 JD | 每位成员可填写临时材料或导入 TXT／MD；使用他人材料须来源本人确认，修改后需重新同意，可撤回 |
| 文字记录与复盘 | 可导出 Word 面经、复盘；原始转写及 AI 内容需要人工核对，不保证识别和回答完全正确 |
| 窗口捕获保护 | 取决于系统及捕获方式，不保证所有录屏中均排除窗口或无黑框；Linux 不支持防录屏 |

语音助手需要发起者配置有效的模型服务凭据，调用费用按服务商规则计算。临时简历和 JD 不自动保存为长期个人档案；分享回答前请核对其中的个人信息。

## Mac 安装说明

当前 Mac 包使用开发签名，**尚未经过 Apple Developer ID 签名与公证**。系统可能要求手动确认打开，以及重新确认录屏、系统声音、麦克风、摄像头或辅助功能权限。请只针对本应用按系统提示处理，不关闭全局安全检查。新旧签名应用之间不保证自动继承权限。

GitHub 下载受所在网络影响；能够打开官网不表示所有网络均能直接下载 GitHub 附件。

## Linux 维护安排

Linux 桌面保留 0.20.2 下载，暂不继续更新；Windows、macOS 与网页／云端继续维护。保留版如仍连接旧 Pages 地址，请在服务器设置中手动填写 `https://yuanxie.hengyuan.team`，也可使用网页版。Linux 默认快捷键为主窗口 Ctrl＋Shift＋F12、透明 Ctrl＋Shift＋F11、会议 Ctrl＋Shift＋F10、问答 Ctrl＋Shift＋F9，可在设置中调整。全局快捷键是否可用取决于桌面环境。

此仓库仅分发安装包、校验文件和说明，应用源码保持私有。历史安装包的旧服务器不作为推荐入口。
