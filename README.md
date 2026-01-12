<p align="center">
  <img src="https://cdn.stelle.moe/stelle-icon.png" alt="Stelle Logo" width="120" height="120">
</p>

<h1 align="center">Stelle Mobile App</h1>

<p align="center">
  <strong>Your media backup companion - now in your pocket</strong>
</p>

<p align="center">
  <a href="#download">
    <img src="https://img.shields.io/badge/Android-Available-brightgreen?style=for-the-badge&logo=android" alt="Android Available">
  </a>
  <a href="#ios">
    <img src="https://img.shields.io/badge/iOS-Coming%20Soon-lightgrey?style=for-the-badge&logo=apple" alt="iOS Coming Soon">
  </a>
  <a href="https://github.com/golfista/stelle.bot.app/releases">
    <img src="https://img.shields.io/github/v/release/golfista/stelle.bot.app?style=for-the-badge&label=Latest" alt="Latest Release">
  </a>
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#download">Download</a> •
  <a href="#screenshots">Screenshots</a> •
  <a href="#requirements">Requirements</a> •
  <a href="#issue-tracker">Issues</a>
</p>

---

## About

**Stelle** is a Discord bot that automatically downloads and backs up media from your favorite platforms — YouTube, TikTok, Instagram, Reddit, Twitter/X, and more. The **Stelle Mobile App** brings your entire media library to your Android device, letting you browse, organize, and enjoy your backed-up content on the go.

This repository hosts the official releases of the Stelle mobile applications.

---

## Features

### Core Features

| Feature | Description |
|---------|-------------|
| **Media Gallery** | Browse your entire media library in a beautiful Pinterest-style masonry grid |
| **Video Playback** | Watch videos with a full-featured player powered by ExoPlayer |
| **Image Viewer** | Swipe through images with pinch-to-zoom support |
| **Audio Player** | Listen to extracted audio with background playback and notification controls |
| **Collections** | Organize your media into custom collections |
| **Favorites** | Quick access to your most-loved content |
| **Search & Filter** | Find media by platform, type, date, or keywords |
| **Offline Mode** | Access cached media without an internet connection |

### Platform Integration

- **Discord OAuth** — Secure sign-in with your Discord account
- **Sync** — Your media, favorites, and collections sync across web and mobile
- **Real-time Updates** — New downloads appear automatically

### Design

- **Dark Theme** — Native dark mode that's easy on the eyes
- **Material Design 3** — Modern UI following Google's latest design guidelines
- **Adaptive Icons** — Beautiful app icon on all Android launchers

---

## Download

### Android

<a href="https://github.com/golfista/stelle.bot.app/releases/latest">
  <img src="https://img.shields.io/badge/Download-APK-blue?style=for-the-badge&logo=android" alt="Download APK">
</a>

