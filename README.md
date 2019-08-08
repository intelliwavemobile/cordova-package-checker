# cordova-plugin-package-checker

Gets an app version

### Install
cordova plugin add https://github.com/intelliwavemobile/cordova-package-checker.git

### getAppVersion(appPackageName)

It returns a promise which will be resolved to the string representation of the version number (eg: `57.0.2987.132`) or rejected with a `Package is not found` error if the app is not installed

```js
// appPackageName: com.example.name
plugins.webViewChecker.getAppVersion(appPackageName)
  .then(function(version) { console.log(version); })
  .catch(function(error) { console.error(error); });
```
