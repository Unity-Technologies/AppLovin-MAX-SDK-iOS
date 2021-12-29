# Changelog

## 8.13.0.3
* Properly destroy native ad.

## 8.13.0.2
* Add support for native custom ads and updated native template ad support.

## 8.13.0.1
* Fix signal collection to include query info type.
* Update request agent to "applovin".

## 8.13.0.0
* Certified with Google SDK 8.13.0.

## 8.12.0.1
* Add query info type for bidding ad requests.
* Fix adapter deprecation warnings.

## 8.12.0.0
* Certified with Google SDK 8.12.0.

## 8.11.0.1
* Add `adDidRecordClick` callback for fullscreen ads.

## 8.11.0.0
* Certified with Google SDK 8.11.0.

## 8.10.0.1
* Initial support for true native ads.

## 8.10.0.0
* Certified with Google SDK 8.10.0.

## 8.9.0.0
* Certified with Google SDK 8.9.0.

## 8.8.0.2
* Add `placement_req_id` to network extras for all ad requests.

## 8.8.0.1
* Add support for rewarded interstitial ads.

## 8.8.0.0
* Certified with Google SDK 8.8.0.

## 8.7.0.0
* Certified with Google SDK 8.7.0.

## 8.6.0.1
* Update bidding APIs.

## 8.6.0.0
* Certified with Google SDK 8.6.0.

## 8.5.0.0
* Certified with Google SDK 8.5.0.

## 8.4.0.1
* Remove expired bids after set amount of time.

## 8.4.0.0
* Certified with Google SDK 8.4.0.
* Update podspec to use `pod_target_xcconfig` over the deprecated `xcconfig`.

## 8.3.0.0
* Certified with Google SDK 8.3.0.

## 8.2.0.1
* Certified with Google SDK 8.2.0.1.
* NOTE: This adapter version is the same as the SDK pod version, because Google released a one-off update with four version numbers.

## 8.2.0.0
* Certified with Google SDK 8.2.0.

## 8.1.0.1
* Add support for bidding.

## 8.1.0.0
* Certified with Google SDK 8.1.0.

## 8.0.0.0
* Certified with Google SDK 8.0.0.
* Remove click tracking for interstitial ads.
* Update podspec source from bintray to S3.

## 7.69.0.2
* Add support for creative id for banner native.

## 7.69.0.1
* Add support for passing creative ID to MAX SDK (supported in iOS SDK 6.15.0+).
* Add support to pass 3rd-party error code and description to SDK.

## 7.69.0.0
* Certified with Google SDK 7.69.0. This version of AdMob is only compatible with Firebase 7.0.0+.

## 7.67.1.5
* Add support for `adViewDidRecordImpression` callback.

## 7.67.1.4
* Add support for adaptive banners.

## 7.67.1.3
* Only set user consent flag if GDPR applies.

## 7.67.1.2
* Update native banners to use custom templates passed down from backend instead of hardcoding templates.

## 7.67.1.1
* Downgrade to Google SDK 7.66.0. This is due to 7.67.x not being compatible with latest release of Firebase 7.0.0 (which has not been released on Unity as well).

## 7.67.1.0
* Certified with Google SDK 7.67.1.

## 7.66.0.3
* Add checks for required native ad assets (headline, body, images, icon and CTA).

## 7.66.0.2
* Add support for vertical template native banners.

## 7.66.0.1
* Add support for disabling mediation 

## 7.66.0.0
* Certified with Google SDK 7.66.0.

## 7.65.0.0
* Certified with Google SDK 7.65.0.
* Removed the i386 slice. Adapter will no longer work on 32-bit simulators.
* Update 7000000 version check to 6140000.

## 7.64.0.2
* Update 70000 version check to 7000000.

## 7.64.0.1
* Re-enable logic in adapter `destroy` method.
* Update 61400 version check to 70000.

## 7.64.0.0
* Certified with Google SDK 7.64.0.
* Update deprecated Google SDK version retrieval.

## 7.63.0.0
* Certified with Google SDK 7.63.0.

## 7.62.0.4
* Fix native ad view ad visibility issue.

## 7.62.0.3
* Updated to not set privacy settings if nil.

## 7.62.0.2
* Roll back privacy changes.

## 7.62.0.1
* Updated to not set privacy settings if nil.

## 7.62.0.0
* Certified with Google SDK 7.62.0.

## 7.61.0.1
* Add support for native ad views.

## 7.61.0.0
* Certified with Google SDK 7.61.0.

## 7.60.0.0
* Certified with Google SDK 7.60.0.

## 7.59.0.0
* Certified with AdMob SDK 7.59.0.
* Use the initialization state passed down by Google. 

## 7.58.0.0
* Certified with AdMob SDK 7.58.0.

## 7.57.0.1
* Fix bug where mute state was not being applied.

## 7.57.0.0
* Certified with AdMob SDK 7.57.0.
* Updated to use GADRewardedAd.

## 7.55.1.0
* Certified with AdMob SDK 7.55.1.
* Fix CCPA support - requires AppLovin SDK 6.11.0 to compile.

## 7.55.0.0
* Certified with AdMob SDK 7.55.0.

## 7.54.0.0
* Certified with AdMob SDK 7.54.0.

## 7.53.1.1
* Updated deprecated API usages.

## 7.53.1.0
* Certified with AdMob SDK 7.53.1.

## 7.51.0.2
* Add support for CCPA.

## 7.51.0.1
* Fix Xcode warning logs due to retrieving SDK version from background thread. 

## 7.51.0.0
* Updated the minimum required AppLovin SDK version to 6.5.0.
* Add support for mute configuration.
* Certified with AdMob SDK 7.51.0.

## 7.44.0.1
* Add support for initialization status.

## 7.44.0.0
* Certified with AdMob SDK 7.44.0.
* Adapter sets the `tagForChildDirectedTreatment` status on AdMob SDK before initializing it.
* Please make sure to have your Google Application ID declared in your app's `Info.plist`. For more information, please refer to our [documentation](https://dash.applovin.com/documentation/mediation/ios/mediation-adapters)
* Add Unity support for automatic dependency resolution. Please ensure that you are on the latest [AppLovin MAX Unity Plugin](https://bintray.com/applovin/Unity/applovin-max-unity-plugin).
* Add support for extra reward options.

## 7.40.0.2
* Minor adapter improvements.

## 7.40.0.1
* Minor improvements.

## 7.40.0.0
* Certified with AdMob SDK 7.40.0.

## 7.36.0.0
* Initial commit.