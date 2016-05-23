#Build ShadowSocks native libs
Make sure you have installed Android NDK.


##Build
```
ndk-build
```

##Copy to the Android project
Copy the lib folders in `/libs` to `$ANDROID_PROJECT/app/src/main/assets`