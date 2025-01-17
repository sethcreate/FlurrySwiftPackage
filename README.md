# Flurry SDK - Swift Package beta 

## Table of Contents

- [Installation](#installation)

## Installation

#### Note: The Flurry Swift Package requires XCode 12 or higher and Swift 5.3 or higher

To add Flurry to your app with Swift Package Manager start in XCode with:

1. File -> Swift Packages -> Add Package Dependency 

OR

1. On the Build Phases screen -> Choose "Link Binary With Libraries" -> Click "+" -> Choose "Add Other" -> Choose "Add Package Dependency"

<img src="SupportingFiles/packageDependency.png" height="700"/>

2. Enter the following repo in the url section: **https://github.com/flurry/FlurrySwiftPackage/**

<img src="SupportingFiles/packageRepository.png"/>

3. Click "Add Package" and the following page should appear:

<img src="SupportingFiles/swiftPackages.png" height="500"/>

5. Choose the Packages needed for your project. 

  *Note: Flurry Analytics is required to use FlurryConfig and FlurryMessaging.

6. The Flurry Analytics Swift Package requires the System Configuration framework (SystemConfiguration.framework).

  a. On the Build Phases page, under "Link Binary With Libraries", click on "+" and add "SystemConfiguration.framework"

7. If you are using Objective C proceed with the integration instructions [here](https://developer.yahoo.com/flurry/docs/integrateflurry/ios/#initialize-flurry):

[https://developer.yahoo.com/flurry/docs/integrateflurry/ios/#initialize-flurry](https://developer.yahoo.com/flurry/docs/integrateflurry/ios/#initialize-flurry)

8. If you are using Swift you will need to add the Flurry header files in a bridging header file. Detailed instructions for this are found [here](https://developer.yahoo.com/flurry/docs/integrateflurry/ios-manual/#swift-sdk-integration):

[https://developer.yahoo.com/flurry/docs/integrateflurry/ios-manual/#swift-sdk-integration](https://developer.yahoo.com/flurry/docs/integrateflurry/ios-manual/#swift-sdk-integration)
