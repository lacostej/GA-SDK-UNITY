# GA-SDK-UNITY
GameAnalytics Unity SDK.

Documentation is in the [wiki](https://github.com/GameAnalytics/GA-SDK-UNITY/wiki).


> :information_source:<br>
> The new Unity SDK only includes support for iOS and Android.<br>
> The prior V1 Unity SDK is still functional and available [here](http://download.gameanalytics.com/unity/UnityWrapper.unitypackage).<br>
> Read this [SDK update FAQ](http://www.gameanalytics.com/docs/sdk-update-faq/) to keep yourself informed about future V2 SDK updates.



Changelog
---------

**2.1.0**
* Android support added
* Google Play purchase validation
* support for individual game keys for each supported platform

**2.0.4**
* fixed an issue with going-to-background on iOS 6
* fixed submit of birthyear value

**2.0.3**
* fixed an iOS 6 issue
* added a post process build script for setting up Xcode (Unity 5 only)

**2.0.2**
* fix for PlayMaker events
* fix for Critical FPS events

**2.0.1**
* fix for business event receipt rejection in some cases
* tweaked local db size trimming

**2.0.0**
* redesigned Unity SDK 
* initially with **only iOS** support
* progression event
* business event validation
* resource event
* custom dimensions
