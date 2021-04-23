# MyApplication_TODO
![Todo](https://user-images.githubusercontent.com/83036192/115811693-2c765b80-a3be-11eb-9148-1cc971b212d0.jpg)

> All in One Task Manager- Manage your task without reminding

## Table of Content:

-Description.

-How to install

-Troubleshooting

-Features

-Technologies

-Manifests

-Dependencies

## Description:
- This application is all about saving the different tasks which you have to do on the daily basis. The main plus point is the user can remember doing every tasks at a time without getting reminded.
This application has one great option of deleting the taskes which are completed on the daily basis. It is a good exercise to do as when the user will get used to this application, he oe she will 
always remember the tasks which they have to do and it will also keep the record is the user doesnot delete the tasks that are completed. Todo list is very useful in our life as it can tell us what 
activity we have to do on the daily basis.

## How to install:
- To install this application the user need to download the zip file from the repository and then extract it using any device. To successsfully install and open the application the user need to have 
android studio and mif the user is downloading the app for learning or refereing the code then they should learn the basics of "Kotlin Language".

## Troubleshooting: 
- If the user is facing trouble in running the application and if there are few errors in the MainActivity.kt or TodoAdapter.kt , then the user must have downloaded the proper SDK files. The user must
have install few SDK's versions like go to the tools and then to SDK Manager and in the SDK Manager the user will find the SDK Platform and in that the user must have to install the 
-Android S Preview

-Android 11.0(R)

-Android 10.0(Q)

## Features:

- ### Screenshots of the application.
![Output2](https://user-images.githubusercontent.com/83036192/115815176-7e21e480-a3c4-11eb-8021-4e8f471a3ffd.jpeg)
![Output1](https://user-images.githubusercontent.com/83036192/115815180-7f531180-a3c4-11eb-887e-ed4b804b9a58.jpeg)
![Output3](https://user-images.githubusercontent.com/83036192/115815182-7f531180-a3c4-11eb-8e2d-f175652c954c.jpeg)

-As you see there are two features in my app, they are just Add the todo title and the delete option which can delete the task once the user have done and checked the tasks.

## Technologies:
- I have used the Android Studio of 4.1.3 version and the whole code is written in the Kotlin language. 
In this code I have used the Constraint LAyout to draw the perfect layout and the recycler view which can add the list of Todo Items in the app.
Also, there are two xml file that are used only for the layout of the item list. So the items_of_todo.xml file is redirectd to the MainActivity.kt and TodoAdapter.kt.

## Manifest Files:
![Files2](https://user-images.githubusercontent.com/83036192/115811714-3b5d0e00-a3be-11eb-94ec-3b97348d9119.JPG)

![Files](https://user-images.githubusercontent.com/83036192/115811717-3c8e3b00-a3be-11eb-93f1-34046a14817b.JPG)

## Dependencies:

-dependencies {
    
    implementation fileTree(dir: "libs", include: ["*.jar"])
    
    implementation "org.jetbrains.kotlin:kotlin-stdlib:$kotlin_version"
    
    implementation 'androidx.core:core-ktx:1.3.1'
    
    implementation 'androidx.appcompat:appcompat:1.2.0'
    
    implementation 'androidx.constraintlayout:constraintlayout:2.0.1'
    
    testImplementation 'junit:junit:4.12'
    
    androidTestImplementation 'androidx.test.ext:junit:1.1.2'
    
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.3.0'

    implementation 'com.google.android.material:material:1.3.0-alpha02'
}

## Author Contact:
  Mit Soni
  msoni2@lakeheadu.ca
