install xcode
install cocoapods
go in to `ios` folder and instal pods `pod install`
open preferences > components > install simulator

install android studio
run go to conofigure sdk manager > SDK Tools > Ccheck Android SDK Build-Tools
change your PATH
must include

```
export ANDROID_SDK=/Users/XXX_USER_XXX/Library/Android/sdk
export PATH=$PATH:$ANDROID_HOME/emulator
export PATH=$PATH:$ANDROID_HOME/tools
export PATH=$PATH:$ANDROID_HOME/tools/bin
export PATH=$PATH:$ANDROID_HOME/platform-tools
export PATH=/Users/XXX_USER_XXX/Library/Android/sdk/platform-tools:$PATH
```

go to android
create file `local.properites`

https://stackoverflow.com/questions/32634352/react-native-android-build-failed-sdk-location-not-found
