# Display Webpage demo (with WebView)

displaywebpagedemo-melvincabatuan created by Classroom for GitHub

This assignment illustrates how to display a webpage from an Android application.

## Problem:

Implement an Android application that displays DLSU webpage on launch.


## Basic WebView usage in MainActivity.java:

```Java
   public void displayWebpage(){
        WebView wv = (WebView) findViewById(R.id.webviewdlsu);
        wv.loadUrl("http://www.dlsu.edu.ph");
    }
```


## Accept

To accept the assignment, click the following URL:

 https://classroom.github.com/assignment-invitations/62b3c1d904e30b167d6b0b54e5fed7ac   


## Sample Solution:

https://github.com/DeLaSalleUniversity-Manila/displaywebpagedemo-melvincabatuan


## Keypoints:

On layout xml:

```xml
 <WebView  xmlns:android="http://schemas.android.com/apk/res/android"
    android:id="@+id/webviewdlsu"
    android:layout_width="match_parent"
    android:layout_height="match_parent" />
```



## Submission Procedure with Git (sample): 

```shell
$ cd /path/to/your/android/app/
$ git init
$ git add –all
$ git commit -m "your message, e.x. Assignment 1 submission"
$ git remote add origin <Assignment link copied from assignment github, e.x. https://github.com/DeLaSalleUniversity-Manila/secondactivityassignment-melvincabatuan.git>
$ git push -u origin master
<then Enter Username and Password>
```

Ex. https://gist.github.com/melvincabatuan/cdc7f35815c2dcb0be73 


## Screenshots:

![alt tag](https://github.com/DeLaSalleUniversity-Manila/displaywebpagedemo-melvincabatuan/blob/master/device-2015-10-02-201143.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/displaywebpagedemo-melvincabatuan/blob/master/device-2015-10-02-201355.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/displaywebpagedemo-melvincabatuan/blob/master/device-2015-10-02-201555.png)

"The difference between the right word and the almost right word is the difference between lightning and the lightning bug." - Mark Twain
