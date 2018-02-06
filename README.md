# tensorflow_mobile

### Installation Instructions:

Follow the installation instructions given in the [link] (https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/android)

It says, NDK 16 is not compatible version and 14b is the compatible version, I found old NDK files [here](https://developer.android.com/studio/releases/build-tools.html)

I already installed SDK tools using Android Studio.

Steps:

  - Downloaded the NDK compressed file from the above link.
  - Uncompress the compressed file and renamed the folder name to ndk
  - Moved the file to
    - /Users/Username/Library/Android/sdk/
    - Final folder structure = /Users/Dinesh/Library/Android/sdk/ndk
  
  
Added the following to bash file and did source bash file
export ANDROID_NDK=/Users/Username/Library/Android/sdk/ndk
export PATH=$PATH:/Users/Username/Library/Android/sdk/ndk
