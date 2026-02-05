DiskUsage
=========

For a better maintained version of this project have a look at:
https://github.com/WhiredPlanck/diskusage

DiskUsage app for Android

DiskUsage provides a way to find files and directories on storage card which consumes a lot of space.<br>
It displays diagram on which directories are displayed proportional to their size, also a few levels of subdirectories are displayed. Users are allowed to zoom in to look at specific directory content.<br>
Purpose of the program is to provide a way to find and cleanup spacehogs on storage card. It is not general purpose file manager.<br>

Screenshot for an ancient version:<br>
<img src="extra/screenshot.png">

YouTube video:
https://www.youtube.com/watch?v=TIiCQfWdtVg

Build Instructions
------------------
To build this project, you need:
- Android SDK Platform 31
- Android Build Tools 31.0.0
- NDK 21.4.7075529
- JDK 17 (Gradle 7.3.3 is incompatible with JDK 21)

Build command:
```bash
./gradlew assembleDebug
```
The APK will be located at `app/build/outputs/apk/debug/diskusage-v*-debug.apk`.
