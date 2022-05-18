
# SeededCrypto for Android

## Installation

SeededCrypto is available through [JitPack](https://jitpack.io/). To install
it, simply follow the instructions:


Add it in your root build.gradle at the end of repositories:
```
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

Add the dependency
```
implementation "com.github.dicekeys:seeded-crypto-android:$latestRelease"
```


### Prerequisites Install CMake and Ninja

#### MacOS

```
brew install cmake
brew install ninja
```

#### Windows
```
 1. Download and install CMake version >= 3.15.0. https://cmake.org/download/
 1. Download ninja-build. https://github.com/ninja-build/ninja/releases and put it on your PATH
 1. Install Android Studio and the Android SDK in it
 1. set enivironment variable ANDROID_HOME to to $HOME/AppData/Local/Android/Sdk (may not actually be necessary, since I succeeded without doing this on 2020-2-11 - Stuart)
```

```
git clone --recursive https://github.com/dicekeys/seeded-crypto-android.git
```
