## Hello World CRNA/Expo Standalone Example

This is a minimal configuration to set your app up to build a standalone
app from your Create React Native Project with Expo. The only notable
changes from a new project are in `app.json`, where I added a bunch of
fields that you need to build a standalone app with Expo.

- Clone this project
- run `npm i` inside of it
- Install exp globally (`npm i -g exp`)
- Log in to your Expo account with `exp login` ([sign up first if you have to](https://expo.io/signup))
- Run `exp build:android` and/or `exp build:ios`
- Once the build starts, run `exp build:status` to check the progress.  When the build is complete, `exp build:status` will return a url to download your app archive.
- Install that on your phone with `adb install file-name-here.apk` on Android or put it on TestFlight to try it on iOS.
