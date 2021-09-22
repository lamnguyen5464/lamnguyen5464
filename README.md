# Hallo

## About `lamnguyen5464`
Hi ✌️

Call me Truong Lam - Mobile developer.

I'm into Android native (Java/Kotlin), iOS native (Swift) and cross-platform technologies (React-native, Flutter).
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=lamnguyen5464&layout=compact)](https://github.com/anuraghazra/github-readme-stats)



---
## Side Projects

### [Where my Images](https://github.com/lamnguyen5464/RN-WhereMyImage)
Caption-based images gallery search Application

#### Usage

Find photos in gallery that match the user's filter tags (through provided keywords or user’s description).
Use ML-Kit to integrate TensorFlow Lite model for processing images-labeling in asynchronous thread at native modules (Java, Swift) and emitting to React-native through RCTEventEmitter.

#### Install

For Window users, you should run:

```
npm run all_window
```

or Mac_er only run:

```
npm run all
```

...to install neccessary packages and start metro bundle before build/run in Android Studio/Xcode

#### Screenshot
<img src="https://user-images.githubusercontent.com/45004786/133646152-6dfe767e-3813-45ef-bd5a-ca179a2af642.png" height="300"/> 
<img src="https://user-images.githubusercontent.com/45004786/133648032-a555b915-00e4-4eb0-a7e7-f7382ca48370.png" height="300"/> 

---

###  [Draw together (demo)](https://github.com/lamnguyen5464/Draw-together-beta)

#### Set up
After clone this project, set up environment of NodeJS (for run local sever), Android Studio, Xcode (if you want to build iOS app).
Change direction to this source and run this setting-up script that I have prepared in `yarn` or `npm`:

```
yarn setup
```
or 
```
npm run setup
```
This scrip is constructed to set up local websocket server with `PORT: 3000` and sync url to configuration files in Android Studio and XCode

#### Tech stack
Kotlin, Java (Android app), Swift (iOS app), NodeJs, Express, SocketIO.

#### Demo

<img src="drawTogetherDemo.gif" alt="drawing" width="300"/>

---

### [Colors-constant-generator](https://github.com/lamnguyen5464/colors-constant-generator)
This repo provides a great deal of color contants in heximal for App development code base


##### [Colors.js](https://github.com/lamnguyen5464/colors-constant-generator/blob/master/res/Colors.js) for ReactJs/ReactNative or other JS frameworks
```JavaScript
const Colors = {
  apricot: "#fcb671",
  baby_blue: "#a3d0f7",
  back_fund_30: "#00000030",
  back_fund_75: "#00000075",
  background_gray: "#edeeee",
  black: "#000000",
...
```

##### [colors.xml](https://github.com/lamnguyen5464/colors-constant-generator/blob/master/res/colors.xml) for Android native application developement
```xml
<?xml version="1.0" encoding="utf-8"?>
<resources>
    <color name="APRICOT">#fcb671</color>
    <color name="BABY_BLUE">#a3d0f7</color>
    <color name="BACK_FUND_30">#00000030</color>
    <color name="BACK_FUND_75">#00000075</color>
    <color name="BACKGROUND_GRAY">#edeeee</color> 
...
```

##### [UIColor+Extensions.swift](https://github.com/lamnguyen5464/colors-constant-generator/blob/master/res/UIColor%2BExtensions.swift) for iOS native application developement
```Swift
extension UIColor{
    static func getColor(hex: String) -> UIColor{
        switch hex {
        case "apricot":	//#fcb671
            return UIColor(red: 0.9882352941176471, green: 0.7137254901960784, blue: 0.44313725490196076, alpha: 1);
        case "baby_blue":	//#a3d0f7
            return UIColor(red: 0.6392156862745098, green: 0.8156862745098039, blue: 0.9686274509803922, alpha: 1);
        case "back_fund_30":	//#00000030
            return UIColor(red: 0, green: 0, blue: 0, alpha: 0.18823529411764706);
...
```

##### [colors.dart](https://github.com/lamnguyen5464/colors-constant-generator/blob/master/res/colors.dart) for Flutter app developement
```Dart
import 'package:flutter/material.dart';
const APRICOT = Color(0xfffcb671);   //#fcb671
const BABY_BLUE = Color(0xffa3d0f7);   //#a3d0f7
const BACK_FUND_30 = Color(0xff00000030);   //#00000030
const BACK_FUND_75 = Color(0xff00000075);   //#00000075
const BACKGROUND_GRAY = Color(0xffedeeee);   //#edeeee 
...
```
---
### [MiniPocket](https://github.com/lamnguyen5464/MiniPocket)
- [Google Play Store](https://play.google.com/store/apps/details?id=com.lamnguyen5454.myapplication.wolit)

#### Demo

<img src="https://user-images.githubusercontent.com/45004786/90224444-e124aa00-de39-11ea-8563-45f84f18249b.png" width="150"/> <img src="https://user-images.githubusercontent.com/45004786/90224452-e4b83100-de39-11ea-9ff5-ed67bc4495c1.png" width="150"/> <img src="https://user-images.githubusercontent.com/45004786/90224472-eb46a880-de39-11ea-8164-bd8d923ace42.png" width="150"/> <img src="https://user-images.githubusercontent.com/45004786/90224504-f8fc2e00-de39-11ea-8b8b-476b0289bf21.png" width="150"/> <img src="https://user-images.githubusercontent.com/45004786/90224511-fac5f180-de39-11ea-85fd-8ec15856aa70.png" width="150"/> 

---
### [HowPopular?](https://github.com/lamnguyen5464/How-popular-Android)
- [Google Play Store](https://play.google.com/store/apps/details?id=com.lforestor.dominodemo&hl=en)

#### Demo
<img src="https://user-images.githubusercontent.com/45004786/90223927-25637a80-de39-11ea-8a0f-2b1f45fbcfe2.png" width="150"/> <img src="https://user-images.githubusercontent.com/45004786/90224015-3dd39500-de39-11ea-87f7-9da89070cbf8.png" width="150"/> <img src="https://user-images.githubusercontent.com/45004786/90224026-41ffb280-de39-11ea-92c9-a5afa04dd1aa.png" width="150"/> <img src="https://user-images.githubusercontent.com/45004786/90224030-42984900-de39-11ea-945e-834c0855458b.png" width="150"/> <img src="https://user-images.githubusercontent.com/45004786/90224182-7a06f580-de39-11ea-84c7-1053153fe691.png" width="150"/> 

---
### [Phrasal Verbs Quiz](https://github.com/lamnguyen5464/PhrasalVerb_ios) 
#### Demo
<img src="https://user-images.githubusercontent.com/45004786/90224844-85a6ec00-de3a-11ea-9d87-23e3efddbaf4.png" width="170"/> <img src="https://user-images.githubusercontent.com/45004786/90224850-8770af80-de3a-11ea-9af9-91f6fc539c38.png" width="170"/> <img src="https://user-images.githubusercontent.com/45004786/90224853-88094600-de3a-11ea-8fb8-2ece88b118a1.png" width="170"/> <img src="https://user-images.githubusercontent.com/45004786/90224858-88a1dc80-de3a-11ea-9ca4-80c55406bce6.png" width="170"/> 

---
### [MiniUno](https://github.com/lamnguyen5464/MiniUno)
- [Google Play Store](https://play.google.com/store/apps/details?id=com.lforestor.superminiuno)
#### Demo
<img src="https://user-images.githubusercontent.com/45004786/90223115-a6ba0d80-de37-11ea-83bb-315be6552851.png" width="150"/> <img src="https://user-images.githubusercontent.com/45004786/90223150-b6395680-de37-11ea-9940-016d0dd96133.png" width="150"/> <img src="https://user-images.githubusercontent.com/45004786/90223252-e5e85e80-de37-11ea-87c8-0a9a60ebcecb.png" width="150"/> <img src="https://user-images.githubusercontent.com/45004786/90223394-2647dc80-de38-11ea-8e19-1ad4bc436454.png" width="150"/> <img src="https://user-images.githubusercontent.com/45004786/90223404-2942cd00-de38-11ea-99cb-0b6c1e1078ab.png" width="150"/> 

---
### [MiniDomino](https://github.com/lamnguyen5464/MiniDomino)
- [Google Play Store](https://play.google.com/store/apps/details?id=com.lforestor.dominodemo&hl=en)
#### Demo
<img src="https://user-images.githubusercontent.com/45004786/79688574-4d6f1280-8279-11ea-9c83-e03be0cb4763.png" width="150"/> <img src="https://user-images.githubusercontent.com/45004786/79688641-c40c1000-8279-11ea-94ea-bbf4cbac255b.png" width="150"/> <img src="https://user-images.githubusercontent.com/45004786/79688657-e140de80-8279-11ea-9980-f49ec9dccf2c.png" width="150"/> <img src="https://user-images.githubusercontent.com/45004786/79688669-f158be00-8279-11ea-8cc7-faf79474e951.png" width="150"/> <img src="https://user-images.githubusercontent.com/45004786/79688681-02a1ca80-827a-11ea-9dcf-226584523013.png" width="150"/> 


