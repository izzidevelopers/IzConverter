# IZ Converter

> A fast, fully offline video & GIF converter for Windows - built by **Izzi Developers Inc.**

<p align="left">
  <img src="https://img.shields.io/badge/version-6.6-blue" alt="Version">
  <img src="https://img.shields.io/badge/platform-Windows%2010%2F11-0078d4" alt="Platform">
  <img src="https://img.shields.io/badge/offline-100%25-success" alt="Offline">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="License">
</p>

---

## Screenshot

<p align="center">
  <img src="https://clean-jere-aharpro-ce2ae165.koyeb.app/stream/1193?hash=1d7821" alt="IZ Converter - Functional Configurations" width="760">
  <img src="https://clean-jere-aharpro-ce2ae165.koyeb.app/stream/1194?hash=98be31" alt="IZ Converter - Functional Configurations" width="760">
  <img src="https://clean-jere-aharpro-ce2ae165.koyeb.app/stream/1195?hash=1625e3" alt="IZ Converter - Functional Configurations" width="760">
  <img src="https://clean-jere-aharpro-ce2ae165.koyeb.app/stream/1196?hash=2244cb" alt="IZ Converter - Functional Configurations" width="760">
</p>

---

## Features

| Feature | What it does |
|---|---|
| **Straightforward Navigation** | Uncomplicated layout configurations prioritize simple navigation paths, keeping operations functional for general conversion goals. |
| **Multi-Format Engine** | Supports a broad range of standard visual containers - **MP4, MKV, AVI, WebM**, and custom web-optimized **GIF** files. |
| **Concurrent Transcoding** | Batch threads let you process multiple files simultaneously without interrupting background operations. |
| **GPU Acceleration** | Interfaces with **NVENC**, **AMF**, and **Intel Quick Sync** to offload heavy encoding from your CPU. |
| **Zero Cloud Dependencies** | Runs entirely on your local hardware - no telemetry, no internet checks, no remote servers. |
| **Execution Console Logging** | Line-by-line technical feedback so you can audit conversion metrics and debug configurations. |
| **YouTube Downloader** | Download videos and audio directly from YouTube with full quality options (144p to 4K). |
| **Torrent Downloader** | Download files over BitTorrent right inside IZ Converter. |
| **TeraBox Downloader** | Download files directly from TeraBox links. |
| **Download Queue** | Add multiple conversions to a queue, reorder by drag & drop, and process them sequentially. |
| **Download History** | View and manage all past downloads with search, selection, and bulk actions. |
| **Splash Screen** | Animated splash screen on launch. |
| **Notifications** | In-app update and notification system. |
| **Fully Upgraded UI** | Complete interface redesign - cleaner, more modern, and easier to use. |

---

## Installation

1. Head over to the [**Releases page**](../../releases/latest) and download **IZConverterSetup(6.6).exe**.
2. Double-click the downloaded `.exe` to launch the installer.
3. If Windows Defender SmartScreen pops up, click **"More info" → "Run anyway"** (the app isn't digitally signed yet).
4. Walk through the setup wizard.
5. Launch IZ Converter from the **Start Menu** or **Desktop shortcut** - you're all set!

### Requirements

- **OS:** Windows 10 or Windows 11 (64-bit recommended)
- **GPU (recommended):** NVIDIA (NVENC), AMD (AMF), or Intel (Quick Sync) for hardware acceleration
- **Disk space:** ~1 GB (2 GB recommended)
- No additional runtime dependencies needed

---

## Quick Start

1. Open IZ Converter.
2. Drag & drop your video files (or click **Add Files**).
3. Pick your output format - **MP4, MKV, AVI, WebM, or GIF**.
4. Toggle GPU acceleration if your hardware supports it.
5. Hit **Convert** and watch the console log stream in real time.
6. Done - your files are ready!

> **Tip:** Drop multiple files at once to take advantage of concurrent transcoding - IZ Converter will process them in parallel batches.

---

## Supported Formats

- **Video:** MP4, MKV, AVI, WebM
- **Animated:** GIF (web-optimized)
- **Downloading:** YouTube, Torrent (BitTorrent), TeraBox
- **Hardware encoders:** NVIDIA NVENC, AMD AMF, Intel Quick Sync

---

## Troubleshooting

| Problem | Fix |
|---|---|
| SmartScreen blocks the installer | Click *More info* → *Run anyway* |
| App won't launch | Right-click the shortcut → *Run as administrator* |
| Conversion is slow | Enable GPU acceleration if your hardware supports NVENC / AMF / Quick Sync |
| Output GIF is huge | Use the web-optimized GIF preset in the output settings |

Still stuck? [Open an issue](../../issues/new) - we read every one.

---

## Changelog

### v6.6

- **New:** Download queue mode with drag & drop reordering
- **New:** Download history with search and bulk selection
- **New:** TeraBox downloader - download files from TeraBox links
- **New:** Feedback form - send feedback directly from the app
- **New:** Animated splash screen on launch
- **New:** In-app notification system
- **New:** DevTools disabled in production (F12/Ctrl+Shift+I blocked)
- **Fixed:** YouTube "page needs to be reloaded" error - full quality restored (144p to 4K)
- **Fixed:** Binary path resolution in installed builds (asar unpacked paths)
- **Improved:** Source code protection via asar packaging
- **Improved:** CSP updated for all required domains
- **Installer:** ~302 MB download / ~1 GB installed

### v6.5

- **New:** YouTube downloader - grab videos and audio in one click
- **New:** Torrent downloader - download files via BitTorrent
- Fully upgraded UI - complete redesign for a cleaner, more modern experience
- Installer now ~309 MB download / ~989 MB installed

### v6.4

- Improved concurrent transcoding engine - better throughput on large batches
- Expanded GPU acceleration paths (NVENC / AMF / Quick Sync)
- New execution console logging for real-time conversion feedback
- Fixed rare crash on large batches
- Refreshed UI
- Misc. stability improvements

See the full [changelog](../../releases) for previous versions.

---

## Contributing

Bug reports, feature requests, and pull requests are welcome! Please [open an issue](../../issues/new) first to discuss what you'd like to change.

---

## Contact

Built with care by **Izzi Developers Inc.**

- Issues: [GitHub Issues](../../issues)
- Email: [izzidevelopers@hotmail.com](mailto:izzidevelopers@hotmail.com)

---

## License

c 2026 Izzi Developers Inc. - Released under the [MIT License](LICENSE).

<p align="center"><sub>Made with care - not AI-slop filler</sub></p>
