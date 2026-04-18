# Android Floating Teleprompter (安卓浮窗提词器)

> **简介**：一款简洁好用的安卓悬浮提词器 App，可悬浮在任何应用之上，适合直播、拍视频、演讲、朗读。支持自动滚动、速度/字号调节、手动拖动定位。[点击下载 APK](https://github.com/guigulaoshi/flompter/raw/main/app/build/outputs/apk/debug/app-debug.apk)（需安卓 14+）。欢迎自由使用！

A lightweight floating teleprompter for Android. The prompter window sits on top of any app, so it works for livestreams, video recording, speeches, and reading practice.

## Download

[Download the latest APK](https://github.com/guigulaoshi/flompter/raw/main/app/build/outputs/apk/debug/app-debug.apk)

> Requires Android 14 (API 34) or later. On first launch the app asks for the "Display over other apps" permission, which is needed to render the floating window.

## Features

- **Floating overlay** — displays on top of any app, ideal for livestreams, video recording, speeches, and reading.
- **Auto-scroll** — play/pause with adjustable scroll speed.
- **Font size control** — change text size on the fly.
- **Manual drag** — swipe inside the prompt area to jump to any position.
- **Movable window** — drag the control bar to reposition the floating window vertically.
- **Persistent settings** — remembers your last script, scroll speed, and font size.

## How to Use

1. Open the app and type (or paste) the script you want to read.
2. Tap the bottom button and grant the overlay permission to enter floating mode.
3. The floating window has two parts:
   - **Top** — prompt text, draggable to reposition.
   - **Bottom** — control bar with speed slider, size slider, and Play/Pause, Edit, Close buttons.
4. Tap **Edit** to return to the main screen and change the script; tap **Close** to dismiss the floating window.

## Build from Source

Kotlin + Gradle. Android Studio recommended.

```bash
git clone https://github.com/guigulaoshi/flompter.git
cd flompter
./gradlew assembleDebug
```

The output APK lands in `app/build/outputs/apk/debug/app-debug.apk`.

### Project Info

- Language: Kotlin
- Min SDK: Android 14 (API 34)
- Target SDK: Android 15 (API 35)
- Package: `com.guigulaoshiren.floatingprompter`

## Feedback

Issues and PRs welcome.
