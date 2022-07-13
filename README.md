# README

Demonstrate how to build simple Flutter Apps.

TODO:

* Sound recorder - tau sounds runs but doesn' capture audio  
* emulator dimensions.  
* Copying files from the emulator
* Building and getting image onto my phone

## Prerequisites

```sh
brew install android-studio
brew install flutter

# add the android sdk manager in android studio

flutter doctor

flutter doctor --android-licenses 

sudo gem install cocoapods

# ensure everything is green
flutter doctor
```

## VSCode

NOTES:

* Select the device in the bottom right corner.  
* Run using run and debug
* Sometimes you have to enter the ios directory and `pod install`

```sh
code --install-extension dart-code.flutter
```

## Building and running (android)

```sh
# getting packages from pubspec.yaml
flutter pub get 

# build and package only
flutter build apk 

# start emulator
flutter emulators --launch flutter_emulator --cold

# run app
flutter run
```

## Building and running (macosx)

```sh
cd ios
pod install
```

## Emulators

```sh
# copying file to and from emulator

```


## 01 - Basic Project

A new Flutter project.  
Steps [README.md](./01_basic_project/README.md)  

## 02 - Skeleton

Build an app following a tutorial from a skeleton.  
Steps [README.md](./02_skeleton/README.md)  

## Resources

* Flutter docs [here](https://docs.flutter.dev/)
https://docs.flutter.dev/get-started/install/macos

https://gallery.flutter.dev/#/

https://docs.flutter.dev/development/packages-and-plugins/using-packages

Cocoa
https://guides.cocoapods.org/using/getting-started.html#installation


https://stackoverflow.com/questions/54444538/how-do-i-run-test-my-flutter-app-on-a-real-device

## Troubleshooting

Let’s be explicit about our intent(-filters)
https://medium.com/androiddevelopers/lets-be-explicit-about-our-intent-filters-c5dbe2dbdce0


https://pub.dev/packages/permission_handler

