# YARNA - Yet Another ReactNative App
Just another ReactNative app. A sandbox where we can play with different concepts and technologies.

## License
This software is released under the GNU GPL 3. See the LICENSE file for full license.

## Prerequisites
The following is a list of prerequisites that are required in order to develop features within this project.

### Android Studio
Install Android Studio from https://developer.android.com/studio

### XCode
Install XCode from the Apple App Store or from https://developer.apple.com/xcode/

## Debugging
Instructions for running and debugging the projects.

### Running the Mobile Application
Ensure that a bundler is running.
react-native start

#### Running on Android
Start an Android emulator
./emulator -avd Pixel_3_API_29

List installed Android emulators
./emulator -list-avds

The Android SDK emulator tools are typically installed at ~/Library/Android/sdk/emulator

Run the Android debug build
yarn run:android

#### Running on iOS
Run the iOS debug build
yarn run:ios