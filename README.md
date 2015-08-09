
#Adding the Plugin to your project

cordova plugin add https://github.com/sebastianor/Cordova-open-native-settings.git

#Removing the Plugin to your project

cordova plugin rm com.phonegap.plugins.nativesettingsopener

#Using the plugin

cordova.plugins.settings.open(success_callback,failure_callback);
