JUGAADU LUDO - OFFLINE ANDROID PROJECT

Yeh Android Studio project hai. Game ki HTML/CSS/JavaScript aur images APK ke andar app/src/main/assets mein bundled hain.
App WebView ke andar local file:///android_asset/index.html load karta hai. Manifest mein INTERNET permission nahi hai aur WebView network loads block karta hai. Isliye game kisi website ko open nahi karegi.

APK banane ke steps:
1. Android Studio install/open karein.
2. File > Open se is extracted project folder ko select karein.
3. Gradle sync complete hone dein (pehli baar Android Gradle Plugin/SDK download ke liye internet chahiye).
4. Build > Build Bundle(s) / APK(s) > Build APK(s).
5. APK app/build/outputs/apk/debug/app-debug.apk par milegi.
6. APK phone mein bhejkar install karein. Phone par install ke baad game offline chalegi.

Note: Build karne ke liye computer par Android Studio + Android SDK ki zaroorat hai. APK install karne ke baad game chalane ke liye internet ki zaroorat nahi.
