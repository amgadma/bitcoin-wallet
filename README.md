Welcome to _Zcash Android Wallet_, a standalone Zcash payment app for your Android device!

This project is based on a fork of https://github.com/bitcoin-wallet/bitcoin-wallet, it 

This software is in POC phase

Original project contains several sub-projects:

 * __wallet__:
     The Android app itself. This is probably what you're searching for.
 * __native-scrypt__:
     Native code implementation for Scrypt. The C files are copied from the
     Java Scrypt project at [GitHub](https://github.com/wg/scrypt).
 * __market__:
     App description and promo material for the Google Play app store.
 * __integration-android__:
     A tiny library for integrating Zcash payments into your own Android app
     (e.g. donations, in-app purchases).
 * __sample-integration-android__:
     A minimal example app to demonstrate integration of Zcash payments into
     your Android app.

You can build all sub-projects at once using Gradle:

`gradle clean build`
