# Display Webpage demo (with WebView)
displaywebpagedemo-rybackpo created by Classroom for GitHub

This assignment illustrates how to display a webpage from an Android application.

## Problem:

Implement an Android application that displays DLSU webpage on launch.

## Basic WebView usage in MainActivity.java:

```Java
   public void displayWebpage(){
        WebView webview = (WebView) findViewById(R.id.viewwebpagedlsu);
        webview.loadUrl("http://www.dlsu.edu.ph");
    }
```

## Sample Solution:

https://github.com/DeLaSalleUniversity-Manila/displaywebpagedemo-rybackpo

## Keypoints:

On layout xml:

```xml
 <WebView
        xmlns:android="http://schemas.android.com/apk/res/android"
        android:id="@+id/viewwebpagedlsu"
        android:layout_width="match_parent"
        android:layout_height="match_parent" />
```

On AndroidManifext xml (In order to have Access to the Internet):

```xml
<uses-permission android:name="android.permission.INTERNET" />
```

## Screenshots:

![alt tag](https://github.com/DeLaSalleUniversity-Manila/displaywebpagedemo-rybackpo/blob/master/device-2015-10-04-175154.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/displaywebpagedemo-rybackpo/blob/master/device-2015-10-04-175249.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/displaywebpagedemo-rybackpo/blob/master/device-2015-10-04-175415.png)
