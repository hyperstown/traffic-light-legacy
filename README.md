<img width="128px" src="https://github.com/hyperstown/traffic-light-legacy/blob/main/fastlane/metadata/android/en-US/images/icon.png?raw=true" alt="Logo">

# Traffic Light (Legacy)
Traffic Light is an open-source tool to track your network speed and data usage inspired by Internet Speed Meter and created by [leekleak](https://github.com/leekleak/). **This fork aims to provide support for older devices (Android 6+) as original app goes only as low as Android 8.**

## QA

- Q: How to download? \
  A: Go to [releases page](/release) and download apk.

- Q: Why not upstream the changes?\
  A: Even if now it is possible to make it work on Android 6 sooner rather than later it will be just extremely difficult to build for older Androids. 
  I don't want to burden original dev with spaghetti code that increases userbase by 3 people.

- Q: Do you plan to maintain this project in a way it's constantly in up to date with upstream? \
  A: No. Android 6 is a dead platform, at some point backporting this app will be near impossible. I might sync with the upstream from time to time but right now it's safe to assume it's the last version.

- Q: Why don't you support Android 5 or 4.4 or 1.0? \
  A: Android 7 is the oldest Android that I can emulate without issues in Android Studio, Android 6 is the oldest Android I still have access to. If you really want to make it work on Android 5 or 4.x you can send PR, but core functionality should be the same.

- Q: Can I use it on newer Android? \
  A: Yes but why? Just go to [original project](https://github.com/leekleak/traffic-light/)

- Q: Part of the app doesn't work, what should I do? \
  A: You can create an issue but due to my limited time and the fact that Android 6 is a dead platform I probably won't fix it. PRs are welcome of course. Please don't report known issues as well.

- Q: Can I request a feature?\
  A: Request it in upstream. If it's already in upstream you can request a sync.


## Know issues

- Theme switcher doesn't work
- Some M3 icons in app are blurry

## Why?
- Why not?

## Why Traffic Light?
- Free and open source
- Uses [fewer permissions](https://github.com/leekleak/traffic-light/wiki/Permissions)
- Uses [less battery](https://github.com/leekleak/traffic-light/wiki/Battery-Usage)
- No tracking
- Beautiful UI
- Incredibly small app size

## Downloads

[<img alt='Get it on GitHub' height="80" src='branding/badge_github.png'>](/releases) |
--------------------------------------------------------------------------------------------------------------------------------|

## Screenshots

| ![Screenshot 1](fastlane/metadata/android/en-US/images/phoneScreenshots/screenshot01.png) | ![Screenshot 2](fastlane/metadata/android/en-US/images/phoneScreenshots/screenshot02.png) | ![Screenshot 3](fastlane/metadata/android/en-US/images/phoneScreenshots/screenshot03.png) | ![Screenshot 4](fastlane/metadata/android/en-US/images/phoneScreenshots/screenshot04.png) |
|-------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|
