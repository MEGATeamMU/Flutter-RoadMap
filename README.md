![](https://icon-library.com/images/mobile-apps-icon/mobile-apps-icon-7.jpg)
### Mobile Application
Mobile Application Development Is One Of The Most Sought-After Fields In The Labor Market, And Therefore It Is Of Great Interest To Companies And Developers.
It Also Enjoys A Lot Of Diversity Through The Approaches Available To Develop The Application .. We Will Now Learn About What Is The Mobile Operating System And How Does It Work?

![](https://g.top4top.io/p_2300f32zz1.png)
###The operating system contains 4 main layers:
####1- Kernal and Device Driver
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
