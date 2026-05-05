# Changelog

## 1.0.1+3
- update to ios 13.0+ and fix swift package manager support for iOS

## 1.0.0+1

Initial release of `facebook_flutter_sdk`, a fork of [facebook_app_events](https://pub.dev/packages/facebook_app_events).

### Features

- Log standard and custom app events
- Log purchase events with event deduplication (`eventId` parameter)
- Track app activations
- Set and clear user data and user ID
- Fetch deferred app links for ad attribution
- AEM (Aggregated Event Measurement) support for iOS 14.5+
- Advertiser tracking and ID collection control
- Data processing options (CCPA / limited data use)
- Push notification open tracking
- Debug mode for event logging
- Convenience methods for common events: `logSubscribe`, `logStartTrial`, `logAdImpression`, `logAdClick`, `logAddToCart`, `logAddToWishlist`, `logViewContent`, `logInitiatedCheckout`, `logCompletedRegistration`, `logRated`
- Swift Package Manager and CocoaPods support for iOS
- Facebook SDK 18.x (Android & iOS)
