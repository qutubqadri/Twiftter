Twiftter 1.0
========

Twiftter is a feature-rich Twitter app for smartphones, powered by Java. It has a simple & easy-to-use UI that will surely make you enjoy the Twitter experience on your smartphone.
This Twitter app is designed to provide convenience to the life of the people who are always on the move and tweeting.

The library is based on the "Cling" view found in the Launcher on Ice-Cream Sandwich and Jelly Bean, but extended to be easier to use.

Please check out the website for more information.

Set-up
========

For people who use Maven, Twiftter should work immediately without any issues. If you aren't, you'll need to download the NineOldAndroids library and add it as a dependency library to the ShowcaseView library. Then add ShowcaseView as a library dependency to your project, and you're done!

WARNING: Sometimes Eclipse/IDE will automatically import the non-NineOldAndroid versions of the animation classes, which will cause crashes on versions of Android below 3.0. Check that your imports start with com.nineoldandroids.animation and not android.animation.

Usage
========

v1 brings the ability to showcase items on the ActionBar. Currently built-in on the Twiftter app are:

Android 3.0 (Honeycomb) and later

All native Android navgation buttons
Authorise the app through the official twitter website; 100% secure
Large Buttons for Tweet, ReTweet and Reply
Fast and Fluid interface
Any ActionItem - requires only the item's ID

Styles are included to maintain consistency. Buttons should use the style ClingButton, with title text using ClingTitleText and standard text using ClingText.

Upcoming features
========

1. Improved styling ability
2. Photo Upload abality
3. Direct Messaging
4. Profile view of personal tweets
5. Add searching capability of different users with there twitter handles

Copyright and Licensing
========
Copyright Syed & Ikramuddin © 2012. All rights reserved.
This library is disributed under an Apache 2.0 License.
