# dump-ios-jsbundle

Dump encrypted `main.jsbundle` file at runtime

## Usage

```sh
# This script dumps main.jsbundle on the iOS device filesystem `/var/mobile/Documents/main.jsbundle`
frida -U -f com.example.foo -l ./dump.js
frida -U -N com.example.foo -l ./dump.js
```

## Similar Repositories

- [dump-index-android-bundle](https://github.com/d0ublew/dump-index-android-bundle) (for Android platform)
