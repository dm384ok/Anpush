## Anpush Integration
Anpush combines all the tools for analytics and tracking tool in one solution.
Allows you to manage, set up detailed statistics and push marketing using one convenient source of truth.
If you want to use our tool in your project, please contact us and we will provide you with the api key.

### Unity version requirements:
In case when your application is unity based - you ALWAYS need use LATEST stable version of unity for ios project export, 2022.3.14f1 as MINIMUM.

## Dependency 
Add SDK swift package dependencies to project: [https://github.com/dm384ok/Anpush6.5.git](https://github.com/dm384ok/Anpush6.5.git)

## Info.plist setup
After dependency is continue processing, go to INFO tab, and setup some necessary fields:

> NSAdvertisingAttributionReportEndpoint : https://appsflyer-skadnetwork.com/

> ITSAppUsesNonExemptEncryption  :  NO

> NSUserTrackingUsageDescription : Select "Allow" for better experience. This identifier will be used to  order to functionalities and user engagement.

> NSLocationWhenInUseUsageDescription : Select "Allow" for better experience. Your location will be used to order to user engagement.

> NSCameraUsageDescription : Select "Allow" for better experience. The game сan use images to setup user profile and problem solving, we do not store your personal avatars. 

> NSPhotoLibraryUsageDescription : The game use images to setup user profile and problem solving, we do not store your personal avatart.

#### Next step is enable **Push Notification** on Capability editor:

![enter image description here](https://i.imgur.com/bg1UMSz.png)

#### Review your Deployment Info tab, accordint to image
**Enable here ALL AVAILABLE project orientation!** 
This is Extremely important for the operation of advertising blocks!

![enter image description here](https://i.imgur.com/g1HDkvC.png)

### SDK Configuration
SDK init by configuration file, so you need ask your manager about it: **GoogleService-Info.plist**, and add this file to your main TARGET without any changes:

![Imgur](https://i.imgur.com/Jvh88dC.png)

## Finish

*Target project is ready , Build test and publish project in original way.*





