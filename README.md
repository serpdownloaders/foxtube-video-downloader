# FoxTube Downloader (Browser Extension)

> Save FoxTube videos in your browser. Finds playable media, adds a download button, and includes 3 free downloads.

FoxTube Downloader is a browser extension that helps you save videos from FoxTube directly through your browser. Instead of hunting through page source code or using separate downloader sites, this extension detects playable media on the page and gives you a simple button to download it.

- Detects playable media from FoxTube video pages without manual inspection
- Adds a download button directly on the video player area
- Works through the extension popup or right-click context menu
- Includes 3 free trial downloads to test the workflow
- Saves files as MP4 for easy playback and archiving

## Links

- :rocket: Get it here: [FoxTube Downloader](https://serp.ly/foxtube-downloader)
- :new: Latest release: [GitHub Releases](https://github.com/serpapps/foxtube-downloader/releases/latest)
- :question: Help center: [SERP Help](https://help.serp.co/en/)
- :beetle: Report bugs: [GitHub Issues](https://github.com/serpapps/foxtube-downloader/issues)
- :bulb: Request features: [Feature Requests](https://github.com/serpapps/foxtube-downloader/issues)

## Preview

![FoxTube Downloader workflow preview](https://raw.githubusercontent.com/devinschumacher/uploads/refs/heads/main/images/source-repo-readmes/foxtube-downloader/assets/workflow-preview.png)

## Table of Contents

- [Why FoxTube Downloader](#why-foxtube-downloader)
- [Features](#features)
- [How It Works](#how-it-works)
- [Step-by-Step Tutorial: How to Download Videos from FoxTube](#step-by-step-tutorial-how-to-download-videos-from-foxtube)
- [Supported Formats](#supported-formats)
- [Who It's For](#who-its-for)
- [Common Use Cases](#common-use-cases)
- [Troubleshooting](#troubleshooting)
- [Trial & Access](#trial--access)
- [Installation Instructions](#installation-instructions)
- [FAQ](#faq)
- [Notes](#notes)
- [License](#license)
- [About FoxTube](#about-foxtube)

## Why FoxTube Downloader

FoxTube video pages often expose media through player scripts rather than simple file links you can right-click and save. Generic browser tools may show you ad assets or non-video content instead of the actual stream you want to download. This makes saving a video feel like a technical chore rather than a normal browsing action.

FoxTube Downloader changes that by looking at the page for real media candidates and filtering out noise. It checks video tags, metadata, scripts, and resource activity to find playable content. The result is a straightforward download button on the player area, a popup with detected formats, and a right-click shortcut — all without leaving the FoxTube page.

## Features

- Download button attached to the FoxTube video player area
- Media detection from page video tags, metadata, scripts, and resource entries
- Direct MP4 and HLS candidate handling through the shared pipeline
- Format labels sorted by inferred quality where possible
- Right-click context menu for page and video contexts
- In-page download progress UI during file saving
- Organized FoxTube download folder for saved files
- OTP email activation with 3 free trial downloads

## How It Works

1. Install the extension from the latest release.
2. Open FoxTube and go to a supported video page.
3. Start playback so the extension can detect the media.
4. Open the popup or use the on-page controls.
5. Choose the quality option you want.
6. Start the download and wait for the MP4 export to finish.
7. Save the final file locally.

## Step-by-Step Tutorial: How to Download Videos from FoxTube

1. Install the FoxTube Downloader extension from the latest release.
2. Open a new tab and navigate to a FoxTube video page you want to save.
3. Press play on the video player so the page loads the media stream.
4. Look for the download button that appears on the video player area.
5. Click the download button to see the available format options.
6. Select the quality you prefer from the list.
7. Wait for the download to process and finish.
8. Save the MP4 file to your preferred location.

## Supported Formats

- Input: Direct MP4 URLs and HLS/M3U8-style media candidates detected from FoxTube pages
- Output: MP4

Saved files use MP4 so they are easier to replay on standard media players, move between devices, or archive locally.

## Who It's For

- FoxTube viewers who want offline access to videos
- Users who prefer a button-driven extension over copy-and-paste downloader sites
- People who want format choices without digging through developer tools
- Anyone looking for a simple browser workflow instead of command-line tools

## Common Use Cases

- Save a FoxTube video for offline viewing when you do not have internet access
- Detect playable media already exposed on a FoxTube page without manual inspection
- Choose from detected MP4 or HLS candidates where multiple formats are available
- Trigger downloads from the player UI instead of inspecting page source
- Use the extension popup or right-click menu for a faster workflow

## Troubleshooting

**No download button appears on the video player**
Refresh the page, press play on the video, and wait a few seconds for the extension to detect the media.

**The popup shows no media detected**
Make sure you are on a supported FoxTube video page and that the video has started playing.

**Download does not start after clicking**
Check your browser download permissions and ensure the extension has the necessary access to the FoxTube domain.

**The quality options look limited**
The extension can only show formats that the page exposes. Some videos may only have one available quality.

**Download fails partway through**
Try again with a stable internet connection. If the issue persists, refresh the page and restart the download.

## Trial & Access

- Includes **3 free downloads** so you can test the workflow first
- Email sign-in uses secure one-time password verification
- No credit card required for the trial
- Unlimited downloads are available with a paid license

Start here: [https://serp.ly/foxtube-downloader](https://serp.ly/foxtube-downloader)

## Installation Instructions

1. Open the latest release page: [GitHub Releases](https://github.com/serpapps/foxtube-downloader/releases/latest)
2. Download the correct build for your browser.
3. Install the extension.
4. Open a supported FoxTube page.
5. Use the popup to detect and download the media.

## FAQ

**How do I download a FoxTube video?**
Open a supported FoxTube page, play the video if needed, then use the player download button, the extension popup, or the right-click menu.

**What formats can it detect?**
The extension is designed to normalize direct MP4 URLs and HLS/M3U8-style media candidates when the page exposes them.

**Will it show different quality options?**
If the page exposes multiple variants, the extension attempts to infer quality from labels or URLs and sorts formats by detected height where possible.

**Where are downloads saved?**
The extension uses an organized FoxTube download folder for your saved files.

**Do I need to press play first?**
Often yes. Some pages only surface the actual media request after player scripts run or playback starts.

## Notes

- Only download content you own or have explicit permission to save
- An internet connection is required for downloads
- Press play on the video first to help the extension detect the media stream
- Available quality options depend on what the FoxTube page exposes

## License

This repository is distributed under the proprietary SERP Apps license in the [LICENSE](LICENSE) file. Review that file before copying, modifying, or redistributing any part of this project.

## About FoxTube

FoxTube is a video hosting platform that offers a wide range of adult content. FoxTube Downloader makes it easier to save videos from the platform directly through your browser without needing separate tools or software.
