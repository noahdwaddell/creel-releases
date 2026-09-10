# Creel
### *Just creel it.*

<p align="left">
  <a href="https://github.com/noahdwaddell/creel-releases/releases/latest"><img src="https://img.shields.io/badge/Version-1.2.1-2D6A4F?style=for-the-badge&logo=windows&logoColor=white" alt="Version 1.2.1" /></a>
  <img src="https://img.shields.io/badge/Privacy-100%25%20Offline-2D6A4F?style=for-the-badge&logo=shield&logoColor=white" alt="100% Offline" />
  <img src="https://img.shields.io/badge/Free%20Tier-Unlimited-40916C?style=for-the-badge" alt="Unlimited Free Tier" />
  <img src="https://img.shields.io/badge/Desktop%20Ads-Zero-52B788?style=for-the-badge" alt="Zero Ads" />
  <img src="https://img.shields.io/badge/Built%20With-Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Built with Flutter" />
</p>

A fast, **100% private, local file converter** for Windows. Convert documents, images, audio, and video — all on your own machine. **No uploads. No cloud servers. No ads.**

---

## 📥 Download
Grab the latest installer for your system:

| Platform | Build | Status | Download |
| :--- | :--- | :---: | :---: |
| 🪟 **Windows 10 / 11 (x64)** | `1.2.1` | 🟢 **Available** | [**📥 Download v1.2.1**](https://github.com/noahdwaddell/creel-releases/releases/download/v1.2.1/CreelSetup-1.2.1.exe) |
| 🍏 **macOS (Apple Silicon / Intel)** | `.dmg` | 🟡 Coming Soon | — |
| 🐧 **Linux (x64)** | `.deb` / `.AppImage` | 🟢 **Available** | [**📥 .deb**](https://github.com/noahdwaddell/creel-releases/releases/download/v1.2.1/creel_1.2.1_amd64.deb) / [**📥 AppImage**](https://github.com/noahdwaddell/creel-releases/releases/download/v1.2.1/Creel-1.2.1-x86_64.AppImage) |

> [!NOTE]
> The Windows installer is fully self-contained (~476 MB). All conversion engines (**LibreOffice, QPDF, Pandoc, FFmpeg, Tesseract OCR, and pdf2docx**) are bundled directly. No separate downloads, Python, or additional dependencies required.

---

## ✨ What's New in v1.2.1
- 🖱️ **Windows Explorer Right-Click Integration:** Convert files right from your Windows context menu (*Convert to PDF*, *Convert to Word DOCX*, *Convert to JPG/PNG*, *Convert to MP4*, or *Extract MP3*) in seconds without launching the app.
- 💻 **Headless / Silent CLI Mode:** Script conversions directly from PowerShell or Command Prompt (`creel --silent --convert <file> --to <format> [--out <dir>]`) with native Windows desktop toast notifications.
- ♾️ **Unlimited Free Tier:** Lifted daily quotas to unlimited conversions on desktop — convert as many files as you need, 100% offline with zero ads.
- 🔄 **In-App Auto Updater:** Checks GitHub releases on launch or on-demand from Settings, with one-click seamless background download and silent in-place installation.
- 📝 **PDF to Editable Word (DOCX):** High-fidelity document conversion from PDF back into formatted Microsoft Word (`.docx`) files using bundled offline sidecar tooling.
- 🛡️ **File Overwrite Protection:** Intelligent overwrite confirmation dialogs prevent accidental data loss.
- 🩺 **Integrated Diagnostics & Bug Reporting:** Fast diagnostic logging and in-app bug report generator accessible via Settings and About.
- 🧹 **Automated Cache & History Pruning:** Thumbnail cache auto-prunes files older than 7 days, and conversion history purges records older than 90 days to keep disk space lean.
- ⏱️ **Reliability & Timeouts:** Process safety timeouts on all conversion backends (Pandoc, LibreOffice, ImageMagick, pdf2docx) to eliminate hanging processes, plus larger hit targets on the PDF toolbar.

---

## ⚖️ Why Creel vs. Online Converters?
Most free online file converters upload your files to remote servers, queue your conversions, limit file sizes, and plaster ads on the screen. Creel does everything locally on your device.

| Feature | 🌐 Online Converters | 🛡️ Creel |
| :--- | :--- | :--- |
| 🔒 **Privacy & Security** | ❌ Uploaded to remote servers | 🟢 **100% on-device (Files never leave your PC)** |
| 📶 **Internet Required** | ❌ Yes (Mandatory) | 🟢 **Works 100% Offline** |
| 📦 **File Size Limit** | ⚠️ Usually 25MB – 100MB | 🟢 **Unlimited (Limited only by your hardware)** |
| ⚡ **Speed** | ⏳ Upload → Queue → Download | 🟢 **Instant local CPU / GPU processing** |
| 🚫 **Ads & Tracking** | 🪤 Heavy ads, trackers, captchas | 🟢 **Zero ads on desktop, zero telemetry** |
| 👤 **Accounts** | 📝 Often required | 🟢 **No account needed** |

---

## 🧰 Features

- 🖱️ **Windows Explorer Context Menu:** Right-click supported files directly in File Explorer to convert to PDF, DOCX, JPG, PNG, MP4, or extract MP3 in seconds without launching the app window.
- ⚡ **Drag & Drop Batch Queue:** Convert multiple files at once across different formats with real-time progress bars and queue controls (pause, resume, cancel).
- 📑 **All-in-One Offline Document Engine:** Convert Office documents (`.docx`, `.xlsx`, `.pptx`, `.odt`, `.ods`, `.odp`, `.txt`) to and from PDF without Microsoft Office installed.
- 📝 **PDF to Editable Word (DOCX):** Reverse document conversion from PDF into formatted Word documents with preserved tables and layout.
- 📐 **Advanced PDF Power Tools:**
  - 🔄 **Visual Page Organizer:** Interactive thumbnail grid to reorder, rotate (90° / 180° / 270°), or delete individual pages.
  - 📑 **Custom Layout Export:** Extract specific page ranges, merge multiple PDFs into one, split documents, or stamp custom text watermarks.
- 🎬 **Video & Audio Transcoder:**
  - 🎯 **One-Click Presets:** Fast 1080p, Discord Compression (under upload limits), High Quality 4K, and Audio Extractor (MP3).
  - 🎛️ Full manual control over resolution, CRF quality, codecs (H.264 / H.265 / VP9), bitrates, and audio channels.
- 🔍 **OCR Text Extraction:** Built-in Tesseract OCR engine with bundled language datasets to extract editable text from scanned documents and images.
- 💻 **Silent CLI & Scripting:** Headless conversion command-line interface with native Windows desktop notifications.
- 🔄 **In-App Updates & Diagnostics:** One-click updater to keep Creel up to date, plus integrated diagnostics to easily report bugs and export system status.
- 📂 **Output Flexibility:** Save converted files directly alongside the source file or route them to a custom destination directory.

---

## 📁 Supported Formats

- 📄 **Documents:** `DOCX`, `XLSX`, `PPTX`, `ODT`, `ODS`, `ODP`, `TXT` ↔ `PDF`
- 📑 **PDF Tools:** Merge, Split, Reorder Pages, Rotate, Delete Pages, Watermark, OCR, PDF → `DOCX`
- 🖼️ **Images:** `JPG`, `PNG`, `WEBP`, `GIF`, `TIFF`, `HEIC`, `BMP`
- 🎵 **Video & Audio:** `MP4`, `MKV`, `MOV`, `WEBM`, `MP3`, `AAC`, `WAV`, `FLAC`, `OGG`

---

## 💎 Free vs. Pro

| Feature | 🆓 Free Tier | 💎 Pro ($9.99 Flat Lifetime) |
| :--- | :---: | :---: |
| 🔄 **Conversions** | 🟢 **Unlimited** | 🟢 **Unlimited** |
| 📂 **All File Formats** | ✅ Included | ✅ Included |
| 🔒 **100% Offline & Private** | ✅ Included | ✅ Included |
| 🧰 **Batch Processing & PDF Tools** | ✅ Included | ✅ Included |
| 🖥️ **Desktop Experience** | ✨ **Zero ads** | ✨ **Zero ads** |
| 📱 **Mobile Experience** | 📢 Ad-supported (upon release) | 🛡️ **100% Ad-Free across all devices** |
| ⚡ **Batch Queue Concurrency** | 🏎️ Standard | 🚀 **High-Concurrency Accelerated Queues** |
| 🌟 **Updates & Support** | ✅ Lifetime Updates | 💖 **Lifetime Updates + Support Development** |

---

## 🚀 Quick Start

1. 📥 **Download:** Grab **`CreelSetup-1.2.1.exe`** from the [Releases](https://github.com/noahdwaddell/creel-releases/releases/latest) section.
2. ⚙️ **Install:** Run the installer (installs cleanly into your local user profile without requiring administrator privileges).
3. 🚀 **Convert via App:** Open Creel, drag & drop your files, choose your desired output format, and click **Convert**.
4. 🖱️ **Convert via Right-Click:** Right-click any file in Windows File Explorer and choose **Creel → Convert to PDF / Word / JPG / MP4** for instant conversions.

---

## 🏢 About

Developed by **[Ellijay Labs](https://ellijaylabs.com)**.  
Creel is built with Flutter and engineered for speed, privacy, and simplicity.
