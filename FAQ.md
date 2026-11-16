# Frequently asked questions

## Is the app only for the Samsung S22 Ultra?

No. The S22 Ultra is the initial test device, not a Samsung-only restriction. The inspected version 0.6.9 APK requires Android 7.0 or newer and a 64-bit ARM Android system (`arm64-v8a`). Other compatible Android phones can run the same build. A 64-bit processor alone is not enough if the phone runs a 32-bit Android system.

## Can I install this APK on an iPhone?

No. This installer is for Android. An iOS app would require a separate build and distribution process.

## What should testers check on other phones?

Check smaller screens, larger font settings, gesture and three-button navigation, keyboard and Save-button visibility, barcode camera access, offline logging, saved records after restarting, light and dark themes, and the intro animation. Report the phone model, Android version, app version, reproduction steps, and a screenshot with personal information removed.

Support for multiple screen sizes is declared in the APK; actual layout quality and performance across devices still need verification.

## Does the app work offline?

Core tracking uses locally stored records and available food data. External food and unfamiliar-barcode lookups can require internet access.

## Do the website and Android app automatically share my records?

No. They use separate local storage. Only use a supported export/import process to transfer records; do not assume automatic cloud synchronization.

## Will I need to create a profile every time?

No. A saved profile should persist between launches. Clearing app data, uninstalling, or using a separate installation can require setup again.

## What are performance tiers?

They summarize supported performance results using the applicable reference standards and profile inputs. Not every exercise or demographic has reference coverage. They are not medical assessments or guarantees of ability.

## Why does a scanned barcode sometimes have no result?

A barcode identifies a product; nutritional information must also exist in the food database or an available lookup service. Verify the product, serving size, and label before saving.

## Can I choose grams, ounces, or servings?

Use the units and serving options available for that food. Household servings require a known quantity conversion; they should not be inferred when data is missing.

## How are weight goals related to nutrition?

Weight goals and available profile information support estimated calorie targets. Estimates are not guarantees of weight change. Review the app's goal-rate notices and update your profile when relevant information changes.

## How do I get help or report a bug?

Use the info icon for help on the current screen. For a software issue, provide your app version, phone model, Android version, reproduction steps, and the error shown. Avoid posting private health records or backup files.

## Are downloads available yet?

Check the Releases section. If no APK release is listed, the public download has not been published yet.
