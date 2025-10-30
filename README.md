# ReVanced Builder
**Automatically builds and publishes ReVanced APKs & Magisk Modules whenever new patches are released.**

### [Join the Telegram Group](https://t.me/rvbygeo)
Get notified instantly when new builds are released.

### [Download from GitHub Releases](https://github.com/geologically/revanced-builder/releases)
If you don’t see the app you want in the latest release, check the older ones.

### How to Install via [Obtainium](https://github.com/ImranR98/Obtainium)
Obtainium is the easiest way to install and update ReVanced APKs.

1. Open the **Obtainium** app.  
2. Tap **Add app**.  
3. In the **App source URL** box, enter one of the following:

   - **For ReVanced APKs:**  
     `github.com/geologically/revanced-builder`

   - **For MicroG (required for Google APKs):**  
     `github.com/WSTxda/MicroG-RE`

   - **For Twitter:**  
      `https://github.com/crimera/twitter-apk`

4. Scroll down to **Filter APKs by regular expression**.  
5. Enter the appropriate regex from the table below for the app you want.  
6. Tap **Add** to begin downloading.

### Regex Patterns for Filtering APKs
| Patch                                                                      | App            | Arch       | Regex Pattern                                                |
|----------------------------------------------------------------------------|----------------|------------|--------------------------------------------------------------|
| [Official](https://github.com/revanced/revanced-patches)                   | YouTube        | universal  | `^youtube-revanced-v[\d.]+-all\.apk$`                        |
|                                                                            | YouTube Music  | arm64      | `^music-revanced-v[\d.]+-arm64-v8a\.apk$`                    |
|                                                                            |                | arm32      | `^music-revanced-v[\d.]+-arm-v7a\.apk$`                      |
|                                                                            | Google Photos  | arm64      | `^photos-revanced-v[\d.]+-arm64-v8a\.apk$`                   |
|                                                                            |                | arm32      | `^photos-revanced-v[\d.]+-arm-v7a\.apk$`                     |
|                                                                            | Duolingo       | arm64      | `^duolingo-revanced-v[\d.]+-arm64-v8a\.apk$`                 |
|                                                                            |                | arm32      | `^duolingo-revanced-v[\d.]+-arm-v7a\.apk$`                   |
| [Extended](https://github.com/inotia00/revanced-patches)                   | YouTube        | universal  | `^youtube-revanced-extended-v[\d.]+-all\.apk$`               |
|                                                                            | YouTube Music  | arm64      | `^music-revanced-extended-v[\d.]+-arm64-v8a\.apk$`           |
|                                                                            |                | arm32      | `^music-revanced-extended-v[\d.]+-arm-v7a\.apk$`             |
|                                                                            | Reddit         | arm64      | `^reddit-revanced-extended-v[\d.]+-arm64-v8a\.apk$`          |
|                                                                            |                | arm32      | `^reddit-revanced-extended-v[\d.]+-arm-v7a\.apk$`            |
| [Advanced](https://github.com/anddea/revanced-patches)                     | YouTube        | universal  | `^youtube-revanced-advanced-v[\d.]+-all\.apk$`               |
|                                                                            | YouTube Music  | arm64      | `^music-revanced-advanced-v[\d.]+-arm64-v8a\.apk$`           |
|                                                                            |                | arm32      | `^music-revanced-advanced-v[\d.]+-arm-v7a\.apk$`             |
|                                                                            | Reddit         | arm64      | `^reddit-revanced-advanced-v[\d.]+-arm64-v8a\.apk$`          |
|                                                                            |                | arm32      | `^reddit-revanced-advanced-v[\d.]+-arm-v7a\.apk$`            |
|                                                                            | Spotify        | arm64      | `^spotify-revanced-advanced-v[\d.]+-arm64-v8a\.apk$`         |
| [Piko](https://github.com/crimera/piko)                                    | Twitter        | universal  | `^x-piko-v(\d+\.\d+\.\d+)-release\.\d+\.apk$`                |

`universal` : For all devices. <br>
`arm32`     : For most older (before 2017) or low-end devices. <br>
`arm64`     : For most modern devices (after 2017).

### Notes
- All modules can be updated directly from Magisk and KSU.
- [MicroG](https://github.com/WSTxda/MicroG-RE/releases/latest) is required for Google APKs to work properly.
- Found a bug? Report it in the [Telegram Group](https://t.me/rvbygeo).

### Credits
All credit goes to the original ReVanced patch developers and maintainers.

| [revanced](https://github.com/ReVanced) | [anddea](https://github.com/anddea/revanced-patches) | [j-hc](https://github.com/j-hc/revanced-magisk-module) | [inotia00](https://github.com/inotia00/revanced-patches) |
|-----------------------------------------|------------------------------------------------------|--------------------------------------------------------|----------------------------------------------------------|


