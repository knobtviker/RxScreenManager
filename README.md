# RxScreenManager

[![Release](https://jitpack.io/v/com.knobtviker/RxScreenManager.svg)](https://jitpack.io/#com.knobtviker/RxScreenManager)

This is a [RxJava2](https://github.com/ReactiveX/RxJava) wrapper around Android Things [ScreenManager](https://developer.android.com/things/reference/com/google/android/things/device/ScreenManager.html) API.  

### How to use

Add this to your project level build.gradle:
```
allprojects {
	repositories {
		maven { url "https://jitpack.io" }
	}
}
```

Then add this repository as dependency in your app module build.gradle:
```
dependencies {
    implementation 'com.knobtviker:RxScreenManager:1.0.0'
}
```

### TODO
- Tests.
- Example app.
- RxJava 1 backwards compatibility support.
