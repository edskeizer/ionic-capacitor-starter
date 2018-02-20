
# Capacitor & Ionic v3 
This repo was made to have a blank Ionic v3 together with [Capacitor](https://github.com/ionic-team/capacitor/), based on Josh Morony's [tutorial](https://www.joshmorony.com/an-early-look-at-capacitor-a-new-native-bridge-for-web-apps/).


## Prerequisites
Use Node v8+ to have the `npx` command available. 

Install Cocoapods if necessary: `sudo gem install cocoapods`

Run `npm install` 

## How to build
Build the code using:

`$ npm run ionic:build --prod`

### For iOS testing
Add iOS as platform: `npx capacitor add ios`

Run `npx capacitor copy ios` (this copies your builded code to the ios platform) 

and run `npx capacitor open ios` respectively.

### For Android testing
Add Android as platform: `npx capacitor add android `

Run `npx capacitor copy android` (this copies your builded code to the android platform) 

and run `npx capacitor open android` respectively.