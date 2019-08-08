# cordova-plugin-checker

Checks app version


### getAppVersion(appPackageName)

It returns a promise which will be resolved to the string representation of the version number (eg: `57.0.2987.132`) or rejected with a `Package is not found` error if the app is not installed

```js
plugins.webViewChecker.getAppVersion(appPackageName)
  .then(function(version) { console.log(version); })
  .catch(function(error) { console.error(error); });
```
