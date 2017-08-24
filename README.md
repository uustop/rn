# rn
rn 0.44.3 集成 导航
1.react-native init rn --version 0.44.3
2.npm install react-native-vector-icons --save
3.yarn add react-navigation
4.
Browse to node_modules/react-native-vector-icons and drag the folder Fonts (or just the ones you want) to your project in Xcode. Make sure your app is checked under "Add to targets" and that "Create groups" is checked if you add the whole folder.
Edit Info.plist and add a property called Fonts provided by application (or UIAppFonts if Xcode won't autocomplete/not using Xcode) and type in the files you just added. It will look something like this:
XCode screenshot
5.react-native run-android # or:
react-native run-ios
