# Dimoo-rich 👋

[中文](#中文) · [English](#english)

## 中文

你好，我是 Dimoo-rich。和 AI 一起做实用小工具，记录从想法、反复修改到发布的过程。

这里放我公开的项目、使用说明和下载入口。

### 我的项目

#### MSG · MacSpaceGuard

一个完全本地运行的 Mac 菜单栏工具：

- 查看内存与磁盘状态。
- 查看指定范围的旧缓存及风险提示，手动选择并确认后移到废纸篓。
- 检查下载的 DMG / PKG 安装包，手动选择并确认后移到废纸篓；不会卸载应用。

**[下载与版本说明](https://github.com/Dimoo-rich/MacSpaceGuard/releases/tag/v1.0.0-beta.2)** · [查看项目源码](https://github.com/Dimoo-rich/MacSpaceGuard) · [安装说明](https://github.com/Dimoo-rich/MacSpaceGuard/blob/main/docs/INSTALL.md) · [问题反馈](https://github.com/Dimoo-rich/MacSpaceGuard/issues)

目前为 **1.0.0-beta.2 公开测试版**，不是稳定正式版。仅面向 Apple Silicon（M 系列）Mac，界面为中文。尚未完成另一台 Mac 和最低系统版本的实测，也未经 Apple 公证，首次打开可能需要按安装说明处理系统提示。

风险提示不代表绝对安全，拿不准的文件请保留。工具不自动清空废纸篓；移入的文件仍占用空间，需要你自行检查并清空后才会释放。

#### PicBatchKit · 批量图片处理

在浏览器里整理发布前的整组配图，无需安装：

- 统一为 3:4 或 1:1，支持居中裁剪和白色留边。
- 批量调整尺寸、格式和文件大小。
- 调整顺序，按 01、02 编号，单张下载或 ZIP 打包。
- 提供 Codex Skill，可用自然语言批量处理本地图片。

**[在线使用](https://dimoo-rich.github.io/PicBatchKit/)** · [查看项目源码](https://github.com/Dimoo-rich/PicBatchKit) · [下载 Skill](https://dimoo-rich.github.io/PicBatchKit/image-compressor-skill.zip) · [使用说明](https://dimoo-rich.github.io/PicBatchKit/%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E.html) · [问题反馈](https://github.com/Dimoo-rich/PicBatchKit/issues)

图片在本地处理，不上传服务器。裁剪可能切掉边缘内容，处理后请检查预览；手机真机体验仍待验证。

### 交流与反馈

有问题或建议，欢迎到对应项目的 Issues 留言。提交截图前，请隐藏私人文件名、路径和其他个人信息。

[查看全部公开项目](https://github.com/Dimoo-rich?tab=repositories)

---

## English

Hi, I’m Dimoo-rich. I build practical tools with AI and share the journey from an idea, through repeated refinements, to release.

This page brings together my public projects, documentation and downloads.

### My projects

#### MSG · MacSpaceGuard

A local-only macOS menu bar tool that helps you:

- Check memory and disk status.
- Review old cache files within supported locations and their risk explanations, then manually select and confirm files to move to Trash.
- Inspect downloaded DMG / PKG installers, then manually select and confirm files to move to Trash. This does not uninstall applications.

**[Download and release notes](https://github.com/Dimoo-rich/MacSpaceGuard/releases/tag/v1.0.0-beta.2)** · [Source code](https://github.com/Dimoo-rich/MacSpaceGuard) · [Installation guide](https://github.com/Dimoo-rich/MacSpaceGuard/blob/main/docs/INSTALL.en.md) · [Report an issue](https://github.com/Dimoo-rich/MacSpaceGuard/issues)

The current version is **1.0.0-beta.2, a public beta**, not a stable release. It targets Apple Silicon (M-series) Macs and has a Chinese-language interface. Testing on a second Mac and the minimum supported OS version is still pending. The app is not notarized by Apple; follow the installation guide if macOS displays a first-launch warning.

Risk labels do not guarantee safety. Keep any files you are unsure about. The tool does not automatically empty Trash. Files moved there still take up disk space until you review and empty Trash yourself.

#### PicBatchKit · Batch image preparation

A browser-based tool for preparing a set of images before posting:

- Crop to 3:4 or 1:1, or keep the full image with white padding.
- Batch resize, convert formats and set a target file size.
- Reorder, number files as 01 / 02, and download individually or as a ZIP.
- Includes a Codex Skill for processing local images with natural-language instructions.

**[Use online](https://dimoo-rich.github.io/PicBatchKit/)** · [Source code](https://github.com/Dimoo-rich/PicBatchKit) · [Download Skill](https://dimoo-rich.github.io/PicBatchKit/image-compressor-skill.zip) · [Report an issue](https://github.com/Dimoo-rich/PicBatchKit/issues)

Images are processed locally, without uploading them to a server. Review cropped images before downloading. Real-device mobile testing is still pending.

### Questions and feedback

For questions or suggestions, please use the relevant project’s Issues page. Hide private filenames, paths and other personal information before submitting screenshots.

[Explore all public projects](https://github.com/Dimoo-rich?tab=repositories)
