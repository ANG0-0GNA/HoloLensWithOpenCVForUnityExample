HoloLens With OpenCVForUnity Example
====================

What's new
-----
By using the �gHoloLensCameraStream�h asset, video capture can now be executed faster.


Demo Video (old version)
-----
[![](http://img.youtube.com/vi/SdzsedkTpCI/0.jpg)](https://youtu.be/SdzsedkTpCI)


Environment
-----
Windows 10 Pro 1709  
Windows 10 SDK 10.0.14393.0 to 10.0.16299.0
Visual Studio 2017 (v151.5.0)
Unity 2017.1.3f1  
HoloToolkit-Unity-v1.2017.1.2 ([https://github.com/Microsoft/MixedRealityToolkit-Unity/releases](https://github.com/Microsoft/MixedRealityToolkit-Unity/releases))  
OpenCV for Unity 2.2.6 ([https://assetstore.unity.com/packages/tools/integration/opencv-for-unity-21088](https://assetstore.unity.com/packages/tools/integration/opencv-for-unity-21088))  
HoloLensCameraStream ([https://github.com/VulcanTechnologies/HoloLensCameraStream](https://github.com/VulcanTechnologies/HoloLensCameraStream))  

Setup
-----
* Clone this repository.
* Create a new project. (HoloLensWithOpenCVForUnityExample)
* Import the HoloToolkit-Unity-v1.2017.1.2.unitypackage.
* Setup the HoloToolKit. (Mixed Reality ToolKit > Configure > Apply Mixed Reality Project Setting)
* Import the OpenCVForUnity.
* Clone HoloLensCameraStream repository.
* Import the HoloLensCameraStream. (Copy the �gHoloLensCameraStream/HoloLensVideoCaptureExample/Assets/CamStream/�h folder to the �gAssets/�h folder.)
* Import the HoloLensWithOpenCVForUnityExample.unitypackage.
![buildsetting01.jpg](buildsetting01.jpg) 
* Add the �gAssets/HoloLensWithOpenCVForUnityExample/*.unity�h files to the �gScenes In Build�h list in the �gBuild Settings�h window.
* Add the �gWebCam�h to �gPublishing Settings > Capabilities�h checklist in the �gPlayer Settings�h window.
![buildsetting02.jpg](buildsetting02.jpg) 
* Build and Deploy to HoloLens. (See [https://developer.microsoft.com/en-us/windows/holographic/holograms_100](https://developer.microsoft.com/en-us/windows/holographic/holograms_100))
*  (Print the AR marker �gArUcoMarker_DICT_6X6_250_ID1.pdf�h on an A4 size paper)

ScreenShot (old version)
-----
![screenshot01.jpg](screenshot01.jpg) 

![screenshot02.jpg](screenshot02.jpg) 

![screenshot03.jpg](screenshot03.jpg) 

![screenshot04.jpg](screenshot04.jpg) 

![screenshot05.jpg](screenshot05.jpg) 


![Light_Frame.png](Light_Frame.png)


