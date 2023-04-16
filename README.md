
**Please note that this example applies to the deprecated V1 moltin API only. For the most up to date iOS example, please go to https://github.com/moltin/ios-sdk/tree/v2/Example**

# Moltin Objective-C iOS Example app
An example app that thoroughly demonstrates how to use the Moltin iOS eCommerce SDK in Objective-C, along with Apple Pay.

*Prefer Swift? [Check out our Swift example app instead](https://github.com/moltin/ios-swift-example)*

# Getting started
This demo app uses [CocoaPods](https://guides.cocoapods.org/using/getting-started.html#getting-started) to manage dependencies. 
- Clone the project repository
- Run `pod install` in the `MoltinSDK iOS Example` directory
- Open the .xcworkspace file
- You're all set.

### Using Apple Pay
To use Apple Pay in the example app, you must have: 
 - A Stripe account.
 - A Moltin store set up with the Stripe payment gateway enabled and associated with your Stripe account.
 - A paid Apple Developer account.

Once you have that sorted, you can follow these steps:

 - Change the app's bundle ID from com.moltin.Moltin to something unique.
 - [Follow this guide](https://stripe.com/docs/mobile/apple-pay) to register your Merchant ID, create a certificate with Stripe and upload it to Apple.
 - Change the value of the StripePublishableKey constant in CartViewController.m to your Stripe account's publishable API key.

Then you're all set to use Apple Pay at the checkout in the demo app!
