# build-openssl-android
A simple bash script for building openssl android.

## Setup Android Development on Mac OS X

* Install Android SDK and NDK

```
brew install android android-ndk ant makedepend
```

* Edit `~/.bashrc` and add:

```
# Android SDK
export ANDROID_SDK_ROOT=/usr/local/Cellar/android-sdk/23.0.2
export ANDROID_NDK_ROOT=/usr/local/Cellar/android-ndk/r10b
```

* Run

```
source ~/.bashrc
```

## Usage `./build-openssl-android.sh <version>`
* Build openssl-1.0.1j

```
./build-openssl-android.sh 1.0.1j
```

* Build openssl-1.0.2-beta3

```
./build-openssl-android.sh 1.0.2-beta3
```