# React Native Native Modules Communication

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/lastminutedotcom/React-Native-Native-Modules-Communication/master/LICENSE.md)

An example project in which I describe a simple architecture for communication between React Native Native Modules 
(usually called bridges) and the Native UIViewController/Activity/Fragment that host the React Native component. 
Generally speaking the architecture shown in this project is useful to let the Native Modules communicate with your 
existing native codebase.
This is a project for the blog posts [React Native: a simple architecture for Native Modules communication with your UIViewController on iOS](https://technology.lastminute.com/react-native-modules-bridge-communication-uiviewcontroller-ios/ "React Native: a simple architecture for Native Modules communication with your UIViewController on iOS")  

### Description

This are some quotes from the post:

> ...Sometimes when you integrated React Native in an existing app, you will want to be able to let your Native
Modules bridges communicate with your UIViewController, especially the ones that contain the `RCTRootView` React
Native View.
In this post I will show you an architecture to put in place this communication on iOS, that will be compatible with
all the features of React Native (for example it will work also with the live reload functionality). This is an
architecture that we put in place for our mobile apps and it already in production.... 

Click on the links above to read the posts.
