# OpenFiles

**适用于 Windows 和 macOS 的 AI 原生文件工作区。**

在一个桌面工作区中打开、预览和处理 350+ 种文件格式。浏览文件夹、编辑支持的文档、自动化批处理，让 AI 助理参与日常文件工作。

[English](README.md) | 简体中文

[官网](https://openfiles.pansysoft.app/) · [下载](https://github.com/pansysoft/openfiles.desktop/releases/latest) · [使用文档](https://openfiles.pansysoft.app/docs/zh-CN) · [更新日志](https://openfiles.pansysoft.app/changelog)

此公开仓库用于提供桌面安装包、产品说明和问题反馈，不包含应用源代码。

## 下载与安装

| 平台 | 安装方式 |
| --- | --- |
| Windows | 从 [Microsoft Store](https://apps.microsoft.com/detail/9n34z0hxdtgk) 安装，或在 [GitHub Releases](https://github.com/pansysoft/openfiles.desktop/releases/latest) 下载 `.exe` 安装程序。发布附件也提供分别适用于 x64 和 ARM64 的 `.appx` 包。 |
| macOS — Apple Silicon | 在 [GitHub Releases](https://github.com/pansysoft/openfiles.desktop/releases/latest) 选择以 `-arm64.dmg` 结尾的安装包。 |
| macOS — Intel | 在 [GitHub Releases](https://github.com/pansysoft/openfiles.desktop/releases/latest) 选择名称中**不含** `-arm64` 的 `.dmg` 安装包。 |

macOS 用户打开磁盘映像后，将 OpenFiles 拖入“应用程序”。通过 Microsoft Store 安装的用户可在商店中检查更新。详细步骤见[安装与更新指南](https://openfiles.pansysoft.app/docs/zh-CN/installation)。

当前公开发行版提供 Windows 和 macOS 安装包，暂未发布 Linux 安装包。

## 一个工作区，处理日常文件

- **浏览与整理：** 浏览文件夹，切换文件视图，排序和分组，查看存储占用，复制或移动文件。
- **预览与多任务：** 选中文件后按空格快速预览；通过 Hub 查找工具、打开文件，并在标签页、分屏和多个窗口之间继续工作。
- **阅读与编辑：** 为文档、表格、Markdown、代码、图片、图表等提供专用工具；支持的文档视图可使用本地系统语音朗读正文。
- **批量处理：** 创建可复用的 `.ofw` 工作流，批量将 RAW 转为 JPG，或从实况照片中提取照片和视频。安装运行环境与模型后，还可使用背景移除、局部重绘、超分辨率等本地 AI 节点。
- **AI 辅助：** 围绕文件和文件夹对话，或选择支持相应能力的模型生成图片、视频和音频。可使用 OpenFiles 内置服务，也可配置自己的服务商。
- **十种界面语言：** 英语、简体中文、繁体中文、日语、韩语、德语、西班牙语、法语、葡萄牙语和俄语。

![OpenFiles 在 macOS 上的工作区](https://openfiles.pansysoft.app/docs/screenshots/workspace-macos.png)

*使用文档中的工作区示例。窗口控件和可用工具会随平台与版本有所不同。*

## 支持的文件格式

| 类别 | 示例 |
| --- | --- |
| 图片与摄影 | JPEG、PNG、WebP、SVG、HEIC/HEIF、JPEG XL、相机 RAW、实况照片、PSD |
| 文档与阅读 | PDF、OFD、Word 文档、演示文稿、Markdown、EPUB 等电子书 |
| 表格与数据 | XLSX、XLS、CSV、TSV、JSON、XML、YAML、SQLite |
| 视频与音频 | MP4、MOV、WebM、MP3、WAV、FLAC、MIDI |
| 代码与开发文件 | 源代码、脚本、配置文件、Jupyter Notebook |
| 图表与设计 | Mermaid、Graphviz、思维导图、调色板、Lottie、SVGA |
| CAD 与三维 | CAD 图纸、三维模型、点云 |
| 压缩包与专业数据 | ZIP、7z、RAR、TAR、日历、飞行日志、DJI 遥测、热成像 |

请在[可搜索的格式目录](https://openfiles.pansysoft.app/formats)中查看具体格式及关联工具。查看、编辑、转换和导出能力因格式而异；能打开文件不代表支持原应用的全部功能。

## 快速开始

1. 安装 OpenFiles，打开文件夹或文件。本地文件浏览和查看无需配置 AI 服务商。
2. 从顶部栏打开 **Hub**，查找工具或添加标签页。在文件浏览器中选中文件，按**空格**快速预览。
3. 使用**分屏**同时处理两组标签页，或将任务移到另一个窗口。
4. 使用 AI 时，登录以启用内置服务，或在 AI 设置中添加自己的服务商，再选择适合当前任务的模型。

常用指南：[工作区与窗口](https://openfiles.pansysoft.app/docs/zh-CN/workspace) · [与文件对话](https://openfiles.pansysoft.app/docs/zh-CN/chat-with-files) · [批处理工作流](https://openfiles.pansysoft.app/docs/zh-CN/batch-workflows) · [本地 AI 配置](https://openfiles.pansysoft.app/docs/zh-CN/local-ai)

## AI、隐私与额度

本地文件查看与编辑直接处理设备上的文件。**使用云端 AI 时，提示词及相关文件上下文会发送给所选服务。** 本地 AI 处理节点使用下载到本机的运行环境和模型；首次配置需要联网并占用磁盘空间。

内置 AI 服务使用 OpenFiles 额度（OFC）；自定义服务商使用相应服务商的凭据与计费方式。可用模型、能力和价格以当前界面为准。生成的媒体请保存到本地，因为远程交付链接可能过期。

进一步了解[内置 AI](https://openfiles.pansysoft.app/docs/zh-CN/builtin-ai)、[自定义服务商](https://openfiles.pansysoft.app/docs/zh-CN/custom-provider)和[隐私政策](https://openfiles.pansysoft.app/privacy)。

## 反馈与交流

- [GitHub Issues](https://github.com/pansysoft/openfiles.desktop/issues)：反馈缺陷或提出功能建议。请提供 OpenFiles 版本、操作系统与架构、复现步骤、预期结果和实际结果；条件允许时附上不含敏感信息的示例文件。
- [Discord](https://discord.gg/ebbukEgZ8k)：交流使用方法，分享反馈。
- [QQ 交流群](https://qm.qq.com/q/OPK3qSolW0)：加入 OpenFiles 中文用户社区。

公开提交前，请移除私人文件内容、API 密钥和个人信息。排查问题可参考[反馈指南](https://openfiles.pansysoft.app/docs/zh-CN/feedback)。
