# react-native-custom-fonts

---------------
npm install --save react-native-custom-fonts

OR

yarn add react-native-custom-fonts

---------------
FOR IOS :
---------------
<key>UIAppFonts</key>
<array>
  <string>YourFontName.ttf</string>
</array>

---------------
HOW TO USAGE
---------------

import CustomFont from 'react-native-custom-fonts'
componentDidMount() {
   let fontName = 'YourFontName' // without .tff
   CustomFont.applyCustom(fontName)
}

-----------------

NOTE: Please make sure your fonts assets already in android assets. 
path: android/app/src/main/assets/fonts

Then rebuild your apk.
Done.