# OpenFiles

**An AI-native file workspace for Windows and macOS.**

Open, preview, and work with 350+ file formats in one desktop workspace. Browse folders, edit supported documents, automate file processing, and bring an AI assistant into your file workflows.

English | [简体中文](README.zh-CN.md)

[Website](https://openfiles.pansysoft.app/) · [Download](https://github.com/pansysoft/openfiles.desktop/releases/latest) · [User guide](https://openfiles.pansysoft.app/docs/en) · [Changelog](https://openfiles.pansysoft.app/changelog)

This public repository provides desktop releases, product information, and issue tracking. It does not contain the application's source code.

## Download and install

| Platform | Installation |
| --- | --- |
| Windows | [Microsoft Store](https://apps.microsoft.com/detail/9n34z0hxdtgk), or the `.exe` installer from [GitHub Releases](https://github.com/pansysoft/openfiles.desktop/releases/latest). Architecture-specific x64 and ARM64 `.appx` packages are also included in the release assets. |
| macOS — Apple Silicon | Choose the `-arm64.dmg` asset from [GitHub Releases](https://github.com/pansysoft/openfiles.desktop/releases/latest). |
| macOS — Intel | Choose the `.dmg` asset **without** `-arm64` from [GitHub Releases](https://github.com/pansysoft/openfiles.desktop/releases/latest). |

On macOS, open the disk image and drag OpenFiles into Applications. For Microsoft Store installations, use the Store to check for updates. See the [installation guide](https://openfiles.pansysoft.app/docs/en/installation) for more details.

Current public releases provide Windows and macOS packages. Linux packages are not currently published.

## One workspace for everyday files

- **Browse and organize:** Navigate folders, switch between file views, sort and group items, inspect storage usage, and copy or move files.
- **Preview and multitask:** Press Space on a selected file for Quick Look. Use Hub to find tools and open files, then work across tabs, Split View, and multiple windows.
- **Read and edit:** Use dedicated tools for documents, spreadsheets, Markdown, code, images, diagrams, and more. Supported document views can read text aloud using local system voices.
- **Process files in batches:** Build reusable `.ofw` workflows, convert RAW photos to JPG, or extract photos and videos from Live Photos. Local AI nodes include background removal, inpainting, and upscaling after their runtime and models are installed.
- **Work with AI:** Chat about files and folders, or generate images, video, and audio with a capable model. Use the built-in OpenFiles service or configure your own provider.
- **Choose your language:** English, Simplified Chinese, Traditional Chinese, Japanese, Korean, German, Spanish, French, Portuguese, and Russian.

![OpenFiles workspace on macOS](https://openfiles.pansysoft.app/docs/screenshots/workspace-macos.png)

*Workspace example from the user guide. Window controls and available tools vary by platform and version.*

## Supported formats

| Category | Examples |
| --- | --- |
| Images and photography | JPEG, PNG, WebP, SVG, HEIC/HEIF, JPEG XL, camera RAW, Live Photos, PSD |
| Documents and reading | PDF, OFD, Word documents, presentations, Markdown, EPUB and other ebooks |
| Spreadsheets and data | XLSX, XLS, CSV, TSV, JSON, XML, YAML, SQLite |
| Video and audio | MP4, MOV, WebM, MP3, WAV, FLAC, MIDI |
| Code and developer files | Source code, scripts, configuration files, Jupyter notebooks |
| Diagrams and design | Mermaid, Graphviz, mind maps, color palettes, Lottie, SVGA |
| CAD and 3D | CAD drawings, 3D models, point clouds |
| Archives and specialist data | ZIP, 7z, RAR, TAR, calendars, flight logs, DJI telemetry, thermal images |

See the [searchable format catalog](https://openfiles.pansysoft.app/formats) for individual formats and their tools. Viewing, editing, conversion, and export capabilities vary by format; support for opening a file does not mean every feature of its original application is supported.

## Get started

1. Install OpenFiles and open a folder or file. Local file browsing and viewing do not require an AI provider.
2. Open **Hub** from the top bar to find a tool or add a tab. Select a file in the browser and press **Space** for a quick preview.
3. Use **Split View** to work with two tab groups, or move work into another window.
4. For AI, sign in to use the built-in provider, or add your own provider in AI Settings. Choose a model suited to the task.

Useful guides: [Workspace and windows](https://openfiles.pansysoft.app/docs/en/workspace) · [Chat with files](https://openfiles.pansysoft.app/docs/en/chat-with-files) · [Batch workflows](https://openfiles.pansysoft.app/docs/en/batch-workflows) · [Local AI setup](https://openfiles.pansysoft.app/docs/en/local-ai)

## AI, privacy, and credits

Local file viewing and editing operate on files on your device. **Cloud AI requests send your prompts and relevant file context to the selected service.** Local AI processing nodes use downloaded runtimes and models; their initial setup requires network access and storage.

The built-in AI service uses OpenFiles credits (OFC). Your own provider uses that provider's credentials and billing. Available models, capabilities, and prices are shown in the current interface. Save generated media locally because remote delivery links can expire.

Read about [built-in AI](https://openfiles.pansysoft.app/docs/en/builtin-ai), [custom providers](https://openfiles.pansysoft.app/docs/en/custom-provider), and the [privacy policy](https://openfiles.pansysoft.app/privacy).

## Feedback and community

- [GitHub Issues](https://github.com/pansysoft/openfiles.desktop/issues): Report bugs or request features. Include your OpenFiles version, operating system and architecture, reproduction steps, and the expected and actual results. Attach a non-sensitive sample when possible.
- [Discord](https://discord.gg/ebbukEgZ8k): Discuss workflows and share feedback with the community.
- [QQ group](https://qm.qq.com/q/OPK3qSolW0): Join the Chinese-language OpenFiles community.

Please remove private file contents, API keys, and personal information from public reports. See the [feedback guide](https://openfiles.pansysoft.app/docs/en/feedback) for troubleshooting details.
