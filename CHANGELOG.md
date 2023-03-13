## 3.0.0

* Add supported networks parameter for Apple Pay request (thank you to [dessonchan](https://github.com/dessonchan)!)
* Upgrade Braintree package versions (thank you to [dessonchan](https://github.com/dessonchan)!)
* Fix problems with Facebook login (thank you to [nicolobozzato](https://github.com/nicolobozzato)!)

## 3.0.0-dev.1

* Add support for specifying payment intent and user action in `BraintreePayPalRequest` (thank you to [nabinadhikari](https://github.com/nabinadhikari)!)
* Clean up naming conventions and documentation

## 2.3.1

* Update iOS dependencies (thank you to [jorgefspereira](https://github.com/jorgefspereira)!)

## 2.3.0

* Add option to disable PayPal in the Drop-In UI (thank you to [santhoshvgts](https://github.com/santhoshvgts)!)

## 2.2.1

* Switch to mavenCentral for Android builds (thank you to [asmengistu](https://github.com/asmengistu)!)
* Fix README to account for code changes (thank you to [hrvojecukman](https://github.com/hrvojecukman)!)

## 2.2.0

* Add PayPal Payer ID to result object (thank you to [nabinadhikari](https://github.com/nabinadhikari)!)

## 2.1.0
* Fix PayPal vault flow not working on iOS (thank you to [andrea689](https://github.com/andrea689)!)
* Add support for Apple Pay's `PKPaymentSummaryItem` (thank you to [bkovac](https://github.com/bkovac)!)

## 2.0.0+1

* Fix new build issue on iOS (thank you to [JideGuru](https://github.com/JideGuru)!)

## 2.0.0

* Upgrade several dependencies to fix build issues on Android and iOS (thank you to [bennibau](https://github.com/bennibau), [reverie-ss](https://github.com/reverie-ss), and [andesappal](https://github.com/andesappal)!)

## 2.0.0-nullsafety.0

* Add null-safety support

## 1.2.1

* Fix Android build (hopefully)

## 1.2.0

* Add option for CreditCard CVV number (thank you to [ilicmilan](https://github.com/ilicmilan)!)

## 1.1.0+1

* Fix vulnerability in Braintree plugin (Play Store issue)

## 1.1.0

* Add ApplePay support for the drop-in UI (thank you again to HareshGediya!)

## 1.0.3

* Fix `cardEnabled = false` not working on iOS drop-in (thank you to HareshGediya)

## 1.0.2+2

* Hotfix 3D Secure (thank you to enzobonggio!)
* Hotfix compilation issues

## 1.0.2+1

* Hotfix Braintree versions

## 1.0.2

* Add Podfile change to installation section

## 1.0.1

* Update outdated iOS Braintree dependency

## 1.0.0

* Support custom UI on iOS (thank you to WipeAir)

## 0.6.0

* Make card.io optional on Android to potentially reduce app sizes

## 0.5.3+3

* Fix disabling card not working for drop-in UI

## 0.5.3+2

* Fix incompatibilities with Google and Facebook sign in plugins

## 0.5.3+1

* Temporarily fix crashes (thank you to peternagy1332)

## 0.5.3

* Fix incompatibility with Flutter's new v2 embedding
* Update example project to use v2 embedding
* Use new platforms key in `pubspec.yaml` (requires Flutter 1.10 or newer!)

## 0.5.2

* Fix credit card expiration not being included correctly

## 0.5.1

* Improve README.md

## 0.5.0

* Add basic support for the direct PayPal Checkout and Vault flow Android

## 0.4.0

* Add basic support for direct credit card tokenization on Android

## 0.3.0

* Add iOS support (thank you to Johannes Erschbamer!)
* Improve documentation

## 0.2.0

* Refactor source code
* Set minimum Dart version to 2.2.2

## 0.1.2

* Fix typo in README.md

## 0.1.1

* Throw proper exception when the Drop-in is launched twice
* Improve README.md

## 0.1.0

* Initial release after discontinuing the old plugin
