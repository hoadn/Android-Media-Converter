![](app/src/main/res/mipmap-xhdpi/ic_launcher.png)  
# Android Media Converter
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](LICENSE) [![CircleCI](https://img.shields.io/circleci/project/github/Khang-NT/Android-Media-Converter.svg)](https://circleci.com/gh/Khang-NT/Android-Media-Converter) [![Latest Release](https://img.shields.io/github/release/Khang-NT/Android-Media-Converter.svg)](https://github.com/Khang-NT/Android-Media-Converter/releases)

**Media Converter** is a robust Android application build on top of [`FFmpeg`](https://ffmpeg.org) with clean UI.
As it name, user can convert media file to other encoding format easily with preset commands. The app 
also can be extended, by allowing user to create their own command.

## Build app
To build the app, you need to create [Fabric](https://fabric.io) account, then place your Fabric's api
key in `app/fabric.properties` file:

```
apiKey=your_api_key_here
```

Also change `signingConfigs` in `app/build.gradle` file with your own key store if you want build signed release 
apks.

## Contributing
You are welcome to open new [PR](https://github.com/Khang-NT/Android-Media-Converter/pulls) or [issue](https://github.com/Khang-NT/Android-Media-Converter/issues) 
for bugs fix or features request.

## FFmpeg license
This software uses code of <a href=http://ffmpeg.org>FFmpeg</a> licensed under the <a href=http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html>LGPLv2.1</a>.
FFmpeg binary files are prebuilt, you can download source and build script from this repo [ffmpeg-binary-android](https://github.com/Khang-NT/ffmpeg-binary-android).

## License
**Media Converter** is released under the GNU General Public License v3.0 (GPLv3), which can be found here:  
[LICENSE](LICENSE)
