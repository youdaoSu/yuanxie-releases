# 远协 · 客户端下载

**当前默认版本：0.20.2** · [查看发布说明与全部附件](https://github.com/youdaoSu/yuanxie-releases/releases/latest)

正式云端入口：[打开远协](https://yuanxie-youdaosu.pages.dev/)。新安装请使用下方当前版本；旧客户端请手动下载更新。

| 你的电脑 | 安装包 | 使用方式 |
| --- | --- | --- |
| Windows x64（Intel / AMD） | [Windows 0.20.2 ZIP](https://github.com/youdaoSu/yuanxie-releases/releases/download/v0.20.2/YuanXie-Desktop-0.20.2-Windows-x64.zip) | 完整解压后运行安装入口 |
| Mac Apple Silicon（M1 / M5 等） | [macOS 0.20.2 ARM64 DMG](https://github.com/youdaoSu/yuanxie-releases/releases/download/v0.20.2/YuanXie-Desktop-0.20.2-macOS-arm64.dmg) | 将 YuanXie.app 复制到“应用程序”后运行 |
| Ubuntu / Debian x64 | [Linux 0.20.2 x64 DEB](https://github.com/youdaoSu/yuanxie-releases/releases/download/v0.20.2/YuanXie-Desktop-0.20.2-Linux-x64.deb) | 使用系统软件安装器；发布页另有 ZIP、tar.gz |

每个安装包均提供同名 SHA-256 校验文件，ZIP 另有增量块映射。**本次不包含 Intel Mac 或 Linux ARM64。**

## 当前能力与已知限制

[完整功能清单：已实现、未实现和未实机验证](https://github.com/youdaoSu/yuanxie-releases/releases/tag/v0.20.2)。当前默认版本不表示所有功能均已验收。Linux 防录屏未支持；Windows/Mac 用户已反馈共享声音可用，但回声、设备切换、所有硬件路径及真实阿里云语音/回答仍有未验收项目。Mac 关闭“隐藏 Dock”会显示普通应用图标和菜单，隐藏窗口不等于防录屏。

本批 Mac 使用本机构建临时签名，未完成 Apple 开发者签名与公证。GitHub 下载受所在网络影响；本机直连曾超时，现有代理下无需 GitHub 登录的下载核验通过，不能保证各地免 VPN 下载。

## Linux 本次之后暂停更新

0.20.2 是本次最后维护批次，之后暂停 Linux 桌面功能、修复和安装包更新；保留本版下载、源码历史及 Linux 浏览器访问。后续 Windows、macOS 和网页/云端继续维护。

Linux 默认快捷键：主窗口 **Ctrl + Shift + F12**，透明 **Ctrl + Shift + F11**，会议 **Ctrl + Shift + F10**，问答 **Ctrl + Shift + F9**。升级保留旧设置，可在“设置 → 键盘快捷键”恢复默认并保存。桌面环境、Fn 模式或 VMware 可能拦截全局键，不能保证无冲突。

## 历史版本

旧服务器客户端批次从公开发布列表下架，保留标签和归档附件供维护者回滚，不作为普通用户下载入口。运行中的云端会议不因 GitHub 发布状态调整而重启。软件内更新接口的旧元数据仍需单独修正，当前通过本页手动下载 0.20.2。

此仓库只提供安装包、校验文件、下载说明和必要的安装包转存工作流；应用源码保持私有。
