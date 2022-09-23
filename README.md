# SPSGP-54858-Virtual-Internship---Android-Application-Development-Using-Kotlin
# **GROCERY LIST APPLICATION USING KOTLIN IN ANDROID STUDIO**
## **Chapter-I**
### **1.1 Abstract:**
Android is an open-source operating system that runs on the linux kernel. With the advent of
new mobile technologies, the mobile application industry is advancing rapidly. Consisting of
several operating systems like symbian OS, iOS, blackberry, etc., Android OS is recognized as
the most widely used, popular and user-friendly mobile platform. This open-source linux kernelbased operating system offers high flexibility due to its customization properties making it a
dominant mobile operating system.
Android applications are developed using the java language. Google has its own Software
Development Kit (SDK) which enables these java codes to control devices like mobile phones,
tablets, etc. Android mobile application development provides a flexible platform for developers
where they can use both java Integrated Development Environment (IDEs) and android java
libraries.
Google android SDK delivers a special software stack that provides developers an easy platform
to develop android applications. Moreover, developers can make use of existing java IDEs which
provides flexibility to the developers. Java libraries are predominant in the process of third-party
application development. Cross-platform approaches make sure that developers do not have to
develop platform-dependent applications. With the help of these approaches, an application can
be deployed to several platforms without the need for changes in coding. However, android is
more prone to security vulnerabilities which the majority of the users do not take into account.
Any android developer can upload their application on the android market which can cause a
security threat to any android device. These applications do not have to go through rigorous
security checks. In this report, a layered approach for android application development along
with various cross-platform approaches is discussed.
### **1.2 Objective:**
The main aim of this project is to list the items so that whenever users go to grocery stores, users will not be able to forget their items and this grocery application helps the users to tackle their day to day chaos more effortlessly. 
### **1.3 Problem Targeted:**
It’s not easy for the users to remember every item in this hectic lifestyle, they frequently can’t recall their required necessity so we decided to build an app to store the items in the database for their future use. After buying the items users can delete the added items in the database.
### **1.4 Problem's Primary Goals:**
The goal of this project is to make an app that stores the user items in a cart and can modify and delete the added item in the list. To develop a reliable system, I have some specific goals such as:

	Develop a system such that users can add item details like product name, product Quantity, and Product Price.

	Develop a database room that is used to store the user data which already been added by the user in the cart and the user can also remove the previously added item in the cart.

	Develop a good UI design that user friendly to the user.

	Develop a good UI that is supported for all android devices.

### **1.5 Introduction:**
We are going to build a grocery application in android using Android Studio. Many times we forget to purchase things that we want to buy, after all, we can’t remember all the items, so with the help of this app, you can note down your grocery items that you are going to purchase, by doing this you can’t forget any items that you want to purchase. In this project, we are using (MVVM) for architectural patterns, Room for database, Recycler View and Coroutines to display the list of items.
## **Chapter-II**
### **2.1 Background:**
The grocery cart application project will help the user or admin to store the list of items in proper sequence. User/Admin can add and remove the items in the list according to his/her will.
 
	UI DESIGN IN THE ANDROID PLATFORM

	ANDROID APPLICATION DEVELOPMENT

	DATABASE CONNECTION TO STORE USER DATA

![image](https://user-images.githubusercontent.com/71881295/191746122-32976452-f98a-46b4-837d-df3d959f7116.png)
## **Chapter-III**
### **3.1 Software Requirements:**
The Software Package is developed using Kotlin and Android Studio, basic SQL commands are used to store the database.
Operating System: Windows 11
Software: Kotlin and Java
Emulator: Pixel 4 API 30
### **3.2 Hardware Requirements:**
RAM: 16 GB RAM
ROM: 20 GB ROM
## **Chapter-IV**
### **4.1 MVVM (Model View ViewModel):**
MVVM architecture in android is used to give structure to the project’s code and understand code easily. MVVM is an architectural design pattern in android. MVVM treat Activity classes and XML files as View. This design pattern completely separate UI from its logic. Here is an image to quickly understand MVVM. 
![image](https://user-images.githubusercontent.com/71881295/191746970-79b2d88d-08da-40a7-9736-7850920185fa.png)
### **4.2 ROOM Database:**
Room persistence library is a database management library and it is used to store the data of apps like grocery item name, grocery item quantity, and grocery item price. Room is a cover layer on SQLite which helps to perform the operation on the database easily.
### **4.3 RecycleView:**
RecyclerView is a container and it is used to display the collection of data in a large amount of dataset that can be scrolled very effectively by maintaining a limited number of views.
### **4.4 Coroutines:**
Coroutines are a lightweight thread, we use coroutines to perform an operation on other threads, by this our main thread doesn’t block and our app doesn’t crash.
## **Step By Step Process**
### **Step 1: Create a New Project**
To create a new project in Android Studio please refer to How to Create/Start a New Project in Android Studio. 
Note that select Kotlin as the programming language.
### **Step 2: Before going to the coding section first you have to do some pre-task**
Before going to the coding part first add these libraries in your gradle file and also apply the plugin as ‘kotlin-kapt’. To add these library go to Gradle Scripts > build.gradle(Module: app).

