1. Go to the [Releases](https://github.com/golfista/stelle.bot.app/releases) page
2. Download the latest `.apk` file
3. Enable "Install from unknown sources" if prompted
4. Install and enjoy!

> **Note:** The app requires you to have an existing Stelle Discord bot account. The bot must be in a server you're a member of.

### iOS

<a name="ios"></a>

<img src="https://img.shields.io/badge/iOS-Coming%20Soon-lightgrey?style=for-the-badge&logo=apple" alt="iOS Coming Soon">

The iOS version is currently in development. Follow this repository or join our Discord server for updates on the release timeline.

---

## Screenshots

<p align="center">
  <i>Screenshots coming soon</i>
</p>

<!--
<p align="center">
  <img src="screenshots/home.png" width="200" alt="Home Screen">
  <img src="screenshots/viewer.png" width="200" alt="Media Viewer">
  <img src="screenshots/collections.png" width="200" alt="Collections">
  <img src="screenshots/player.png" width="200" alt="Audio Player">
</p>
-->

---

## Requirements

### Android

| Requirement | Minimum |
|-------------|---------|
| **Android Version** | 8.0 (Oreo) / API 26 |
| **Architecture** | arm64-v8a, armeabi-v7a, x86_64 |
| **Storage** | ~100 MB for app + cache |
| **Internet** | Required for login and syncing |

### Account Requirements

- A Discord account
- Access to a Discord server with the Stelle bot
- Media previously downloaded through the bot

---

## Release Channels

We offer different release channels to match your preferences:

| Channel | Stability | Updates | Recommended For |
|---------|-----------|---------|-----------------|
| **Stable** | High | Slow | Most users |
| **Beta** | Medium | Regular | Early adopters |
| **Alpha** | Low | Frequent | Testers |
| **Prototype** | Experimental | Rapid | Developers |

Download from the [Releases](https://github.com/golfista/stelle.bot.app/releases) page and choose the version that suits you.

---

## Issue Tracker

Found a bug? Have a feature request? We'd love to hear from you!

### Reporting Issues

<a href="https://github.com/golfista/stelle.bot.app/issues/new?template=bug_report.md">
  <img src="https://img.shields.io/badge/Report-Bug-red?style=for-the-badge" alt="Report Bug">
</a>
<a href="https://github.com/golfista/stelle.bot.app/issues/new?template=feature_request.md">
  <img src="https://img.shields.io/badge/Request-Feature-purple?style=for-the-badge" alt="Request Feature">
</a>

**Before submitting an issue, please:**

1. Check the [existing issues](https://github.com/golfista/stelle.bot.app/issues) to avoid duplicates
2. Include your device model and Android version
3. Provide steps to reproduce the bug
4. Attach screenshots or screen recordings if applicable

### Issue Labels

| Label | Description |
|-------|-------------|
| `bug` | Something isn't working |
| `enhancement` | New feature or improvement |
| `android` | Android-specific issue |
| `ios` | iOS-specific issue |
| `ui/ux` | User interface or experience |
| `performance` | Speed or resource usage |
| `help wanted` | Looking for contributors |

### Known Issues

Check our [Known Issues](https://github.com/golfista/stelle.bot.app/issues?q=is%3Aissue+is%3Aopen+label%3A%22known+issue%22) list for problems we're already aware of.

---

## Roadmap

### In Progress
- [x] Share intent (receive URLs from other apps)
- [x] Push notifications for new downloads
- [ ] Android Auto support

### Planned
- [ ] iOS app development
- [x] Playlist management
- [ ] Download media directly in-app
- [ ] Widget support
- [ ] Wear OS companion app

### Completed
- [x] Discord OAuth authentication
- [x] Media gallery with masonry layout
- [x] Video and image viewing
- [x] Audio playback with notification controls
- [x] Collections and favorites
- [x] Offline caching
- [x] Dark theme

---

## Tech Stack

### Android

| Technology | Purpose |
|------------|---------|
| **Kotlin** | Primary language |
| **Jetpack Compose** | Modern declarative UI |
| **Material Design 3** | UI components and theming |
| **Hilt** | Dependency injection |
| **Retrofit** | Network requests |
| **Room** | Local database / offline cache |
| **Coil** | Image loading |
| **ExoPlayer (Media3)** | Video and audio playback |
| **Firebase Cloud Messaging** | Push notifications |

---

## Privacy & Security

- **No data collection** — We don't collect analytics or personal data
- **Secure authentication** — OAuth 2.0 with Discord
- **Local storage** — Your cached media stays on your device
- **Open source** — Transparency in how your data is handled

---

## Support

Need help? Have questions?

- **Issues:** [GitHub Issues](https://github.com/golfista/stelle.bot.app/issues)
- **Discord:** Join our community server (link coming soon)

---

## License

This project is proprietary software. The releases are provided for personal use only. Redistribution or modification is not permitted without explicit permission.

---

<p align="center">
  Made with ❤️ by the Stelle team
</p>

<p align="center">
  <a href="https://stelle.moe">stelle.moe</a>
</p>
