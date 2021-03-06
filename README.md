## The Idea
This is an open project to create an Android application to allow user the ability to split bill by taking a photo of the receipt  after those gatherings with friends and family in a fun and simple way!

### Features
1. Using phone's camera to capture Receipts
2. Import photos from photo gallery
3. Read the items and amount from the receipt
4. Allow to select which item want to pay for.
5. Calculate the receipt, 3 methods available :
   1. Split the total amount evenly to everyone
   2. Select each item and it's amount by person
   3. Select which item to split evenly + each item and amount by person

Android version supported - Android 4.1 Jelly Bean and above

### Project Structure
```
├─ external libraries
├─ app
│  ├─ libs
│  ├─ src
│  │  ├─ androidTest
│  │  │  └─ java
│  │  │     └─ wwckl/projectmiki
│  │  └─ main
│  │     ├─ java
│  │     │  └─ wwckl/projectmiki
│  │     ├─ res
│  │     └─ AndroidManifest.xml
│  └─ proguard-rules.pro
├─ build.gradle
└─ settings.gradle
```
### Java Packages Architecture
```
wwckl/projectmiki
├─ models
├─ utils
├─ fragments
└─ views
   ├─ adapters
   ├─ actionbar
   ├─ widgets
   └─ notifications
```
### High-level Technical Req
1. [Project Miki Wiki](https://github.com/wwcodekl/project-miki-android/wiki)
2. OCR - https://code.google.com/p/tesseract-ocr/
3. Android Resources
   1. https://source.android.com/
   2. http://developer.android.com/training/basics/firstapp/index.html
   3. https://github.com/futurice/android-best-practices
4. Project Management Tools - https://trello.com/b/eTg0MwUT/project-miki
