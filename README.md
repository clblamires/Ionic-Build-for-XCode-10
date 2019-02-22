# Ionic-Build-for-XCode-10

If you have XCode 10 on your Macbook, you might notice that building for iOS always seems to fail. That's because XCode 10 uses (by default) a newer build system, one that is not compatible with the current version of cordova.

To fix it, download the `build.json` file you see here and put it in the root directory of your app.

Once you build your app for iOS, open the XCode project. Go to File > Project Settings and select `Legacy Build System`
