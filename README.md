# cordova-tutorial
This step will download and install Cordova module globally. Open the command prompt and run the following 
npm install -g cordova

how to create cordova application
steps to follow
1.create first app using command line 
cordova create hello com.example.hello HelloWorld
hello>>Folder name
com.example.hello>>package name /unique domain name
HelloWorld>>App name

2.Add platform i.e for which platform we are going create the app(android/IOS)
cordova platform add android(to add android)
cordova platform remove android(to remove android)
cordova platform add ios(for ios)

3.Add plugins according to the requirements like
// npm hosted (new) id
cordova plugin add cordova-plugin-splashscreen

// you may also install directly from this repo
cordova plugin add https://github.com/apache/cordova-plugin-splashscreen.git

------------------some usefull cmd-------------------------------

Cordova -v(to check cordova version)
cordova platform version android(to check android version)

cordova plugin list(to check plugins in application)
cordova info(to check information of config.xml file)


