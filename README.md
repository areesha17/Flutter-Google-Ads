<h1 align="center">Flutter Mobile Google Ads </h1>

</h1>
<p align="center">
   <a href="https://github.com/sagarshende23">
    <img src="https://img.shields.io/badge/Github-Sagar Shende-black.svg?style=for-the-badge">
  </a>
  <a href="https://github.com/sagarshende23/reflectly-like-loginpage-flutter/stargazers">
    <img src="https://img.shields.io/github/stars/sagarshende23/flutter_google_ads.svg?style=for-the-badge">
  </a>
  <a href="https://play.google.com/store/apps/details?id=com.alltechsavvy.calculator">
    <img src="https://img.shields.io/badge/Google-PlayStore-green.svg?style=for-the-badge">
  </a>
   <a href="https://www.youtube.com/channel/UCEW4YMELtVeLjcpAzevNabg">
    <img src="https://img.shields.io/badge/YouTube-AllTechSavvy-red.svg?style=for-the-badge">
  </a>
 <a href="https://github.com/sagarshende23/flutter_google_ads">
    <img src="https://img.shields.io/badge/Open-Source-green.svg?style=for-the-badge">
  </a>  
   
 
</p>

[![Youtube](https://raw.githubusercontent.com/sagarshende23/shared_preference_flutter/master/Subscribe.png)](https://www.youtube.com/channel/UCEW4YMELtVeLjcpAzevNabg)




## Prerequisites


*   Android
    *   Target Android API level 19 or higher
    *   Set `compileSdkVersion` to 28 or higher
*   Ios
    *   Latest version of Xcode with [enabled command-line tools](https://flutter.dev/docs/get-started/install/macos#install-xcode).


#### Update your Info.plist

Update your app's `ios/Runner/Info.plist` file to add two keys:

* A `GADApplicationIdentifier` key with a string value of your AdMob app ID ([identified in the AdMob UI](https://support.google.com/admob/answer/7356431)).
* A `SKAdNetworkItems` key with Google's `SKAdNetworkIdentifier` value of `cstr6suwn9.skadnetwork`.

```xml
<key>GADApplicationIdentifier</key>
<string>ca-app-pub-3940256099942544~1458002511</string>
<key>SKAdNetworkItems</key>
  <array>
    <dict>
      <key>SKAdNetworkIdentifier</key>
      <string>cstr6suwn9.skadnetwork</string>
    </dict>
  </array>
```

#### Update AndroidManifest.xml

The AdMob App ID must be included in the `AndroidManifest.xml`. Failure to do so will result in a crash on launch of an app.

Add the AdMob App ID ([identified in the AdMob UI](https://support.google.com/admob/answer/7356431)) to the app's `android/app/src/main/AndroidManifest.xml` file by adding a `<meta-data>` tag with name `com.google.android.gms.ads.APPLICATION_ID`, as shown below. You can find your App ID in the AdMob UI. For `android:value` insert your own AdMob App ID in quotes, as shown below.


```xml
<manifest>
    <application>
        <meta-data
            android:name="com.google.android.gms.ads.APPLICATION_ID"
            android:value="ca-app-pub-3940256099942544~3347511713"/>
    </application>
</manifest>
```


& then Initialize the Mobile Ads SDK

## ???? Watch Video on How to Add new Google Mobile Ads in Flutter App 2021 #

[![Youtube](https://raw.githubusercontent.com/sagarshende23/flutter_google_ads/master/flutter_ads%20_2021.png)](https://youtu.be/X6Cz48cLuE4)

####  Select Banner Ads Sizes

The table below lists the standard banner sizes.

<table>
  <tr>
   <td><strong>Size in dp (WxH)</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>AdSize Constant</strong>
   </td>
  </tr>
  <tr>
   <td>320x50
   </td>
   <td>Standard Banner
   </td>
   <td><code>banner</code>
   </td>
  </tr>
  <tr>
   <td>320x100
   </td>
   <td>Large Banner
   </td>
   <td><code>largeBanner</code>
   </td>
  </tr>
  <tr>
   <td>320x250
   </td>
   <td>Medium Rectangle
   </td>
   <td><code>mediumRectangle</code>
   </td>
  </tr>
  <tr>
   <td>468x60
   </td>
   <td>Full-Size Banner
   </td>
   <td><code>fullBanner</code>
   </td>
  </tr>
  <tr>
   <td>728x90
   </td>
   <td>Leaderboard
   </td>
   <td><code>leaderboard</code>
   </td>
  </tr>
  <tr>
   <td>Screen width x 32|50|90
   </td>
   <td><a href="https://developers.google.com/admob/android/banner/smart">Smart Banner</a>
   </td>
   <td>Use <code>getSmartBanner(Orientation)</code>
   </td>
  </tr>
  <tr>
   <td>Provided width x Adaptive height</td>
   <td><a href="https://developers.google.com/admob/android/banner/adaptive">Adaptive Banner</a></td>
   <td>Use <code>getAnchoredAdaptiveBannerAdSize(Orientation, int)</code></td>
  </tr>
</table>


To define a custom banner size, set your desired `AdSize`, as shown here:


## ???? Flutter Tutorial
All Flutter Tutorials plus additional Code and shorter posts can be found on the [Official AllTechSavvy website](https://www.alltechsavvy.com/). 

## ?????? Built with Amazing Tools
* [Flutter](https://flutter.dev/) - Beautiful native apps in record time.
* [Android Studio](https://developer.android.com/studio/index.html/) - Tools for building Awesome apps on every type of Android device.
* [Visual Studio Code](https://code.visualstudio.com/) - Code editing. Redefined.


### :heart: Found this project useful?

If you found this project useful, then please consider giving it a :star: on Github and follow me on GitHub.


## ???? Bugs/Requests #
If you encounter any problems feel free to open an issue. If you feel the library is missing a feature, please raise a ticket on Github and I'll look into it. Pull request are also welcome.


## ???? Social Media Links


[<img align="center" alt="sagarshende | Twitter" width="40" src="https://image.flaticon.com/icons/svg/174/174876.svg" />](https://twitter.com/intent/follow?original_referer=https%3A%2F%2Fgithub.com%2Fsagarshende95&screen_name=SagarShende95)&ensp;Twitter: [@sagarshende95](https://twitter.com/intent/follow?original_referer=https%3A%2F%2Fgithub.com%2Fsagarshende95&screen_name=SagarShende95)

[<img align="center" alt="sagarshende | LinkedIn" width="40" src="https://image.flaticon.com/icons/svg/174/174857.svg" />](https://linkedin.com/in/sagarshende "Linkedin Sagar Shende")&ensp;Linkedin: [@SagarShende](https://linkedin.com/in/sagarshende "Linkedin Sagar Shende")

[<img align="center" alt="SagarShende | Medium" width="40" src="https://image.flaticon.com/icons/svg/174/174858.svg" />](https://medium.com/@SagarShende "Medium Sagar Shende")&ensp;Medium: [@SagarShende](https://medium.com/@SagarShende "Medium Sagar Shende")

[<img align="center" alt="AllTechSavvy | Medium" width="50" src="https://image.flaticon.com/icons/svg/733/733590.svg" />](https://www.youtube.com/alltechsavvy "YouTube AllTechSavvy")&ensp;YouTube:  [@AllTechSavvy](https://www.youtube.com/alltechsavvy "AllTechSavvy AllTechSavvy")

[<img align="center" alt="SagarShende | Medium" width="40" src="https://image.flaticon.com/icons/svg/1409/1409946.svg" />](https://www.instagram.com/sagarshende95 "Instagram Sagar Shende")&ensp;Instagram: [@SagarShende](https://www.instagram.com/sagarshende95/ "Medium Sagar Shende")



## ???? Donation

<img width="400" alt="inceptive-donate_artboard_2_2x_2x" src="https://user-images.githubusercontent.com/43273993/64881998-ca9a2f80-d679-11e9-98ec-e4f0d5470dbd.png">

**Paypal**

> If you found this project helpful or you learned something from the source code and want to thank me, consider buying me a cup of :coffee:
>
> - [PayPal](https://www.paypal.me/alltechsavvy/)

<p align="center">
   
[<img src="https://i.imgur.com/1Xiu9b4.png" />](https://www.paypal.me/alltechsavvy/)

</p>

**For All Developers**
* **[Donate $5](https://www.paypal.me/alltechsavvy/USD5)**: Thank's for creating this project, here's a coffee or juice or beer for you!
* **[Donate $10](https://www.paypal.me/alltechsavvy/USD10)**: Wow, I am stunned. Let me take you to the movies.
* **[Donate $15](https://www.paypal.me/alltechsavvy/USD15)**: I really appreciate your work, let's grab some lunch!
* **[Donate $20](https://www.paypal.me/alltechsavvy/USD20)**: That's some awesome stuff you did right there, Pizza/Burger is on me!


If you like my project, "Star" in the corresponding project right corner, please. Your support is my biggest encouragement! ^^ You can also scan the qr code below or Donate to this project, donation to Author.

<img src="https://github.com/sagarshende23/Simple_calculator_flutter/blob/master/Donation%20Page.jpg">


