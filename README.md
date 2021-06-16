# cordova_flutter
A cordova app that is capable of running flutter app inside

Tested :heavy_check_mark: OK

In ❤️ with cordova community

You can clone this 📁 and start your desired application

## Platforms available
1. Android
2. iOS

## Requirements
1. Flutter installation should be completed.
 
    To install flutter follow this <https://flutter.dev/docs/get-started/install>
    
2. Cordova version requirements are there , for more info follow the plugin documentation <https://www.npmjs.com/package/cordova-plugin-flutter> , for english version of the same refere ##plugin documentation section below 


## Steps
1. Create a cordova project
  `cordova create cordova_flutter`. Replace `cordova_flutter` with your project name
2. Add platform
   `cordova add platform android`
3. Add cordova-plugin-flutter to your project
    `cordova plugin add cordova-plugin-flutter`
4. Thats it you can now write your flutter app inside corodova

5. `cordova run android` will not work here use `cordova build android` instead.

## Warnings

1. In some systems, `repositories.gradle` file remains missing , you have to add a blank `repositories.gradle` file to the location, which its prompting in terminal error.

2. In some computers you have to make new cordova project to make this work.


## cordova-plugin-flutter documentation
  1. Use google translator to read in English <https://www.npmjs.com/package/cordova-plugin-flutter>

## Performance improvement
✖️ Any one interested to have a collaboration for performance improvement can mail me at <anshuman@nexsb.in>
  
Thanks to ❤️ [@waitaction](https://github.com/waitaction) for such awesome plugin.
  
  
  



