# AdColony Android SDK
* Modified: November 7th, 2018
* SDK Version: 3.3.6

## Overview
AdColony delivers zero-buffering, [full-screen Instant-Play™ HD video](https://www.adcolony.com/technology/instant-play/), [interactive Aurora™ Video](https://www.adcolony.com/technology/auroravideo/), and Aurora™ Playable ads that can be displayed anywhere within your application. Our advertising SDK is trusted by the world’s top gaming and non-gaming publishers, delivering them the highest monetization opportunities from brand and performance advertisers. AdColony’s SDK can monetize a wide range of ad formats including in-stream/pre-roll, out-stream/interstitial and V4VC™, a secure system for rewarding users of your app with virtual currency upon the completion of video and playable ads.


## Release Notes

#### 3.3.6
* Added additional configure() signatures that accept an Application context instead of Activity.
* Deprecated AdColonyAdViewActivity, AdColonyNativeAdView, and onAudioStarted/onAudioStopped() callbacks.
* Handle API level 28 changes for [default cleartext traffic behavior](https://developer.android.com/about/versions/pie/android-9.0-changes-28#framework-security-changes).
* Several bug fixes and stability improvements.

Here is the link to the [release notes](https://github.com/AdColony/AdColony-Android-SDK-3/blob/master/CHANGELOG.md) for all the previous SDK versions and please check out the 3.3 SDK [integration tips](https://www.adcolony.com/blog/2018/02/22/reaching-new-heights-sdk-3-3/).

## Getting Started 
To get started, here is the link to [Android SDK integration documentation](https://github.com/AdColony/AdColony-Android-SDK-3/wiki).

## Upgrade 
#### SDK 2.x:

Please note that updating from our 2.x SDK is not a drag and drop update, but rather includes breaking API and process changes. In order to take advantage of the 3.x SDK, a complete re-integration is necessary. Please review our [documentation](https://github.com/AdColony/AdColony-Android-SDK-3/wiki) to get a better idea on what changes will be necessary in your app.

#### SDK 3.x:
Update the AdColony library referenced by your project following the steps below:

**Manual**

* Drag and drop the adcolony.jar into your project.
* Drag and drop the native libraries your application supports into your project.

**Via Gradle**

Assuming our maven repo is added to your project (see our [project setup guide](https://github.com/AdColony/AdColony-Android-SDK-3/wiki/Project-Setup)), update your 'dependencies' configuration within your module's build.gradle to point to the latest version:

```
dependencies {
  /** 
   * Any other dependencies your module has are placed in this dependency configuration
   */
  implementation 'com.adcolony:sdk:3.3.6'
}
```

## Legal Requirements
By downloading the AdColony SDK, you are granted a limited, non-commercial license to use and review the SDK solely for evaluation purposes.  If you wish to integrate the SDK into any commercial applications, you must register an account with AdColony and accept the terms and conditions on the AdColony website.

Note that U.S. based companies will need to complete the W-9 form and send it to us before publisher payments can be issued.

## Contact Us
For more information, please visit AdColony.com. For questions or assistance, please email us at support@adcolony.com.
