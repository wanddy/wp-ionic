# wp-ionic
A cordova hybird app using ionic framework that backing data on wordpress.
### 1 New cordova app
npm install -g cordova ionic
cordova create wp-ionic cn.org.appinventor.wpionic wpionic
### 2 Add platform and build
cordova platform add android
cordova requirements

setp1 and 2 ref http://cordova.apache.org/docs/en/dev/guide/cli/index.html
### 3 copy wpionic file and add plugins
copy & paste wpionic  hooks\ scss\ www\ package.json
cordova plugin add cordova-plugin-crosswalk-webview
cordova plugin add cordova-plugin-device
cordova plugin add cordova-plugin-camera
