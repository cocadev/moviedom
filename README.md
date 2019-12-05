<h1 align="center"><b> Youtube Streaming App</b> </h1>

<h1 align="center">
  <br>
  <kbd>
    <img src="https://image.prntscr.com/image/YrkdAm5xSxe0MmkqrvGeJA.png" alt="Animavita" height="525" width="725">
  </kbd>
  <br>
  <br><br>
</h1>

<p align="center">React Native UI challenge DEMO APP</p>

<p align="center"><i>"How to save a life?" - The Youtube</i> </p>

<p align="center">
  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/progress-40%25-brightgreen.svg" alt="PRs Welcome">
  </a>
  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/contribuition-welcome-brightgreen.svg" alt="PRs Welcome">
  </a>
  <a href="https://saythanks.io/to/wendelfreitas">
      <img src="https://img.shields.io/badge/SayThanks.io-%E2%98%BC-1EAEDB.svg">
  </a>
<a href="https://www.repostatus.org/#wip"><img src="https://www.repostatus.org/badges/latest/wip.svg" alt="Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public." /></a>  
</p>

<p align="center">
  <a href="#blush-overview">Overview</a> •
  <a href="#dizzy-roadmap">Roadmap</a> •
  <a href="#wrench-install-instructions">Install</a> •
  <a href="#zap-tech-stack">Tech Stack</a> •
  <a href="#iphone-Test">Test</a> •
  <a href="#eyes-version">Version</a> •
</p>

<p align="center">
  <kbd>
    <img width="250" style="border-radius: 5px" height="450" src="screenshots/1.PNG" alt="1">
  </kbd>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <kbd>
    <img width="250" style="border-radius: 5px" height="450" src="screenshots/2.PNG" alt="2">
  </kbd>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <kbd>
    <img width="250" style="border-radius: 5px" height="450" src="screenshots/3.PNG" alt="3">
  </kbd>
  <br/><br/>
  <kbd>
    <img width="250" style="border-radius: 5px" height="450" src="screenshots/4.PNG" alt="4">
  </kbd>
    &nbsp;&nbsp;&nbsp;&nbsp;
  <kbd>
    <img width="250" style="border-radius: 5px" height="450" src="screenshots/5.PNG" alt="5">
  </kbd>
    &nbsp;&nbsp;&nbsp;&nbsp;
  <kbd>
    <img width="250" style="border-radius: 5px" height="450" src="screenshots/6.PNG" alt="6">
  </kbd>
</p>

## :blush: **Overview?**

Animavita is a combination of two Latin words, ‘Animal’ and ‘Vitae’, which means respectively ‘Animal’ and ‘Life’. This is an idea to create or animate something that was born a while ago, when I realized that facebook is used to publicize adoption and also ask for help for animals that lives on the streets.

Animavita's purpose is not to change how people use facebook to the activities described above, but to centralize the helpful information in a single application. Anyone can make an adoption request, but it doesn’t mean that the pet will be automatically adopted. It means that the person interested can talk to the person who registered the pet, allowing both sides to have a conversation, and the user to research and decide his favorite pet.

## :dizzy: **Roadmap**

-   [x] Make it work on IOS
-   [x] Make it work on Android
-   [x] Transform into responsive
-   [x] Update to latest React Native version

## :wrench: **Install instructions**

### Getting Started

#### 1) Clone & Install Dependencies

- 1.1) `git clone https://github.com/funnyjerry/react-native-homeautomation-app.git`
- 1.2) `cd react-native-homeautomation-app` - cd into your newly created project directory.
- 1.3) Install NPM packages with `yarn install`
        **Note:** NPM has issues with React Native so `yarn` is recommended over `npm`.
- 1.4) **[iOS]** `cd ios` and run `pod install` - if you don't have CocoaPods you can follow [these instructions](https://guides.cocoapods.org/using/getting-started.html#getting-started) to install it.
- 1.5) **[Android]** If you haven't already generated a `debug.keystore` file you will need to complete this step from within the `/android/app` folder. Run `keytool -genkey -v -keystore debug.keystore -storepass android -alias androiddebugkey -keypass android -keyalg RSA -keysize 2048 -validity 10000`

#### 2) Start your app

- 2.1) **[iOS]** Build and run the iOS app, run `react-native run-ios` (to run on simulator) or `react-native run-ios --device` (to run on real device) from the root of your project. The first build will take some time.
- 2.2) **[Android]** If you haven't already got an android device attached/emulator running then you'll need to get one running (make sure the emulator is with Google Play / APIs). When ready run `react-native run-android` from the root of your project.

## :zap: **Tech Stack**

<h1 align="center">
  <img src="https://ionicframework.com/docs/assets/icons/logo-react-icon.png" alt="RN" height="100" width="100">
  <br>
</h1>

-   [React Native](https://github.com/facebook/react-native)
-   [Eslint](https://eslint.org/)

## :iphone: **Test**

- [x] Test on Android
- [x] Test on iOS

## :eyes: **Version**
- [x] React-Native (0.59.9)
- [ ] Expo 35