# nazmos-sakib.github.io

# [TrinkBrunnen:Stay Hydrated with Ease]() Android App  📱
<a href=""><img src="app/src/main/res/mipmap-hdpi/ic_launcher.png?raw=true" height="70"></a> <a href=""><img src="https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png" height="75"></a>


<img align="left" alt="java" height="25px" src="https://upload.wikimedia.org/wikipedia/de/e/e1/Java-Logo.svg" />
<img align="left" alt="kotlin" height="25px" src="https://upload.wikimedia.org/wikipedia/commons/0/06/Kotlin_Icon.svg" />
<img align="left" alt="gradle" height="25px" src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Gradle_logo.svg" />
<img align="left" alt="android studio" height="25px" src="https://upload.wikimedia.org/wikipedia/commons/5/55/Android_Studio_Logo_%282023%29.svg" />
<img align="left" alt="Parse" height="25px" src="https://parseplatform.org/img/logo.svg" />
<br/>
<br/>
<br/>


Trinkbrunnen is your ideal companion for staying hydrated while exploring the city. Designed with simplicity and convenience in mind, this Android app empowers users to discover, save, and even contribute to the ever-growing list of public drinking fountains. Whether you're a local or a traveler, Trinkbrunnen makes sure you never go thirsty again.

Key Features:
=====

+ 🌍 [Location-Aware:]() Trinkbrunnen uses your device's GPS to pinpoint your location, helping you find the nearest drinking fountains effortlessly.

+ 🚰 [Find Fountains:]() Discover drinking fountain locations around you on an intuitive map interface, ensuring you always have access to clean and refreshing water.

+ 🔍 [Search for Fountains:]() Looking for water sources in a specific area? Trinkbrunnen's search feature allows you to search for fountain locations and view available fountains within your search area.

+ 🗺️ [Turn-by-Turn Navigation:]() Need to reach a fountain? Trinkbrunnen provides turn-by-turn directions to guide you to your chosen fountain location seamlessly.

+ 📌 [Save Favorites:]() Mark your favorite fountain locations for quick access later. Perfect for planning your routes and ensuring you never run out of hydration options.

+ ✏️ [Contribute and Edit:]() Did you spot a new fountain or need to correct existing information? Trinkbrunnen lets you easily add and edit fountain locations to help the community.

+ 🌟 [User-Friendly:]() The app's clean and user-friendly design ensures a seamless experience, making it suitable for users of all ages.

Never worry about finding water sources during your outdoor adventures, city walks, or daily routines. Stay hydrated, explore with confidence, and share the joy of clean drinking water with Trinkbrunnen.


## Screenshots of the app

| <img src="app/SchreenShots/Screenshot_20230912-214357.png"> | <img src="app/SchreenShots/Screenshot_20230912-214406.png">  | <img src="app/SchreenShots/Screenshot_20230912-214433.png">  | <img src="app/SchreenShots/Screenshot_20230912-214444.png">  | <img src="app/SchreenShots/Screenshot_20230912-214453.png"> |
| ---------------------------------------------- | -------------------------------------------- | ------------------------------------------- | ------------------------------------------- | ------------------------------------------- |


|  <img src="app/SchreenShots/Screenshot_20230912-214504.png">  | <img src="app/SchreenShots/Screenshot_20230912-214513.png">  | <img src="app/SchreenShots/Screenshot_20230912-214523.png">  | <img src="app/SchreenShots/Screenshot_20230912-214541.png"> |
| ---------------------------------------------- | -------------------------------------------- | ------------------------------------------- | ------------------------------------------- |

|  <img src="app/SchreenShots/Screenshot_20230912-214616.png">  | <img src="app/SchreenShots/Screenshot_20230912-214702.png">  | <img src="app/SchreenShots/Screenshot_20230912-214754.png">  | <img src="app/SchreenShots/Screenshot_20230912-214819.png"> | <img src="app/SchreenShots/Screenshot_20230912-214824.png">  | 
| ---------------------------------------------- | -------------------------------------------- | ------------------------------------------- | ------------------------------------------- | ------------------------------------------- | 




Android Build
=====
>compileSdk 33 <br>
>minSdk 24 <br>
>targetSdk 33 <br>

