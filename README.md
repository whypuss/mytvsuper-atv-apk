# myTV SUPER (Android TV) APK (Extracted)

從 Android 裝置 (Chromecast HD, `armeabi-v7a`) 提取的原版 myTV SUPER Android TV 電視版 Split APK。

## 📦 版本資訊

- **Package Name**: `com.tvb.mytvsuper.atv`
- **Version Name**: `4.3.4`
- **Version Code**: `515`
- **Min SDK**: `23` (Android 6.0+)
- **Target SDK**: `35` (Android 15)
- **Architecture**: `armeabi-v7a`
- **Screen Density**: `xhdpi`

## 📁 包含檔案

- `mytvsuper_base.apk` (主程式包)
- `split_config.armeabi_v7a.apk` (Native Lib 架構庫)
- `split_config.xhdpi.apk` (介面與高解析度資產包)
- `split_config.zh.apk` (繁簡中文語言資源包)
- `mytvsuper-atv-v4.3.4-split-apks.zip` (完整分包一鍵壓縮檔)

## 🚀 安裝方式

若需安裝至目標 Android 電視或電視盒，解壓後透過 ADB 多包安裝：

```bash
adb install-multiple mytvsuper_base.apk split_config.armeabi_v7a.apk split_config.xhdpi.apk split_config.zh.apk
```
