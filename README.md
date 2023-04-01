![](/assets/logo/logo_full.png)

![flutter support](https://img.shields.io/badge/flutter%20support-%3E%3D%20%203.3.0-skyblue)
![dart support](https://img.shields.io/badge/dart%20support-%3E%3D%20%202.14.0-blue)
![python support](https://img.shields.io/badge/python%20support-%3E%3D%20%203.8.0-yellow)
![go support](https://img.shields.io/badge/go%20support-%3E%3D%20%201.18.0-blue)

The application aims to help users classify waste quickly and accurately, while also providing knowledge about waste classification and increasing awareness of the environmental impact of waste.

## Overall

<img alt="SoWaste Overall" src="./images/overall.png" width="100%" />

<hr />

## Project structure module

Project compose 3 git submodules:

1. Mobile Application: [current repository](./)
2. Backend: [./sowaste-backend](https://github.com/GDSC-UIT/sowaste-backend.git)
3. AI Model: [./waste_detect_api](https://github.com/tien02/waste_detect_api.git)

README.MD : are covered in each module for clearer explanation + installation + self-host solution

<hr />

## How to run the project

Bellow steps are required to run fully gateway application which include Flutter - Go - Python:

## Mobile Installation

Download APK file **<ins>[here](https://www.tuankietcoder.tech/file/sowaste.apk)!</ins>**

## Local Installation

**Requirements**:

- Flutter: [https://docs.flutter.dev/get-started/install](https://docs.flutter.dev/get-started/install)
- Dart: [https://dart.dev/get-dart](https://dart.dev/get-dart)
- Android Studio: [https://developer.android.com/studio](https://developer.android.com/studio)
- Xcode: [https://developer.apple.com/xcode/](https://developer.apple.com/xcode/)
- Or you can use physical device to run the project. You can find the instruction [here](https://flutter.dev/docs/get-started/install/macos#set-up-the-ios-device) (for iOS) and [here](https://flutter.dev/docs/get-started/install/windows#set-up-the-android-device) (for Android).

**Steps**:

- Clone project to local machine:

```bash
git clone https://github.com/GDSC-UIT/SoWaste.git
```

- Open your terminal and run the following commands:

```bash
cd SoWaste
```

- Run the following commands to install all dependencies:

```bash
flutter pub get
```

- Run the following commands to run the project:

```bash
flutter run
```

- Run the following commands in production mode:

```bash
flutter run --release
```

**Note**: If you meet the problem from installation, you should:

- Check your internet connection;
- Run `flutter clean` and `flutter run`;
- Delete `graddle-wrapper.jar` file from `android/gradle/wrapper/gradlle-wrapper.jar` and `flutter run`.

## Backend Installation

You can find the backend installation guide [here](https://github.com/GDSC-UIT/sowaste-backend/blob/main/README.md)

## AI Model Installation

You can find the AI model installation guide [here](https://github.com/tien02/waste_detect_api/blob/main/README.md#run-on-local)

<hr />

## Contributors:

![](https://contrib.rocks/image?repo=GDSC-UIT/sowaste)
