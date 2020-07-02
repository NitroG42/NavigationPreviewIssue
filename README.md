# Error sample navigation preview

Android Studio 4.1 and 4.2 beta/canary cannot display the file nav_test.xml preview normally.

On Android Studio 4.0 :
![Android Studio 4.0](https://raw.githubusercontent.com/NitroG42/NavigationPreviewIssue/master/screens/androidstudio40.png)

On Android Studio 4.1 and 4.2 :
![Android Studio 4.2](https://raw.githubusercontent.com/NitroG42/NavigationPreviewIssue/master/screens/androidstudio42.png)

Removing the following line from build.gradle (app) makes it work again :

implementation project(":mylibrary")