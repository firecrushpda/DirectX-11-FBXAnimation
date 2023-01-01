# DirectX-11-FBXAnimation

Here is a small sample made by DirectX11.
I use FBXSDK2019 library to parse a FBX model and animation which made and exported by Blender

you can double click DirectX 11 Engine VS2017.exe to check the result 
or you can build the project yourself 

build issues:
1.when you open up .sln file you should relocate the 
    project -> propertites -> C/C++ -> General -> Additional Include Directories
                           -> Linker -> Input -> Additional Dependencies 
  make sure your include path is fit your FBKSDK file path
  
2. if you cant open source file correctly maybe there is some code page problem
which is caulsed by note word written in Chinese,you can open in chinese code page 
and delete these note then you can see the code correctly

thanks to Jacob Pindrought who provide the DirectX11 framework for the project
i use his tutorial guide capture 44 and 45
the framework contain DirectXTK lib and Imgui for UI work 
the detail explain for these two can be found in his youtube channel : 
  
  https://www.youtube.com/watch?v=gQIG77PfLgo&list=PLcacUGyBsOIBlGyQQWzp6D1Xn6ZENx9Y2

the model i used for this test is made in the guide of youtube channel : 
  
  3Dのメモ帳 video upload : https://www.youtube.com/watch?v=7DClegc4SZ0
                           https://www.youtube.com/watch?v=SXD0rmpYIWo&t=637s
                           https://www.youtube.com/watch?v=02yENu82rIU&t=611s

it is a japanese blender tutorial whitch contain model making and animation making
 
the sample does not contain the material parse i will do it later
