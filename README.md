# Awesome IPTV Players

A curated list of IPTV player apps, organised by device. Every entry says what the app is good at, what it costs and which playlist formats it accepts (M3U, Xtream Codes API, Stalker/MAG portal).

Maintained by [SmartVPro](https://github.com/smartvpro-tv). Contributions welcome: open a pull request with the app name, platform, official link and one honest sentence about it.

## Contents

- [Before you choose](#before-you-choose)
- [Amazon Fire TV / Firestick](#amazon-fire-tv--firestick)
- [Android TV, Google TV, Android phones](#android-tv-google-tv-android-phones)
- [Samsung Smart TV (Tizen)](#samsung-smart-tv-tizen)
- [LG Smart TV (webOS)](#lg-smart-tv-webos)
- [Apple TV, iPhone, iPad](#apple-tv-iphone-ipad)
- [Windows](#windows)
- [macOS](#macos)
- [Linux](#linux)
- [Kodi](#kodi)
- [MAG boxes and Enigma2 receivers](#mag-boxes-and-enigma2-receivers)
- [Web browser](#web-browser)
- [Comparison table](#comparison-table)
- [Setup guides](#setup-guides)
- [License](#license)

## Before you choose

Three things decide which player you should use:

1. **Device.** Samsung and LG TVs run their own operating systems, so the app choice is much smaller than on Android.
2. **Login type.** Your provider gives you either an M3U URL, Xtream Codes credentials (server URL + username + password) or a MAG portal address. Check the table below for which formats each app supports.
3. **EPG.** If you care about the TV guide, pick an app with a proper EPG grid (TiviMate, OTT Navigator, IPTV Smarters Pro).

Almost every paid app has a free trial or a free tier with ads. Try before buying.

## Amazon Fire TV / Firestick

| App | Price | M3U | Xtream | MAG | Notes |
|---|---|---|---|---|---|
| [TiviMate](https://tivimate.com/) | Free / Premium (yearly) | Yes | Yes | No | Best EPG grid on Android-based devices. Premium unlocks multiple playlists, recording, favourites. |
| [IPTV Smarters Pro](https://www.iptvsmarters.com/) | Free | Yes | Yes | No | Most widely used app. Simple interface, multi-screen, parental control. |
| XCIPTV | Free | Yes | Yes | No | Lightweight, works well on older Firesticks. |
| OTT Navigator | Free / Premium | Yes | Yes | No | Very customisable, strong EPG, catch-up support. |
| IBO Player | Free trial / Yearly | Yes | Yes | No | Activated by MAC address through a web panel, no typing on the TV. |
| [VLC](https://www.videolan.org/vlc/) | Free | Yes | No | No | Plays a single M3U, no EPG. Good for testing a link. |

All of these are sideloaded through the **Downloader** app when they are not in the Amazon Appstore for your region.

## Android TV, Google TV, Android phones

| App | Price | M3U | Xtream | MAG | Notes |
|---|---|---|---|---|---|
| [TiviMate](https://tivimate.com/) | Free / Premium | Yes | Yes | No | Reference player for Android TV. |
| [IPTV Smarters Pro](https://www.iptvsmarters.com/) | Free | Yes | Yes | No | Also has a phone-friendly layout. |
| OTT Navigator | Free / Premium | Yes | Yes | No | Good on both TV and phone. |
| Televizo | Free / Premium | Yes | Yes | No | Fast channel switching, small footprint. |
| GSE Smart IPTV | Free / Pro | Yes | Yes | No | Older but still maintained; supports EPG in several formats. |
| Perfect Player | Free / Paid | Yes | Yes | No | Classic choice, minimal UI. |
| [Kodi](https://kodi.tv/) + PVR IPTV Simple Client | Free | Yes | No | No | See the [Kodi](#kodi) section. |

## Samsung Smart TV (Tizen)

Samsung TVs cannot sideload Android apps. Use an app from the Samsung store:

| App | Price | M3U | Xtream | MAG | Notes |
|---|---|---|---|---|---|
| [Smart IPTV (SIPTV)](https://siptv.app/) | One-time activation fee | Yes | No | No | Upload your playlist on the SIPTV website using the TV's MAC address. |
| IPTV Smarters Pro (Tizen) | Free | Yes | Yes | No | Available on newer Samsung models. |
| Set IPTV | Yearly | Yes | No | No | Playlist is linked to the TV's MAC address via a web panel. |
| Net IPTV | Yearly | Yes | No | No | Same model as Set IPTV. |
| Flix IPTV | Yearly | Yes | No | No | Same model, different interface. |
| IBO Player | Yearly | Yes | Yes | No | Web-panel activation. |

Tip: write down the MAC address shown in the app before you go to the activation website.

## LG Smart TV (webOS)

| App | Price | M3U | Xtream | MAG | Notes |
|---|---|---|---|---|---|
| [Smart IPTV (SIPTV)](https://siptv.app/) | One-time activation fee | Yes | No | No | Same web-panel workflow as on Samsung. |
| IPTV Smarters Pro (webOS) | Free | Yes | Yes | No | Available on newer LG models. |
| Set IPTV / Net IPTV / Flix IPTV | Yearly | Yes | No | No | MAC-based activation. |
| IBO Player | Yearly | Yes | Yes | No | MAC-based activation. |

## Apple TV, iPhone, iPad

| App | Price | M3U | Xtream | MAG | Notes |
|---|---|---|---|---|---|
| IPTV Smarters Pro | Free | Yes | Yes | No | On the App Store. |
| GSE Smart IPTV | Free / Pro | Yes | Yes | No | Supports Chromecast and AirPlay. |
| iPlayTV | Paid | Yes | Yes | No | Apple TV focused, clean interface. |
| Flex IPTV | Free / Pro | Yes | Yes | No | Apple TV and iOS. |
| [VLC](https://www.videolan.org/vlc/) | Free | Yes | No | No | Testing only. |

## Windows

| App | Price | M3U | Xtream | MAG | Notes |
|---|---|---|---|---|---|
| IPTV Smarters Pro (Windows) | Free | Yes | Yes | No | Same interface as the TV app. |
| MyIPTV Player | Free | Yes | No | No | Microsoft Store app with EPG support. |
| [IPTVnator](https://github.com/4gray/iptvnator) | Free, open source | Yes | Yes | No | Cross-platform Electron app, also on Linux and macOS. |
| [VLC](https://www.videolan.org/vlc/) | Free | Yes | No | No | Open the M3U via *Media → Open Network Stream*. |
| [Kodi](https://kodi.tv/) | Free | Yes | No | No | With the PVR IPTV Simple Client add-on. |

## macOS

| App | Price | M3U | Xtream | MAG | Notes |
|---|---|---|---|---|---|
| IPTV Smarters Pro (macOS) | Free | Yes | Yes | No | |
| [IPTVnator](https://github.com/4gray/iptvnator) | Free, open source | Yes | Yes | No | |
| [VLC](https://www.videolan.org/vlc/) | Free | Yes | No | No | |
| [Kodi](https://kodi.tv/) | Free | Yes | No | No | |

## Linux

| App | Price | M3U | Xtream | MAG | Notes |
|---|---|---|---|---|---|
| [Hypnotix](https://github.com/linuxmint/hypnotix) | Free, open source | Yes | Yes | No | Ships with Linux Mint; supports Xtream and M3U. |
| [IPTVnator](https://github.com/4gray/iptvnator) | Free, open source | Yes | Yes | No | AppImage, deb, rpm, Flatpak. |
| [VLC](https://www.videolan.org/vlc/) | Free | Yes | No | No | |
| [Kodi](https://kodi.tv/) | Free | Yes | No | No | |

## Kodi

Kodi is not an IPTV player by itself. Install the **PVR IPTV Simple Client** add-on (Settings → Add-ons → Install from repository → PVR clients), then point it at your M3U URL and optional XMLTV EPG URL. Kodi runs on nearly everything: Fire TV, Android, Windows, macOS, Linux, Raspberry Pi.

## MAG boxes and Enigma2 receivers

- **MAG (Infomir) boxes** use a *portal URL* instead of an M3U. Your provider gives you the portal address; enter it under *Settings → System settings → Servers → Portals*. The box's MAC address is tied to the subscription.
- **Enigma2 receivers** (Dreambox, Vu+, Zgemma and others) load IPTV through a bouquet file or a plugin such as *E2iPlayer*, *XStreamity* (Xtream Codes) or *JediMakerXtream*. Most providers can export an Enigma2 bouquet directly.

## Web browser

A few players run entirely in the browser, which is handy for a quick test on a laptop:

| Player | Notes |
|---|---|
| [IPTVnator](https://github.com/4gray/iptvnator) (web build) | Open-source, M3U and Xtream. |
| Browser-based players offered by your provider | Some providers host a web player on their own domain; check your welcome email. |

Browsers cannot play every stream format (MPEG-TS in particular), so a stream that fails in the browser may still work in a dedicated app.

## Comparison table

| Feature | TiviMate | IPTV Smarters Pro | OTT Navigator | Smart IPTV (SIPTV) | Kodi + PVR |
|---|---|---|---|---|---|
| Platforms | Android / Fire TV | Almost all | Android / Fire TV | Samsung / LG | Almost all |
| EPG grid | Excellent | Good | Excellent | Basic | Good |
| Multiple playlists | Premium | Yes | Yes | No | Yes |
| Catch-up / timeshift | Premium | Yes (if provider supports) | Yes | No | Partial |
| Recording | Premium | No | Yes | No | Yes |
| Price | Free / yearly premium | Free | Free / premium | One-time activation | Free |

## Setup guides

Step-by-step installation guides for each device are in the [iptv-setup-guides](https://github.com/smartvpro-tv/iptv-setup-guides) repository. Country-specific guides:

- United States: [IPTV player installation tutorial](https://smartvpro.com/iptv-player-installation-tutorial-usa-iptv/)
- United Kingdom: [IPTV tutorials](https://smartvpro.co.uk/iptv-tutorials/)
- Canada: [IPTV setup Canada](https://iptvv-ca.ca/iptv-setup-canada/)
- Nederland: [IPTV installeren](https://dutchiptvnl.net/iptv-installeren/)

## License

This list is released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). App names and trademarks belong to their respective owners. No playlists or streams are hosted in this repository.
