# Android Demo - Splash screen

[![Build Status](https://travis-ci.org/kaderud/android-demo-splashscreen.svg?branch=master)](https://travis-ci.org/kaderud/android-demo-splashscreen)

Small sample of a Material design Splash screen


This example tries to implement the Material design Launch/Splash screen. It cheats a little by not having all the drawables for various sizes, it only implements xxxhdpi, but it should provide a basic app on how to display a splash screen in a theme during cold start loading.

To simulate a heavy workload during launch, it simply cheats by doing a Thread.sleep()-call.

Tested and working on:

 * Nexus 6 (Marshmallow 6.0)
 * Nexus S (Jelly Bean 4.1.2)
 * Samsung Galaxy S4+ (Lollipop 5.0.1)

## Links

 * [Google Material design](https://www.google.com/design/spec/patterns/launch-screens.html)
 * [Use cold start time effectively with a branded launch theme](https://plus.google.com/+AndroidDevelopers/posts/Z1Wwainpjhd?linkId=17769888)

## Screenshot

![](https://github.com/kaderud/android-demo-splashscreen/blob/master/splashscreen.gif)
