# Unity_Project_Templates

# Template for AR Foundation based on Unity 2020.3 LTS

## Dependencies / Packages

* AR Foundation 
* ARCore Extensions (https://github.com/google-ar/arcore-unity-extensions.git)
* Universal Rendering Pipeline

## Basic Setup

* Based on the AR Template of Unity 2020.3 LTS (Downloadable)
* Enabled ARCore on Android, removed Vulkan in graphics settings, switched to API level 24 and IL2CPP (for 64bit)
* Configured ARCore for Android in the XR Plug-in Management Settings
* Added ARCore Extensions from https://github.com/google-ar/arcore-unity-extensions.git based on the description on this page: https://developers.google.com/ar/develop/unity-arf/getting-started-extensions
* Configured Universal Rendering Pipeline
* Enabled background rendering of camera picture
* Enabled Development Build and Scrupt Debugging

# How to Start and Use

* Open the project in Unity
* Switch Build Settings to Android + Development Build + Script Debugging
* Open Scenes/BasicARScene

# FAQ

* There is a strange error when running Unity 2020.3 LTS without Build-Support for iOS. Then the following issue keeps popping up in the console: "Assembly 'Packages/com.google.ar.core.arfoundation.extensions/Editor/ExternalDependencyManager/Editor/Google.IOSResolver.dll' will not be loaded due to errors:
Unable to resolve reference 'UnityEditor.iOS.Extensions.Xcode'. Is the assembly missing or incompatible with the current platform?
Reference validation can be disabled in the Plugin Inspector.". This should be solved when installing iOS Build Support, but should also be not a problem, just annoying, when not installing the Build Support for iOS.