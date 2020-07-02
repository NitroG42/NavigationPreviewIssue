# Error sample navigation preview

Android Studio 4.1 and 4.2 beta/canary cannot display the file nav_test.xml preview normally.

On Android Studio 4.0 :
![Android Studio 4.0]()

On Android Studio 4.1 and 4.2 :
![Android Studio 4.2]()

Removing the following line from build.gradle (app) makes it work again :

implementation project(":mylibrary")