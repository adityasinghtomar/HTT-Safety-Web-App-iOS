##Project Tree:
```
├───.github
│   └───workflows
├───FBAudienceNetwork.framework
│   ├───Headers
│   └───Modules
├───OneSignal.framework
│   └───Versions
│       └───A
│           ├───Headers
│           ├───Modules
│           └───Resources
├───OneSignalNotificationServiceExtension
├───Pods
│   ├───FBAudienceNetwork
│   │   └───Static
│   │       └───FBAudienceNetwork.xcframework
│   │           ├───ios-arm64
│   │           │   └───FBAudienceNetwork.framework
│   │           │       ├───Headers
│   │           │       ├───Modules
│   │           │       └───_CodeSignature
│   │           ├───ios-arm64_x86_64-simulator
│   │           │   └───FBAudienceNetwork.framework
│   │           │       ├───Headers
│   │           │       ├───Modules
│   │           │       └───_CodeSignature
│   │           └───_CodeSignature
│   ├───Firebase
│   │   └───CoreOnly
│   │       └───Sources
│   ├───FirebaseAnalytics
│   │   └───Frameworks
│   │       └───FirebaseAnalytics.xcframework
│   │           ├───ios-arm64
│   │           │   └───FirebaseAnalytics.framework
│   │           │       ├───Headers
│   │           │       └───Modules
│   │           │           └───FirebaseAnalytics.swiftmodule
│   │           │               └───Project
│   │           ├───ios-arm64_x86_64-maccatalyst
│   │           │   └───FirebaseAnalytics.framework
│   │           │       ├───Headers
│   │           │       ├───Modules
│   │           │       │   └───FirebaseAnalytics.swiftmodule
│   │           │       │       └───Project
│   │           │       ├───Resources
│   │           │       └───Versions
│   │           │           └───A
│   │           │               ├───Headers
│   │           │               ├───Modules
│   │           │               │   └───FirebaseAnalytics.swiftmodule
│   │           │               │       └───Project
│   │           │               └───Resources
│   │           ├───ios-arm64_x86_64-simulator
│   │           │   └───FirebaseAnalytics.framework
│   │           │       ├───Headers
│   │           │       └───Modules
│   │           │           └───FirebaseAnalytics.swiftmodule
│   │           │               └───Project
│   │           ├───macos-arm64_x86_64
│   │           │   └───FirebaseAnalytics.framework
│   │           │       ├───Headers
│   │           │       ├───Modules
│   │           │       │   └───FirebaseAnalytics.swiftmodule
│   │           │       │       └───Project
│   │           │       ├───Resources
│   │           │       └───Versions
│   │           │           └───A
│   │           │               ├───Headers
│   │           │               ├───Modules
│   │           │               │   └───FirebaseAnalytics.swiftmodule
│   │           │               │       └───Project
│   │           │               └───Resources
│   │           ├───tvos-arm64
│   │           │   └───FirebaseAnalytics.framework
│   │           │       ├───Headers
│   │           │       └───Modules
│   │           │           └───FirebaseAnalytics.swiftmodule
│   │           │               └───Project
│   │           ├───tvos-arm64_x86_64-simulator
│   │           │   └───FirebaseAnalytics.framework
│   │           │       ├───Headers
│   │           │       └───Modules
│   │           │           └───FirebaseAnalytics.swiftmodule
│   │           │               └───Project
│   │           └───_CodeSignature
│   ├───FirebaseCore
│   │   └───FirebaseCore
│   │       ├───Extension
│   │       └───Sources
│   │           ├───Public
│   │           │   └───FirebaseCore
│   │           └───Resources
│   ├───FirebaseCoreInternal
│   │   └───FirebaseCore
│   │       └───Internal
│   │           └───Sources
│   │               ├───HeartbeatLogging
│   │               └───Resources
│   ├───FirebaseInstallations
│   │   ├───FirebaseCore
│   │   │   └───Extension
│   │   └───FirebaseInstallations
│   │       └───Source
│   │           └───Library
│   │               ├───Errors
│   │               ├───IIDMigration
│   │               ├───InstallationsAPI
│   │               ├───InstallationsIDController
│   │               ├───InstallationsStore
│   │               ├───Private
│   │               ├───Public
│   │               │   └───FirebaseInstallations
│   │               └───Resources
│   ├───FirebaseMessaging
│   │   ├───FirebaseCore
│   │   │   └───Extension
│   │   ├───FirebaseInstallations
│   │   │   └───Source
│   │   │       └───Library
│   │   │           └───Private
│   │   ├───FirebaseMessaging
│   │   │   ├───Interop
│   │   │   └───Sources
│   │   │       ├───Protogen
│   │   │       │   └───nanopb
│   │   │       ├───Public
│   │   │       │   └───FirebaseMessaging
│   │   │       ├───Resources
│   │   │       └───Token
│   │   └───Interop
│   │       └───Analytics
│   │           └───Public
│   ├───Google-Mobile-Ads-SDK
│   │   └───Frameworks
│   │       └───GoogleMobileAdsFramework
│   │           └───GoogleMobileAds.xcframework
│   │               ├───ios-arm64
│   │               │   └───GoogleMobileAds.framework
│   │               │       ├───Headers
│   │               │       │   ├───Mediation
│   │               │       │   ├───QueryInfo
│   │               │       │   └───RTBMediation
│   │               │       └───Modules
│   │               ├───ios-arm64_x86_64-simulator
│   │               │   └───GoogleMobileAds.framework
│   │               │       ├───Headers
│   │               │       │   ├───Mediation
│   │               │       │   ├───QueryInfo
│   │               │       │   └───RTBMediation
│   │               │       └───Modules
│   │               └───_CodeSignature
│   ├───GoogleAppMeasurement
│   │   └───Frameworks
│   │       ├───GoogleAppMeasurement.xcframework
│   │       │   ├───ios-arm64
│   │       │   │   └───GoogleAppMeasurement.framework
│   │       │   │       └───Modules
│   │       │   ├───ios-arm64_x86_64-maccatalyst
│   │       │   │   └───GoogleAppMeasurement.framework
│   │       │   │       └───Versions
│   │       │   │           └───A
│   │       │   │               ├───Modules
│   │       │   │               └───Resources
│   │       │   ├───ios-arm64_x86_64-simulator
│   │       │   │   └───GoogleAppMeasurement.framework
│   │       │   │       └───Modules
│   │       │   ├───macos-arm64_x86_64
│   │       │   │   └───GoogleAppMeasurement.framework
│   │       │   │       └───Versions
│   │       │   │           └───A
│   │       │   │               ├───Modules
│   │       │   │               └───Resources
│   │       │   ├───tvos-arm64
│   │       │   │   └───GoogleAppMeasurement.framework
│   │       │   │       └───Modules
│   │       │   ├───tvos-arm64_x86_64-simulator
│   │       │   │   └───GoogleAppMeasurement.framework
│   │       │   │       └───Modules
│   │       │   └───_CodeSignature
│   │       └───GoogleAppMeasurementIdentitySupport.xcframework
│   │           ├───ios-arm64
│   │           │   └───GoogleAppMeasurementIdentitySupport.framework
│   │           │       └───Modules
│   │           ├───ios-arm64_x86_64-maccatalyst
│   │           │   └───GoogleAppMeasurementIdentitySupport.framework
│   │           │       └───Versions
│   │           │           └───A
│   │           │               ├───Modules
│   │           │               └───Resources
│   │           ├───ios-arm64_x86_64-simulator
│   │           │   └───GoogleAppMeasurementIdentitySupport.framework
│   │           │       └───Modules
│   │           ├───macos-arm64_x86_64
│   │           │   └───GoogleAppMeasurementIdentitySupport.framework
│   │           │       └───Versions
│   │           │           └───A
│   │           │               ├───Modules
│   │           │               └───Resources
│   │           ├───tvos-arm64
│   │           │   └───GoogleAppMeasurementIdentitySupport.framework
│   │           │       └───Modules
│   │           ├───tvos-arm64_x86_64-simulator
│   │           │   └───GoogleAppMeasurementIdentitySupport.framework
│   │           │       └───Modules
│   │           └───_CodeSignature
│   ├───GoogleDataTransport
│   │   └───GoogleDataTransport
│   │       ├───GDTCCTLibrary
│   │       │   ├───Private
│   │       │   ├───Protogen
│   │       │   │   └───nanopb
│   │       │   └───Public
│   │       ├───GDTCORLibrary
│   │       │   ├───Internal
│   │       │   ├───Private
│   │       │   └───Public
│   │       │       └───GoogleDataTransport
│   │       └───Resources
│   ├───GoogleUserMessagingPlatform
│   │   └───Frameworks
│   │       └───Release
│   │           └───UserMessagingPlatform.xcframework
│   │               ├───ios-arm64
│   │               │   └───UserMessagingPlatform.framework
│   │               │       ├───Headers
│   │               │       └───Modules
│   │               ├───ios-arm64_x86_64-simulator
│   │               │   └───UserMessagingPlatform.framework
│   │               │       ├───Headers
│   │               │       └───Modules
│   │               └───_CodeSignature
│   ├───GoogleUtilities
│   │   ├───GoogleUtilities
│   │   │   ├───AppDelegateSwizzler
│   │   │   │   ├───Internal
│   │   │   │   └───Public
│   │   │   │       └───GoogleUtilities
│   │   │   ├───Common
│   │   │   ├───Environment
│   │   │   │   ├───NetworkInfo
│   │   │   │   ├───Public
│   │   │   │   │   └───GoogleUtilities
│   │   │   │   ├───SecureStorage
│   │   │   │   └───URLSessionPromiseWrapper
│   │   │   ├───Logger
│   │   │   │   └───Public
│   │   │   │       └───GoogleUtilities
│   │   │   ├───MethodSwizzler
│   │   │   │   └───Public
│   │   │   │       └───GoogleUtilities
│   │   │   ├───Network
│   │   │   │   └───Public
│   │   │   │       └───GoogleUtilities
│   │   │   ├───NSData+zlib
│   │   │   │   └───Public
│   │   │   │       └───GoogleUtilities
│   │   │   ├───Privacy
│   │   │   │   └───Resources
│   │   │   ├───Reachability
│   │   │   │   └───Public
│   │   │   │       └───GoogleUtilities
│   │   │   └───UserDefaults
│   │   │       └───Public
│   │   │           └───GoogleUtilities
│   │   └───third_party
│   │       └───IsAppEncrypted
│   │           └───Public
│   ├───Headers
│   │   ├───Private
│   │   │   └───Firebase
│   │   └───Public
│   │       └───Firebase
│   ├───nanopb
│   │   └───spm_resources
│   ├───OneSignalXCFramework
│   │   └───iOS_SDK
│   │       └───OneSignalSDK
│   │           ├───OneSignal_Core
│   │           │   └───OneSignalCore.xcframework
│   │           │       ├───ios-arm64
│   │           │       │   └───OneSignalCore.framework
│   │           │       │       ├───Headers
│   │           │       │       ├───Modules
│   │           │       │       └───_CodeSignature
│   │           │       ├───ios-arm64_x86_64-maccatalyst
│   │           │       │   └───OneSignalCore.framework
│   │           │       │       └───Versions
│   │           │       │           └───A
│   │           │       │               ├───Headers
│   │           │       │               ├───Modules
│   │           │       │               ├───Resources
│   │           │       │               └───_CodeSignature
│   │           │       ├───ios-arm64_x86_64-simulator
│   │           │       │   └───OneSignalCore.framework
│   │           │       │       ├───Headers
│   │           │       │       ├───Modules
│   │           │       │       └───_CodeSignature
│   │           │       └───_CodeSignature
│   │           ├───OneSignal_Extension
│   │           │   └───OneSignalExtension.xcframework
│   │           │       ├───ios-arm64
│   │           │       │   └───OneSignalExtension.framework
│   │           │       │       ├───Headers
│   │           │       │       ├───Modules
│   │           │       │       └───_CodeSignature
│   │           │       ├───ios-arm64_x86_64-maccatalyst
│   │           │       │   └───OneSignalExtension.framework
│   │           │       │       └───Versions
│   │           │       │           └───A
│   │           │       │               ├───Headers
│   │           │       │               ├───Modules
│   │           │       │               ├───Resources
│   │           │       │               └───_CodeSignature
│   │           │       ├───ios-arm64_x86_64-simulator
│   │           │       │   └───OneSignalExtension.framework
│   │           │       │       ├───Headers
│   │           │       │       ├───Modules
│   │           │       │       └───_CodeSignature
│   │           │       └───_CodeSignature
│   │           ├───OneSignal_Outcomes
│   │           │   └───OneSignalOutcomes.xcframework
│   │           │       ├───ios-arm64
│   │           │       │   └───OneSignalOutcomes.framework
│   │           │       │       ├───Headers
│   │           │       │       ├───Modules
│   │           │       │       └───_CodeSignature
│   │           │       ├───ios-arm64_x86_64-maccatalyst
│   │           │       │   └───OneSignalOutcomes.framework
│   │           │       │       └───Versions
│   │           │       │           └───A
│   │           │       │               ├───Headers
│   │           │       │               ├───Modules
│   │           │       │               ├───Resources
│   │           │       │               └───_CodeSignature
│   │           │       ├───ios-arm64_x86_64-simulator
│   │           │       │   └───OneSignalOutcomes.framework
│   │           │       │       ├───Headers
│   │           │       │       ├───Modules
│   │           │       │       └───_CodeSignature
│   │           │       └───_CodeSignature
│   │           └───OneSignal_XCFramework
│   │               └───OneSignal.xcframework
│   │                   ├───ios-arm64
│   │                   │   └───OneSignal.framework
│   │                   │       ├───Headers
│   │                   │       └───Modules
│   │                   ├───ios-arm64_x86_64-maccatalyst
│   │                   │   └───OneSignal.framework
│   │                   │       └───Versions
│   │                   │           └───A
│   │                   │               ├───Headers
│   │                   │               ├───Modules
│   │                   │               └───Resources
│   │                   ├───ios-arm64_x86_64-simulator
│   │                   │   └───OneSignal.framework
│   │                   │       ├───Headers
│   │                   │       ├───Modules
│   │                   │       └───_CodeSignature
│   │                   └───_CodeSignature
│   ├───Pods.xcodeproj
│   │   └───xcuserdata
│   │       └───user291110.xcuserdatad
│   │           └───xcschemes
│   ├───PromisesObjC
│   │   └───Sources
│   │       └───FBLPromises
│   │           ├───include
│   │           └───Resources
│   ├───PushwooshXCFramework
│   │   └───XCFramework
│   │       └───Pushwoosh.xcframework
│   │           ├───ios-arm64
│   │           │   └───Pushwoosh.framework
│   │           │       ├───Headers
│   │           │       └───Modules
│   │           ├───ios-arm64_x86_64-maccatalyst
│   │           │   └───Pushwoosh.framework
│   │           │       └───Versions
│   │           │           └───A
│   │           │               ├───Headers
│   │           │               ├───Modules
│   │           │               └───Resources
│   │           └───ios-arm64_x86_64-simulator
│   │               └───Pushwoosh.framework
│   │                   ├───Headers
│   │                   ├───Modules
│   │                   └───_CodeSignature
│   ├───SwiftQRScanner
│   │   └───Classes
│   ├───SwiftyGif
│   │   └───SwiftyGif
│   ├───SwiftyStoreKit
│   │   └───Sources
│   │       └───SwiftyStoreKit
│   └───Target Support Files
│       ├───FBAudienceNetwork
│       ├───Firebase
│       ├───FirebaseAnalytics
│       ├───FirebaseCore
│       ├───FirebaseCoreInternal
│       ├───FirebaseInstallations
│       ├───FirebaseMessaging
│       ├───Google-Mobile-Ads-SDK
│       ├───GoogleAppMeasurement
│       ├───GoogleDataTransport
│       ├───GoogleUserMessagingPlatform
│       ├───GoogleUtilities
│       ├───nanopb
│       ├───OneSignalXCFramework
│       ├───Pods-OneSignalNotificationServiceExtension
│       ├───Pods-WebViewGold
│       ├───PromisesObjC
│       ├───PushwooshXCFramework
│       ├───SwiftQRScanner
│       ├───SwiftyGif
│       └───SwiftyStoreKit
├───WebView
│   ├───ApplicationIcon
│   │   └───AppIconAlternate
│   ├───Assets.xcassets
│   │   ├───AppIcon.appiconset
│   │   ├───camera.imageset
│   │   ├───cancel.imageset
│   │   ├───flash-off.imageset
│   │   ├───flash-on.imageset
│   │   ├───ic_back.imageset
│   │   ├───noinet.imageset
│   │   ├───purchase.imageset
│   │   └───Shareee.imageset
│   ├───Barcode Scanner
│   ├───Base.lproj
│   ├───Handler
│   ├───local-www
│   │   └───images
│   │       ├───example1
│   │       └───example2
│   └───SVProgressHUD
│       └───SVProgressHUD.bundle
├───WebViewGold.xcodeproj
│   ├───project.xcworkspace
│   │   └───xcshareddata
│   ├───xcshareddata
│   │   └───xcschemes
│   └───xcuserdata
│       └───user291110.xcuserdatad
│           └───xcschemes
└───WebViewGold.xcworkspace
    ├───xcshareddata
    │   └───swiftpm
    │       └───configuration
    └───xcuserdata
        └───user291110.xcuserdatad
```