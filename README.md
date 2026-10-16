<div align="center">

<img src="docs/icon.png" width="96" alt="Soundlift icon">

# Soundlift

**Paste links. Get audio or video files.**

Turn up to 10 YouTube links at once into MP3, M4A, Opus, OGG, FLAC or WAV, or download a video from almost any site as MP4, MKV or WEBM.
Runs on your PC. No account, no install, no ads.

[![Download](https://img.shields.io/badge/Download-Windows%20(portable)-FFB347?style=for-the-badge&labelColor=0D0A10)](https://github.com/walkingcorpses/soundlift-releases/releases/latest)
![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011-FF4D7E?style=for-the-badge&labelColor=0D0A10)

<img src="docs/screenshot.png" width="560" alt="Soundlift window converting three links">

</div>

## Download and run

1. Get the **Soundlift-<version>-windows.zip** file from the [latest release](https://github.com/walkingcorpses/soundlift-releases/releases/latest).
2. Unzip it anywhere.
3. Open the `Soundlift` folder and double-click **Soundlift.exe**.
4. **Audio** tab: paste up to 10 YouTube links, pick a format, press **Convert**.
5. **Video** tab: paste one link, press **Fetch**, watch the preview, pick a format and quality, press **Download video**.

Audio lands in `Music\Soundlift` and video in `Videos\Soundlift` unless you pick another folder.

> Windows SmartScreen may warn because the app is not code-signed. Click **More info**, then **Run anyway**.

## Updates

Soundlift checks for a new version each time it opens. If there is one, it downloads it, checks it, installs it and restarts by itself. Nothing to click. (Versions before 1.1.0 cannot do this; download 1.1.0 once by hand.)

## What's new

**1.2.0** adds a **Video** tab.
- Download a video from almost any site, one link at a time. Some sites block certain countries and may need a VPN.
- Press **Fetch** for a preview card with a small player: Play, Pause and a volume slider.
- Choose MP4, MKV or WEBM, and a quality. Only sizes that format can hold are listed.

**1.1.1** fixes downloads that sometimes failed with `HTTP Error 403: Forbidden`. Soundlift now retries those by itself.

## Formats

Audio:

| Format | Type | Good for |
|--------|------|----------|
| MP3 | Lossy | Plays everywhere |
| M4A | Lossy | Apple devices, good quality per MB |
| Opus | Lossy | Best quality at small sizes |
| OGG | Lossy | Open format, wide player support |
| FLAC | Lossless | Archiving without losing quality |
| WAV | Lossless | Editing in audio software (large files) |

Video: **MP4** (plays everywhere, H.264), **MKV** (holds anything, up to 4K) and **WEBM** (VP9 or AV1, up to 4K).

## Built with

[yt-dlp](https://github.com/yt-dlp/yt-dlp), [FFmpeg](https://ffmpeg.org), [CustomTkinter](https://github.com/TomSchimansky/CustomTkinter) and [PyInstaller](https://pyinstaller.org).

## Fair use

Only download content you own, that is licensed for it, or that you otherwise have the right to copy. You are responsible for what you download.

