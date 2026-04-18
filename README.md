# flompter (Floating Teleprompter)

一款简洁好用的安卓悬浮提词器 App。由于找不到满意的提词器 App，所以自己写了一款。欢迎大家自由使用！

## 下载

[点击这里下载最新 APK](https://github.com/guigulaoshi/flompter/raw/main/app/build/outputs/apk/debug/app-debug.apk)

> 需要安卓 14（API 34）或更高版本。首次运行会请求"显示在其他应用上层"的权限，用于显示悬浮窗。

## 功能

- **悬浮窗提词**：在任何 App 之上显示提词内容，适合直播、拍视频、演讲、朗读。
- **自动滚动**：支持播放/暂停，滚动速度可调。
- **字号调节**：字体大小实时可调。
- **手动拖动**：在提词区域上下滑动，手动调整阅读位置。
- **窗口移动**：拖动底部控制栏，可上下移动悬浮窗位置。
- **自动记忆**：自动保存上次的文本内容、滚动速度和字号设置。

## 使用方法

1. 打开 App，在主界面输入要显示的提词内容。
2. 点击底部按钮，授予悬浮窗权限后进入悬浮窗模式。
3. 悬浮窗分为两部分：
   - **上半部分**：显示提词文本，可上下拖动调整位置。
   - **下半部分**：控制栏，包含滚动速度、字号、播放/暂停、编辑、关闭按钮。
4. 点击 **Edit** 返回主界面修改文本，点击 **Close** 关闭悬浮窗。

## 从源码构建

本项目使用 Kotlin + Gradle 构建，需要 Android Studio。

```bash
git clone https://github.com/guigulaoshi/flompter.git
cd flompter
./gradlew assembleDebug
```

构建产物位于 `app/build/outputs/apk/debug/app-debug.apk`。

### 项目信息

- 语言：Kotlin
- 最低 SDK：Android 14（API 34）
- 目标 SDK：Android 15（API 35）
- 包名：`com.guigulaoshiren.floatingprompter`

## 反馈

欢迎提 Issue 或 PR。
