# Tint — light photo filter app for Android

65 filters in 8 categories (Film, Vintage, Mood, Cinema, Pastel, B&W, Retro, Glow), intensity slider,
hold-to-compare, saves full-resolution JPEGs to **Pictures/Tint**. No libraries, no internet,
no permissions. Expected APK size: ~100 KB. Android 10+ (made for Android 15 / Nothing Phone 3a).

## Get the APK — easiest way (no software to install)
1. Create a free account at github.com and make a **new repository** (e.g. `tint`).
2. On the repo page click **Add file → Upload files**, drag in everything inside this folder
   (including the hidden `.github` folder — on a phone, upload the zip contents via a PC if needed), then **Commit**.
3. Open the **Actions** tab → wait ~3 minutes for "Build APK" to turn green → open it →
   download **Tint-apk** at the bottom.
4. On your phone: unzip it, tap `app-release.apk`, allow "Install unknown apps" when asked.

## Or with Android Studio
Open this folder → let it sync → **Build → Build APK(s)**.

## Also
- Share any photo from Gallery/Google Photos → **Tint** to open it directly.
- Add filters in `Filters.java` — one line each.
