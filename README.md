# androidtools
A set of linux commandline tools to make my life easier. 

## android-bruteactivities
A script that tries to open all found activities within a mobile app

## android-generatekeystore
generates a debug keystore for signing. NOT FOR PRODUCTION USE

## android-patchapk-frida
patches an apk or multiple apk's in a folder with frida so that root is not required

## android-signapk
signs an apk based on a debug certificate to test code changes. 

## android-installstudio
android-installstudio installs android studio and the fastboot tools from google instead of the adb installed ones (which are bugged)

## android-logappdata
android-logappdata uses adb logcat for the specific app PID so only app data will be logged to a file

## android-pullapk
android-pullapk pulls apk's from an android device, names them, sorts them and attempts to upload them to mobsf.

## android-setproxy
android-setproxy sets the adb proxy for eth0 or wlan0 for use with a test phone

## android-unsetproxy
android-unsetproxy unsets the adb proxy for eth0 or wlan0 for use with a test phone

## mobsf
Attempts to start the mobile security framework from a default location.

## mobsf-scanapp
mobsf-scanapp accepts an .apk, .zip, or .ipa for scanning with mobsf and uses the built in api to scan the app.  
