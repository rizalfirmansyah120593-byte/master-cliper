# 🚀 Master Cliper

<<<<<<< HEAD
=======
[![Discord](https://img.shields.io/badge/Join-Discord-5865F2?logo=discord&logoColor=white)](https://s.id/ytsdiscord)
[![GitHub Stars](https://github.com/jipraks/yt-short-clipper)](https://github.com/rizalfirmansyah120593-byte/master-cliper)
>>>>>>> 5dcc78ca5ea0a4dbd942968d55f92eff7d42757e
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS-lightgrey)]()
[![Saweria](https://img.shields.io/badge/Support-Saweria-red?logo=kofi&logoColor=white)](https://saweria.co/RizalFirmansyah)

---

## 🎬 Automated YouTube to Short-Form Content Pipeline

Transformasikan video YouTube durasi panjang (podcast, interview, vlogs) menjadi konten *short-form* yang viral untuk **TikTok, Instagram Reels, dan YouTube Shorts** — didukung penuh oleh kekuatan AI.

<<<<<<< HEAD
> *"Reinventing your content creation workflow with AI-powered precision."*
=======
Download the desktop app for your platform:

| Platform | Download | Notes |
|----------|----------|-------|
| **Windows** | [Latest Release (.exe)](https://github.com/rizalfirmansyah120593-byte/master-cliper/releases) | Windows 10+ |
| **macOS** | [Latest Release (.dmg)](https://github.com/rizalfirmansyah120593-byte/master-cliper/releases) | macOS Catalina+, Apple Silicon & Intel |

Then follow the complete setup guide:

- 📖 **[English Guide](GUIDE.md)** - Complete setup guide with screenshots
- 📖 **[Panduan Indonesia](PANDUAN.md)** - Panduan lengkap dengan screenshot

**What you'll learn:**
1. How to download and run the app
2. Setup required libraries (yt-dlp, FFmpeg, Deno)
3. Setup YouTube cookies for video access
4. Configure AI API (multiple providers supported)
5. Start processing videos

### For Developers

If you want to contribute or run from source:

1. See [Installation](#-installation-for-development) below for development setup
2. See [Contributing](#-contributing) for contribution guidelines
3. See [Building from Source](#-building-from-source) for packaging the app

## ✨ Features

- **🎥 Auto Download** - Downloads YouTube videos with subtitles using yt-dlp
- **🔍 AI Highlight Detection** - Uses GPT-4 to identify the most engaging segments (60-120 seconds)
- **✂️ Smart Clipping** - Automatically cuts video at optimal timestamps
- **📱 Portrait Conversion** - Converts landscape (16:9) to portrait (9:16) with intelligent speaker tracking
- **🎯 Face Detection** - Two modes available:
  - **OpenCV (Fast)** - Crops to largest face, faster processing
  - **MediaPipe (Smart)** - Tracks active speaker via lip movement detection, more accurate but 2-3x slower
- **🪝 Hook Generation** - Creates attention-grabbing intro scenes with AI-generated text and TTS voiceover
- **📝 Auto Captions** - Adds CapCut-style word-by-word highlighted captions using Whisper
- **🖼️ Watermark Support** - Add custom watermark with adjustable position, size, and opacity
- **📊 SEO Metadata** - Generates optimized titles and descriptions for each clip
- **🖥️ Cross-Platform** - Runs on Windows and macOS (Apple Silicon + Intel)
- **⚡ GPU Acceleration** - NVENC (NVIDIA), AMF (AMD), QSV (Intel), VideoToolbox (macOS)

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────────────────────┐
│                        Master Cliper                         │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  ┌──────────┐    ┌──────────────┐    ┌─────────────┐           │
│  │ YouTube  │───▶│  Downloader  │───▶│  Subtitle   │           │
│  │   URL    │    │   (yt-dlp)   │    │   Parser    │           │
│  └──────────┘    └──────────────┘    └─────────────┘           │
│                                              │                  │
│                                              ▼                  │
│                                    ┌─────────────────┐         │
│                                    │ Highlight Finder │         │
│                                    │    (GPT-4)       │         │
│                                    └─────────────────┘         │
│                                              │                  │
│                                              ▼                  │
│  ┌──────────────────────────────────────────────────────────┐  │
│  │                    Video Processing                       │  │
│  │  ┌────────────┐  ┌────────────┐  ┌────────────────────┐  │  │
│  │  │   Clipper  │─▶│  Portrait  │─▶│  Hook Generator    │  │  │
│  │  │  (FFmpeg)  │  │ Converter  │  │  (TTS + Overlay)   │  │  │
│  │  └────────────┘  │ OpenCV /   │  └────────────────────┘  │  │
│  │                   │ MediaPipe  │             │            │  │
│  │                   └────────────┘             ▼            │  │
│  │                                    ┌────────────────┐     │  │
│  │                                    │Caption Generator│    │  │
│  │                                    │   (Whisper)     │    │  │
│  │                                    └────────────────┘     │  │
│  └──────────────────────────────────────────────────────────┘  │
│                                              │                  │
│                                              ▼                  │
│                                    ┌─────────────────┐         │
│                                    │  Output Clips   │         │
│                                    │  + Metadata      │         │
│                                    └─────────────────┘         │
└─────────────────────────────────────────────────────────────────┘
```
>>>>>>> 5dcc78ca5ea0a4dbd942968d55f92eff7d42757e

---

## 📥 Download Aplikasi

| Platform | Download Link |
| :--- | :--- |
| **Windows** | [Download Terbaru (.exe)](https://github.com/rizalfirmansyah120593-byte/master-cliper/releases) |
| **macOS** | [Download Terbaru (.dmg)](https://github.com/rizalfirmansyah120593-byte/master-cliper/releases) |

---

## 💡 Fitur Utama

- **🎥 Auto Download:** Unduh video YouTube dengan subtitle secara otomatis.
- **🔍 AI Highlight Detection:** Identifikasi momen paling menarik (60-120 detik) menggunakan GPT-4.
- **✂️ Smart Clipping:** Potong video otomatis pada timestamp yang optimal.
- **📱 Portrait Conversion:** Konversi 16:9 ke 9:16 dengan *intelligent speaker tracking*.
- **🪝 Hook Generation:** Buat intro yang memancing atensi dengan AI Voiceover.
- **📝 Auto Captions:** Tambahkan subtitle bergaya CapCut yang dinamis.
- **⚡ GPU Acceleration:** Mendukung NVENC (NVIDIA), AMF (AMD), & VideoToolbox (macOS).

---

## 🛠️ Persiapan & Panduan

Untuk langkah-langkah instalasi, silakan ikuti panduan berikut:

* 📖 **[Panduan Indonesia](PANDUAN.md)** - Panduan lengkap dengan screenshot.
* 📖 **[English Guide](GUIDE.md)** - Complete setup guide.

---

## ❤️ Dukung Proyek Ini

Jika aplikasi ini membantu alur kerja konten Anda, silakan berikan dukungan agar pengembangan tetap berlanjut:

  <div align="center">
  <a href="https://saweria.co/RizalFirmansyah" target="_blank">
    <img src="qrcode.png" alt="Saweria QR Code" width="200" />
    <br>
    <sub>Klik gambar untuk mendukung via Saweria</sub>
  </a>
</div>

---

## 🏗️ Struktur Proyek

master-cliper/
├── app.py              # Main GUI Entry Point
├── clipper_core.py     # Logika pemrosesan video
├── components/         # Komponen UI
├── pages/              # Halaman antarmuka
└── utils/              # Modul utilitas & GPU detection

---

## 📝 Lisensi
Proyek ini dilisensikan di bawah **MIT License**. Anda bebas memodifikasi dan mendistribusikan aplikasi ini.

---

## 👨‍💻 Dikembangkan Oleh

Dibuat dengan dedikasi untuk kreator konten oleh **Rizal Firmansyah**.

| Socials | Link |
| :--- | :--- |
| 🌐 **Portofolio** | [rizal-firmansyah-portofolio.vercel.app](rizal-firmansyah-portofolio.vercel.app) |
| ☕ **Saweria** | [saweria.co/RizalFirmansyah](https://saweria.co/RizalFirmansyah) |

---

### ⚠️ Disclaimer
* *Alat ini ditujukan untuk penggunaan pribadi dan edukasi.*
* *Harap hargai ketentuan layanan YouTube.*
* *Pastikan Anda memiliki hak cipta atas konten yang Anda proses.*
