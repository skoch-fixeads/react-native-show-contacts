# react-native-show-contacts

Using
- React Native
- Redux
- React-Redux
- React-Native-Router-Flux
- React-Native-Contact
- React-Native-Communications


For now only support android.
see:
https://github.com/stvkoch/react-native-show-contacts/blob/master/index.android.js

<img src="https://raw.githubusercontent.com/stvkoch/react-native-show-contacts/master/contactList.png" alt="alt tag" width="250">
<img src="https://raw.githubusercontent.com/stvkoch/react-native-show-contacts/master/contactDetail.png" alt="alt tag" width="250">



## Useful _adb_ commands:


Capture screenshot:

	adb shell screencap /sdcard/sreen.png


Kill app:

	adb shell am force-stop com.lellol.conct

Show proccess:

	adb shell ps

Map localhost port to mobile port

	adb reverse tcp:8081 tcp:8081



Show log:

	adb logcat '*:S' ReactNative:V ReactNativeJS:V

	adb logcat com.lellol.conct:I 89c3d001|grep skoch -B 10 -A 10
