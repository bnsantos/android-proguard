# android-proguard
Android proguard example

Initial project 
No minify and proguard-android.txt
Overall method count: 18242

With minify enabled and proguard-android.txt
Overall method count: 7836

With minify enabled and proguard-android-optimize.txt
Overall method count: 6690

Removing parcelables (So far I'm not using any from framework neither other libs)
Overall method count: 6690

https://guides.codepath.com/android/Configuring-ProGuard

https://docs.fabric.io/android/crashlytics/dex-and-proguard.html

References
<br>[Android Docs](https://developer.android.com/studio/build/shrink-code.html)
<br>[Dex Methods count tool](https://github.com/mihaip/dex-method-counts)
<br>[3](https://lab.getbase.com/proguard-for-android/)