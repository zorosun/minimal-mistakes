## Preparing to deploy

- Make sure you include launch image and app icon for all sizes, please make sure the size is exactly match the requirement. There are many online app icon generators for you to choose.
- Able to run in simulator without error. There will be alot of warning but that should be okay.
- Specify your app version and build. You have to update build or version everytime you wanted to update your app. Apple does not allow you to upload the same build and same version.
- Change your scheme to release.
- Get your Apple Developer ID ready.

## Submit to iTune connect

1. `npm install`
2. Open xcode project in project/ios
3. Set Team and authentic certificate to build production ready app
4. In xcode, go to Product → Scheme → Edit Scheme (cmd + <), make sure you're in the Run tab from the side, and set the Build Configuration dropdown to Release.
5. Product -> Archive
6. Archive window -> choose latest archive -> Uplaod. If there is an error, just google it.


Credit
- https://facebook.github.io/react-native/docs/running-on-device.html#building-your-app-for-production
- https://stackoverflow.com/questions/43661945/how-to-make-ipa-file-from-react-native-app