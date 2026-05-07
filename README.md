# Karaoke Video Creator — Releases  This repository hosts public release artifacts for **Karaoke Video Creator**, a Windows desktop app for turning song audio, lyrics, and timing data into karaoke videos.  > Source code: [sylvanas-labs/Karaoke-Video-Creator](https://github.com/sylvanas-labs/Karaoke-Video-Creator) *(private)*  ## Downloads  Go to the [Releases](../../releases) tab to download the latest version.  | File | Description | |------|-------------| | `KaraokeVideoCreator-Setup-<version>.exe` | Windows NSIS installer |  ## Release Tracks  | Track | Tag format | Description | |-------|-----------|-------------| | **Stable** | `v1.2.3` | Built from `main`. Recommended for most users. | | **Beta** | `v1.2.3-beta.N` | Built from `develop`. May contain incomplete features or bugs. |  ## Installing on Windows  Download and run the installer from the [Releases](../../releases) tab. The app requires Windows 10 or later.  ## About  Karaoke Video Creator is a .NET 9 WinForms desktop app. The pipeline covers importing source audio or video, loading and editing lyrics, optional source separation via Demucs, word alignment via WhisperX, ASS subtitle generation, and final FFmpeg rendering. 

## Portfolio Notes

- Desktop media workflow design.
- Audio, lyrics, timing, subtitles, and FFmpeg-backed rendering pipeline work.
- Automated public releases without exposing private product source.

## Source Policy

This repository intentionally contains release artifacts and public documentation only. Product source code remains private.
