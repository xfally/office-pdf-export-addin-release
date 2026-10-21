# Office PDF Export

> **Convert Word, Excel & PowerPoint to PDF** — with custom text watermarks, non-editable (scanned) output, and searchable double-layer PDFs.
> **100% offline & private: your documents never leave your computer.** Free, no account, no internet required.

**[English](#english) | [中文](#中文)**

---

<a id="english"></a>

## English

Office PDF Export is a free add-in for Microsoft Word, PowerPoint, and Excel that converts your documents to PDF — with custom text watermarks, an optional "scanned" mode that produces non-editable PDFs, and a double-layer mode that produces scanned-style PDFs that remain searchable and copyable.

Unlike online PDF converters, **everything runs locally on your own computer, inside Microsoft Office**. Your documents are never uploaded to any server.

### 🔒 Privacy First — Your Files Never Leave Your PC

Most online converters (SmallPDF, iLovePDF, and similar) require you to **upload your documents to their servers** before processing. This add-in does not.

- **No upload** — documents are processed entirely on your machine
- **No internet required** — works fully offline, even in air-gapped environments
- **No account, no login** — nothing is tracked or associated with you
- **No telemetry, no data collection** — the add-in makes no network requests during normal use

> Ideal for **contracts, financial records, legal documents, medical files, and any confidential material** you would never trust to an online service.

### ✨ Key Features

- 🆓 **Free & unlimited** — no subscription, no per-file fee, no file-size cap, no third-party watermark added
- 💧 **Custom text watermark** — your own text, font, size, color, opacity, rotation angle; tiled or single layout
- 🖼️ **Non-editable scanned PDF** — export as image-based PDF (DPI 150 / 200 / 300) so recipients cannot edit or copy the content
- 🔍 **Searchable double-layer PDF** — image layer + aligned hidden text layer (local OCR): looks like a scan, stays searchable/copyable; optional auto bookmarks, black-white binarization, permission encryption, read-only attribute
- 👁️ **Live preview** — see the watermark exactly as it will appear before exporting
- ⚡ **Quick export** — one-click plain PDF (no watermark, no scan mode)
- 🖱️ **Windows Explorer right-click menu** — Right-click any `.docx` / `.xlsx` / `.pptx` to Quick Export, Export with Watermark, or Export as Double-Layer PDF, without opening Office
- 🌐 **Bilingual** — English + Chinese (auto-detects Office language, switchable manually)
- 📦 **Three apps in one** — Word + PowerPoint + Excel

### 🎯 Use Cases

- Convert a **Word document to PDF** and add a confidential watermark
- Convert an **Excel spreadsheet to PDF** for sharing
- Convert a **PowerPoint presentation to PDF**
- **Make a PDF non-editable** so it cannot be modified or copied
- **Protect confidential documents** with a watermark before sending
- **Prepare tender/bid documents** as searchable double-layer PDFs (scanned look, copyable text)

### 📥 Download & Install

1. Go to the [Releases](../../releases) page and download the latest installer `OfficePdfExportSetup-0.2.0.exe`
2. Run the installer (requires administrator / UAC elevation once)
3. Restart Word / PowerPoint / Excel after installation
4. A "Office PDF Export" tab will appear in the ribbon

### 📖 How to Use

1. Open a Word document, PowerPoint presentation, or Excel workbook
2. Click the "Office PDF Export" tab in the ribbon
3. **Quick Export**: click "Quick Export" to generate a plain PDF directly
4. **Watermark Export**: click "Watermark Export" to open the preview window
   - Configure the watermark (text, font, color, opacity, angle, layout)
   - Check "Scanned PDF" for non-editable output (optional binarization)
   - Read-only / permission-encryption options apply to every export mode (off by default)
   - Click "Export PDF" to generate the file
5. **Double-Layer PDF**: click "Export Double-Layer PDF" for a scanned-style PDF that stays searchable and copyable (local OCR; optional bookmarks / encryption)

### 🖱️ Via Windows Explorer Right-Click Menu

1. In Windows Explorer, right-click any `.docx` / `.xlsx` / `.pptx` file
2. Select **Office PDF Export ▶** (a cascading submenu)
3. Choose **Quick Export to PDF** (plain PDF), **Export with Watermark** (configure first), or **Export as Double-Layer PDF** (searchable scanned-style)
4. Pick the output location / configure options in the dialogs

### 🗑️ Uninstall

- **Control Panel** → Programs and Features → find "Office PDF Export" → Uninstall
- **Start Menu** → Office PDF Export → "Uninstall Office PDF Export"

All COM registrations and registry entries are removed automatically. Restart Office after uninstalling.

### 💻 System Requirements

- Windows 10 / 11
- Microsoft Office 2019 / 2021 / 365 (32-bit or 64-bit)
- .NET Framework 4.8 Runtime

### ❓ FAQ

**Does this tool upload my documents?**
No. All processing happens locally on your computer. Your files never leave your machine.

**Is it free?**
Yes — completely free, with no subscription, no hidden fees, and no usage limits.

**Does it need an internet connection?**
No. It works fully offline.

**Do I need to create an account?**
No account or login is required.

**How is this different from online converters?**
Online converters upload your file to a server for processing. This add-in processes everything locally, so your documents are never transmitted anywhere — better for privacy and sensitive files.

**Which Office versions are supported?**
Microsoft Office 2019, 2021, and 365 (both 32-bit and 64-bit).

**Does it support WPS Office?**
No — Microsoft Office only.

**What is a double-layer PDF?**
A PDF that looks like a scan (page images, not editable) but carries an invisible, aligned text layer underneath — so it stays searchable and copyable. Ideal for tender/bid submissions that require "scanned" documents while keeping the text retrievable.

### 📄 License

This Project: Proprietary — All Rights Reserved

### 👤 Author

pax (coolwinding@foxmail.com)

### ⚠️ Known Limitations

- Currently supports text watermarks only (image watermarks planned for future versions)
- Supports Microsoft Office only (no WPS Office)
- Windows platform only
- Double-layer bookmarks are heuristic (off by default); read-only / encryption options may affect downstream e-seal tools (off by default)

---

<a id="中文"></a>

## 中文

Office PDF Export 是一款免费的 Microsoft Word、PowerPoint、Excel 插件，可将文档转换为 PDF——支持自定义文字水印、生成不可编辑的「扫描式」PDF，以及生成仍可搜索复制的「双层」PDF。

与在线 PDF 转换工具不同，**所有处理都在你自己的电脑上、由 Microsoft Office 本地完成**。你的文档绝不会上传到任何服务器。

### 🔒 隐私优先 —— 文档永不离开你的电脑

大多数在线转换工具（SmallPDF、iLovePDF 等）都需要你**把文档上传到它们的服务器**才能处理。本插件不会。

- **不上传** —— 文档完全在本机处理
- **无需联网** —— 完全离线可用，支持内网 / 隔离环境
- **无需注册账号** —— 不追踪、不关联你的身份
- **无遥测、不收集数据** —— 正常使用过程中插件不发起任何网络请求

> 非常适合**合同、财务、法律、医疗等各类机密文档**——这些文件你绝不会放心交给在线服务处理。

### ✨ 核心特性

- 🆓 **免费·无限制** —— 无订阅、无按次收费、无文件大小上限、不添加任何第三方水印
- 💧 **自定义文字水印** —— 自定义文字、字体、大小、颜色、透明度、倾斜角度；平铺或单个布局
- 🖼️ **不可编辑的扫描式 PDF** —— 导出为图片式 PDF（DPI 150 / 200 / 300），他人无法编辑或复制内容
- 🔍 **可搜索双层 PDF** —— 图像层+对齐隐藏文字层（本地 OCR）：看起来是扫描件，仍可搜索/复制；可选自动书签、黑白二值化、权限加密、只读属性
- 👁️ **实时预览** —— 导出前所见即所得地查看水印效果
- ⚡ **快速导出** —— 一键生成纯 PDF（无水印、无扫描模式）
- 🖱️ **Windows 资源管理器右键菜单** —— 在任意 `.docx` / `.xlsx` / `.pptx` 文件上右键即可快速导出、带水印导出或导出双层 PDF，无需打开 Office
- 🌐 **中英双语** —— 自动检测 Office 语言，可手动切换
- 📦 **三合一** —— Word + PowerPoint + Excel

### 🎯 适用场景

- **Word 文档转 PDF** 并添加机密水印
- **Excel 表格转 PDF** 便于分享
- **PPT 演示文稿转 PDF**
- **生成不可编辑的 PDF**，防止被修改或复制
- 发送前**为机密文档加水印保护**
- **编制投标响应文件**：生成可搜索的双层 PDF（扫描件外观 + 可复制文字）

### 📥 下载安装

1. 前往 [Releases](../../releases) 页面下载最新版安装包 `OfficePdfExportSetup-0.2.0.exe`
2. 双击运行安装程序（需要管理员权限/UAC 提权一次）
3. 安装完成后重启 Word / PowerPoint / Excel
4. 功能区将出现「Office PDF 导出」选项卡

### 📖 使用说明

1. 打开一个 Word 文档、PPT 演示文稿或 Excel 工作簿
2. 点击功能区中的「Office PDF 导出」选项卡
3. **快速导出**：点击「快速导出」直接生成纯 PDF
4. **水印导出**：点击「水印导出」打开预览窗口
   - 配置水印（文字、字体、颜色、透明度、角度、布局）
   - 如需不可编辑的输出，勾选「扫描式 PDF」模式（可选黑白二值化）
   - 只读属性 / 权限加密对所有导出模式生效（均默认关）
   - 点击「导出 PDF」生成文件
5. **双层导出**：点击「双层导出」打开双层导出对话框，由本地 OCR 生成扫描件外观但可搜索复制的 PDF（可选书签/加密）

### 🖱️ 通过 Windows 资源管理器右键菜单

1. 在文件资源管理器中右键点击任意 `.docx` / `.xlsx` / `.pptx` 文件
2. 选择 **Office PDF 导出 ▶**（级联子菜单）
3. 在子菜单中选择**快速导出 PDF**（纯 PDF）、**带水印导出**（先配置水印再导出）或**导出双层 PDF**（可搜索扫描式）
4. 在对应对话框中配置并选择输出位置

### 🗑️ 卸载

- **控制面板**：程序和功能 → 找到 "Office PDF Export" → 卸载
- **开始菜单**：Office PDF Export → "Uninstall Office PDF Export"

卸载程序会自动清理所有 COM 注册和注册表条目。卸载后重启 Office 即可。

### 💻 系统要求

- Windows 10 / 11
- Microsoft Office 2019 / 2021 / 365（32-bit 或 64-bit 均可）
- .NET Framework 4.8 Runtime

### ❓ 常见问题

**这个工具会上传我的文档吗？**
不会。所有处理都在你的电脑本地完成，文档绝不离开你的设备。

**它是免费的吗？**
是——完全免费，无订阅、无隐藏费用、无使用次数限制。

**需要联网吗？**
不需要，完全离线可用。

**需要注册账号吗？**
不需要任何账号或登录。

**和在线转换工具有什么区别？**
在线工具需要把文件上传到服务器处理；本插件全部在本地处理，文档不会被传输到任何地方——更保护隐私，适合敏感文件。

**支持哪些 Office 版本？**
Microsoft Office 2019、2021、365（32-bit 和 64-bit 均支持）。

**支持 WPS 吗？**
不支持，仅支持 Microsoft Office。

**什么是双层 PDF？**
一种看起来是扫描件（页面图像、不可编辑）但内含对齐隐藏文字层的 PDF——保持可搜索、可复制。适合要求"扫描件"形态又需要文字可检索的投标/归档场景。

### 📄 许可证

本项目: Proprietary — All Rights Reserved

### 👤 作者

pax (coolwinding@foxmail.com)

### ⚠️ 已知限制

- 目前仅支持文字水印（图片水印计划在后续版本中添加）
- 仅支持 Microsoft Office（不支持 WPS）
- 仅支持 Windows 平台
- 双层 PDF 书签为启发式识别（默认关）；只读/加密选项可能影响下游电子签章工具（默认关）