Dependencies
=====
```
dependencies {

    //implementation 'androidx.core:core-ktx:1.10.1'
    implementation 'androidx.core:core-ktx:1.7.0'
    implementation 'androidx.appcompat:appcompat:1.6.1'
    implementation 'com.google.android.material:material:1.9.0'
    implementation 'androidx.constraintlayout:constraintlayout:2.1.4'
    testImplementation 'junit:junit:4.13.2'
    androidTestImplementation 'androidx.test.ext:junit:1.1.5'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.5.1'

    //for parse server
    implementation "com.github.parse-community.Parse-SDK-Android:parse:4.2.0"

    //osmdroid
    implementation 'org.osmdroid:osmdroid-android:6.1.16'
    implementation 'org.osmdroid:osmdroid-geopackage:6.1.10'

    //osm bonuspack for routing
    implementation(name:'osmbonuspack_6.9.0', ext:'aar')
    implementation 'org.apache.commons:commons-lang3:3.12.0'
    implementation 'com.google.code.gson:gson:2.10.1'
    implementation 'com.squareup.okhttp3:okhttp:5.0.0-alpha.11'

    // Mapbox Navigation SDK
    implementation "com.mapbox.navigation:android:2.10.1"
    implementation "com.mapbox.navigation:ui-dropin:2.13.1"
}
```

[osmdroid](https://osmdroid.github.io/osmdroid/)
=====
osmdroid's MapView is basically a replacement for Google's MapView class. It also includes a modular tile provider system with support for numerous online and offline tile sources and overlay support with built-in overlays for plotting icons, tracking location, and drawing shapes.

[OSMBonusPack](https://code.google.com/archive/p/osmbonuspack/)
=====
osmdroid is a library to interact with OpenStreetMap data inside an Android application. It offers an almost full/free replacement to Android map objects: MapView, MapController, Overlays, etc.
The OSMNavigator application demonstrates the use of these classes. This is a generic-purpose Map/Navigation tool, including a KML viewer and editor.

[Framework](https://parseplatform.org)   <img align="left" alt="Parse" height="25px" src="https://parseplatform.org/img/logo.svg" />
=======
Parse is the most used open-source framework to develop application backends. It helps developers to accelerate app development and reduces the total amount of effort required to build an app. A large community of engaged developers supports the platform and has been evolving it since 2016.  It’s a great tool to develop apps quickly and under an affordable budget.

[MapBox](https://www.mapbox.com)
=====
Mapbox provides powerful routing engines, accurate, traffic-powered travel times, and intuitive turn-by-turn directions to help you build engaging navigation experiences.

Permissions
=======
  
    android.permission.ACCESS_FINE_LOCATION -> to access precise location
    android.permission.ACCESS_COARSE_LOCATION -> approximate location 
    android.permission.ACCESS_NETWORK_STATE -> to check the current network connectivity status of the device.
    android.permission.INTERNET ->  allows an app to access the internet
    android.permission.ACCESS_BACKGROUND_LOCATION ->  to access the device's location even when the app is running in the background. 

User Data collection
=======
    User Name
    User Email
    User Current location

***User current location*** is only used to fetch available fountain location nearby. It is never stored and shared.
To save a location in you bookmark and/or to add a new fountain location one must create a user account with ***name, email*** and ***password***
Name and Email is ***visible*** to database admin but ***password*** is ***encrypted*** and ***not visible*** to database admin.


Note
====
This has not been tested on all phones, such as xiaomi phones and Android 5.x.

[Download]()
========
Download Trinkbrunnen now and join the community of users committed to making hydration accessible for all.


License
=======



# [Privacy Policy](https://sites.google.com/view/trinkbrunnen-privacy-policy/home)

sakib built the Trinkbrunnen app as a Free app. This SERVICE is provided by sakib at no cost and is intended for use as is.

If you choose to use my Service, then you agree to the collection and use of information in relation to this policy. The Personal Information that I collect is used for providing and improving the Service. I will not use or share your information with anyone except as described in this Privacy Policy. Further Details can be found [here](https://sites.google.com/view/trinkbrunnen-privacy-policy/home)


## Development version :hammer:

*   [APK (direct download)]()

## Support :rescue\_worker\_helmet:

If you need assistance or want to ask a question about the Android app, you are welcome to [ask for support](mailto:to.nazmos.sakib@gmail.com) in our Forums. If you have found a bug, feel free to [open a new Issue on GitHub](). Keep in mind, that this repository only manages the Android app. If you find bugs or have problems with the server/backend, you should ask the [Back4app server team](www.back4app.com/) for help!

## Remarks :scroll:

Google Play and the Google Play logo are trademarks of Google Inc.
