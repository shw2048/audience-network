AdUnitsSample
=============

In this sample we demonstrate how to use ad formats such as banner, medium rect, intersttial, rewarded video, in-stream video as well as the Native Ad API (FBNativeAd) from the Facebook Ads SDK for iOS. FBNativeAd gives the flexibility to the to allow developer to render the ad in a more native format that blends into their app. We also show how to wire up the delegate to get notified when the ad status changes over time or when the user interacts with the ad.

When running the sample on the simulator, test ads are served by default. On a device however, real ads will be served unless you specify otherwise. If you test your app on a device, please make sure to call the following API to enable test ads: [FBAdSettings addTestDevice:@"<your device hash printed out on console>"]. You can also toggle the test mode requests from the Settings menu.

How to use the sample
---------------------

1. Launch the AdUnitsSample project using Xcode from the <Facebook SDK>/samples/AdUnitsSample directory.
2. Open the file ViewController.m and replace "YOUR_PLACEMENT_ID" with the Placement ID you created through developer.facebook.com.
3. Run the sample on the simulator or on a device.
