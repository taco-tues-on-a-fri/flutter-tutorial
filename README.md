# wordpair_generator

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


# Flutter Setup & Notes

## 1. Download SDK

Download Flutter SDK, extract the "Flutter" folder and put it in your user's home directory ( `MacintoshHD/Users/mrkittens`)

https://flutter.dev/docs/get-started/install

## 2. Add path

Add path for 'location/flutter/bin'

For zsh shell:
```
$ open ~/.zshrc
```
Then add the following, save and restart shell.
```
export PATH=$HOME/flutter/bin:$PATH
```

## 3. Check dependencies

```
$ flutter doctor
```

## 4. Install CocoaPods
Install CocoaPods by running the following command:
```
$ sudo gem install cocoapods
```

## 4. Install Xcode (Mac)


Don't install Xcode from the App Store. Install it from: 

 https://developer.apple.com/downloads

Do this for three reasons:

1. It will allow you to have multiple versions of Xcode on your machine
2. If you have multiple Macs, you can transfer the file quickly between them
3. The App Store version will auto-update if you have automatic updates turned on and that can break your builds

[(source)][1]

Ensure Xcode app is in the /Applications directory (   NOT `/Users/{user}/Applications`   ).

[1]: https://www.reddit.com/r/iOSProgramming/comments/d75k9y/anyone_else_having_issues_downloading_xcode_11/f0xpktl/

## 5. Configure Xcode command line tools (Mac)

```
$ sudo xcode-select --switch /Applications/Xcode.app/Contents/Developer
$ sudo xcodebuild -runFirstLaunch
$ sudo xcodebuild -license
```

## 6. Test iOS Simulator (Mac)

```
open -a Simulator
```

## 7. Install Android Studio

https://developer.android.com/studio

## 8. Install Android Studio Flutter plugin

macOS
In Android Studio go to:

1. `Preferences > Plugins` then search `flutter` and click `install`

2. Click Yes when prompted to install the Dart plugin.

## 9. Create virtual device from AVD manager

## 10. Install VSCode Flutter extension

## 11. Create flutter app

```
flutter create my_app
```

## 12. Run Debugger in VSCode

You should now be setup to start edit