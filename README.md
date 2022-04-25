![](https://icon-library.com/images/mobile-apps-icon/mobile-apps-icon-7.jpg)
### Mobile Application
Mobile Application Development Is One Of The Most Sought-After Fields In The Labor Market, And Therefore It Is Of Great Interest To Companies And Developers.
It Also Enjoys A Lot Of Diversity Through The Approaches Available To Develop The Application .. We Will Now Learn About What Is The Mobile Operating System And How Does It Work?

![](https://g.top4top.io/p_2300f32zz1.png)
### The operating system contains 4 main layers:
#### 1- Kernal and Device Driver
What is meant by it are the operating system definitions to allow you to play audio and image files and all known definitions.. and it is a layer with which neither the user nor the developer interacts.

#### 2- Core OS
And it is a layer that contains all the basic and main system files without which the system will not work, it will stop .. as it is in the Windows system .. There is a folder called Windows that contains all system files .. If you delete files inside this folder, you will not be able to run the system Run again, and therefore it is a layer that it is not desirable to deal with as a developer or as a user of the system.

#### 3- Core Service & Media
Finally, this layer is what you deal with as a developer and as a user, and here is this layer in a simplified way through which the system provides all the tools and programs that allow you to deal with media such as audio, images, video, camera operation or audio recording through your application, and this layer usually deals with Developers and users in a simple way.

#### 4- OEM Widget - Original User Interface
This layer represents 90% of the developer's work.. In this layer, each company has standards and a specific form through which the application of the system appears, for example..
- Android system
It uses a specific system called [Material Design](https://material.io/ "Material Design"), which provides a set of shapes and designs that help developers implement their application.

- ios system
It uses a completely different design system called [Human User Interface](https://developer.apple.com/design/human-interface-guidelines/ "Human User Interface")


If we notice, we will find that all the applications of each system are very similar .. For example, all applications of the Android system are similar to each other, as well as for the iOS system.

Thus, we talked about the smartphone operating system, so let's move on to the two systems that provide application programming for smartphones

------------
### Flutter VS IOS
![](https://blog.codemagic.io/fl_vs_ios_6519329690763382146_hu860fbc6364c0fb8e09b04f1a7781fc18_0_1280x1800_fit_linear_3.png)

We have two ways to program applications and they are..
- Native
And it is an application programming that works on one operating system only.. For example, in the iOS operating system, if you decide to write it in Native, it will work on the iOS system only and will not work on any other system such as Android.

The languages ​​that will be used in application programming are Swift or Objective C.

- Cross-platform
The meaning of cross is diversity or plurality and it was.. This system allows you to write one code to be able to run your application on more than one system and this is what is available in filters.

With one code that you created with filters, you can run it on more than one operating system such as Android, iOS, desktop operating systems and also the web!

### Flutter VS Android
![](https://blog.codemagic.io/fl_vs_and_10526591714446286115_hud95d795c40948d4f1fb2dab2514d6233_0_1280x1800_fit_linear_3.png)
We will talk about the Android operating system through Native
It is exactly the same as the idea of programming an application for iOS, but the language used is different, which is Java or Kotlin.

And here we think a little. If you want to implement a simple application for Android and iOS via Native, it will take a long time to implement on the two systems with their different languages, but through the cross platform, you can do this with one code that works on both systems with ease.

------------
### Architecture 
#### - Native
![](https://blog.codemagic.io/native_arch_18441826894107385812_hu7bf0b0592a3e37adaaff8629a24d85ac_0_1280x1800_fit_linear_3.png)
In the native apps, whether it is Android or iOS, the native app code talks to the Platform to create OEM Widgets or for accessing various Services like audio, sensors, camera, etc. The widgets are rendered to a screen canvas, and events are passed back to the widgets. This architecture restricts the widgets to be reused across all platforms as they are OEM specific. And, this is the reason we have to write whole app for each platform separately.

#### - Flutter
![](https://blog.codemagic.io/flutter_arch_7830193927981686462_hudbb300a1f4eb1da523b0152848c8a63d_0_1280x1800_fit_linear_3.png)
Now, coming to the Flutter apps. Flutter solves the most challenging part of the other cross-platform frameworks, i.e. getting rid of the BRIDGE. Flutter does not use the OEM widgets, it provides its own widgets. Flutter moves the widgets and the renderer from the Platform into the app, which allows them to be customizable and extensible. This also helps Flutter to maintain the consistent 60 FPS.

------------

### What's Flutter
- Flutter is defined as the Google’s UI toolkit for building beautiful, natively compiled applications for mobile (Android, iOS ) desktop (Linux, Mac, Windows, Google Fuchsia) and the web from a single codebase.
- Flutter uses  programming language which was introduced by Google in 2011 and is rarely used by developers. Dart syntax is easy to understand for JavaScript or Java developers as it supports most of the object-oriented concepts.

------------
### Benefits of Flutter
![](https://blog.codemagic.io/flutter_tenets_16166160693565645176_hu51183d645e1e2c043b289a2f86dea4da_0_1280x1800_fit_linear_3.png)
##### - Productivity:
Since Flutter is cross-platform, you can use the same code base for your iOS and Android app. This can definitely save you both time and resources.
##### - Performance:
Dart compiles into native code and there is no need to access OEM widgets as Flutter has its own, this means faster code execution.
##### - Fast and simple development:
One of the most lauded features of Flutter is hot reload which allows you to instantly view the changes made in the code on emulators, simulators and hardware in less than a second.
##### - Compatibility:
Since widgets are part of the app and not the platform, you’ll likely experience less or no compatibility issues on different OS versions.
##### - Open-source:
Both Flutter and Dart are open-source in github and free to use.

------------

This is the beginning of an introduction to what we are coming to now.. You can find out more details [from here](https://blog.codemagic.io/what-is-flutter-benefits-and-limitations// "from here").

# Basics
## Dev Enviroment
Here you can choose your preferred dev environment..
### Offline
- [Android Studio](https://developer.android.com/studio?gclid=Cj0KCQjw3v6SBhCsARIsACyrRAmw7fH7v8rOu10Z4fFV6P1K_yFC_vIf21dE2mkCR8uLTr41hb51CIMaAmBiEALw_wcB&gclsrc=aw.ds)
- [VSCode](https://code.visualstudio.com)
- [Intellij IDEA](https://www.jetbrains.com/idea/)

### Online
- [Dart Pad](https://dartpad.dev)

## Language
At first we learn the programming language Dart .. **we learn it perfectly!!**
Choose one of the next resourses..
+ Arabic Resources
  + [Code2Start](https://www.youtube.com/watch?v=ZYXol94Lyi0&list=PL3aG1K3LWCrdihgr1PnIrbphTyt3PZwoK)
  + [Everest Academy](https://www.youtube.com/watch?v=W_INooszMtM&list=PLOFO6BO5XHZZ1aqrtC4J1f_4Pb6YFbF86)
  + [Wael Abo hamza](https://www.youtube.com/watch?v=kgN7veo9tC0&list=PL93xoMrxRJIsYc9L0XBSaiiuq01JTMQ_o)
  + [Asem Safaan](https://www.youtube.com/watch?v=HVYlPAw70MU&list=PLMDrOnfT8EAj6Yjdki9OCLSwqdBs4xhQz)
  + [Mr. Developer](https://www.youtube.com/watch?v=_dAs23kBnPM&list=PL2mK_EczeaCtMH5QB83kfFbi85Y2Xc0tV)
+ English Resourses
  + [Fluttery](https://www.youtube.com/watch?v=uZvoTCSsfjo&list=PLptHs0ZDJKt_fLp8ImPQVc1obUJKDSQL7)
  + [Academind](https://www.youtube.com/watch?v=x0uinJvhNxI)  crash-course
  + [freeCodeCamp.org](https://www.youtube.com/watch?v=Ej_Pcr4uC2Q)  crash-course
  + [Mike Dane](https://www.youtube.com/watch?v=5xlVP04905w)  crash-course

---------------

# Flutter
You must watch the video [“What are Flutter”](https://www.youtube.com/watch?v=gvAvYwMM5MA&t) before starting any course so that you can understand what is coming next ..

## Everything is a widget ..
![](https://vitalflux.com/wp-content/uploads/2020/07/widget-animation.gif)
After you have studied the Dart course, there is an important thing that you must know, which is that filters are a set of widgets that you must know in order to be able to start..

+ Arabic Resources
  + [Code2Start](https://www.youtube.com/watch?v=QdWIE6VFiAM&list=PL3aG1K3LWCrejzY86JLKfjw-hThXYSf_1)
  + [Eyad Development](https://www.youtube.com/watch?v=t6OZzbFDnYs&list=PLuBL2DYgVDm0ugRCTjNatqDBaf7JP8vc8)
  + [Wael Abo hamza](https://www.youtube.com/watch?v=qfm-mG-BCJs&list=PL93xoMrxRJItdRumqolHX0UT-LHK8_39N)
  + [Asem Safaan](https://www.youtube.com/watch?v=hCDX5ttbxnw&list=PLMDrOnfT8EAhsiJwkzspHp_Ob6oRCHxv0)
  + [Mohamed Saudi](https://www.youtube.com/watch?v=cShqGV13qdo&list=PLoMmMinVeSkud4SURAo6ccR6MduZWTdTq)
+ English Resourses
  + [The Net Ninja](https://www.youtube.com/watch?v=1ukSR1GRtMU&list=PL4cUxeGkcC9jLYyp2Aoh6hcWuxFDX6PBJ)
  + [Easy Approach](https://www.youtube.com/watch?v=QwXqNGPaacY&list=PLh7i6AwsWt1s4GFfeBNsU8WiKhOPg1kix)
  + [freeCodeCamp.org](https://www.youtube.com/watch?v=VPvVD8t02U8)  crash-course
  + [Academind](https://www.youtube.com/watch?v=x0uinJvhNxI)  crash-course
  
## Networking
After you know about all the widgets in Flutter, you should know what is meant by API and how you can make your application connected to a specific API.. Through the following videos, you will be able to understand what is meant by Networking ..

### What's API
#### English
   - [MuleSoft Videos](https://www.youtube.com/watch?v=s7wmiS2mSXY)
   - [Programming with Mosh](https://www.youtube.com/watch?v=SLwpqD8n3d0)
#### Arabic
   - [A-To-Z ForLearning](https://www.youtube.com/watch?v=u5EInXlNfWE)
   - [Dev Zone](https://www.youtube.com/watch?v=lNOVhs0AGWk)
