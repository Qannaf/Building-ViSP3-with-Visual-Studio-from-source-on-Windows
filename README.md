# Building-ViSP3-with-Visual-Studio-from-source-on-Windows
In this tutorial I will show yow how to install ViSP from source on Windows 10 with Visual C++. These steps have been tested on Windows 10 (64 bit), with CMake 3.19.4 and Visual Studio Community 2019.

# Install prerequisites
1.Visual Studio
-------------
Visual Studio Community 2019 could be downloaded from https://www.visualstudio.com/downloads/. During a fresh installation enable "Desktop development with C++" workload and check box "Windows 10 SDK" to enable usage of the Graphical Device Interface (GDI) useful to display images in a window thanks to vpDisplayGDI class. After a fresh installation, start Visual Studio and create an empty C++ project to install the common tools for Visual C++ 2019.

If you already have Visual Studio Community 2019, you can check if "Desktop Development with C++" workload is activated and if "Windows 10 SDK" is enabled following instructions given here that we resume:
1.1 Find the Visual Studio Installer on your computer. Select Start, and then scroll to the letter V, where it's listed as Visual Studio Installer
Click or tap to start the installer, and then choose "Modify"
1.2 From the Workloads screen, check if "Desktop Development with C++" workload is activated and if "Windows 10 SDK" is enabled like in the following image
![img-msvc16-config](https://user-images.githubusercontent.com/48203467/109415963-e3a4b680-79bb-11eb-9a2d-28a026cb3955.png)

1.3 Choose Modify again.
1.4 After the new workloads and components are installed, choose Launch.

2.CMake
------
CMake could be download from http://www.cmake.org. Download the latest release for Windows win64-x64 platform (at the time this tutorial was written it was the file cmake-3.19.4-win64-x64.msi). To install just double click on the msi file.

3.Git
------
Install Git for Windows from https://git-for-windows.github.io/. This installation allows then to use git in a cmd Command Prompt.

4.PCL 1.10.0
------------
In this link I show yow how to install ViSP from source on Windows 10 with Visual C++.
https://github.com/Qannaf/Building-PCL-with-Visual-Studio-from-source-on-Windows/blob/main/PCL1.10.0.md

5.OpenCV
--------
Once you have saved the file, follow the blog for further instructions on How to Install OpenCV through this Link

OpenCV Version	Visual Studio 16	Visual Studio 15	Visual Studio 14
OpenCV-4.5.1	OpenCV-4.5.1-vc16.exe	OpenCV-4.5.1-vc15.exe	OpenCV-4.5.1-vc14.exe
OpenCV-4.5.0	OpenCV-4.5.0-vc16.exe	OpenCV-4.5.0-vc15.exe	OpenCV-4.5.0-vc14.exe
OpenCV-4.4.0	OpenCV-4.4.0-vc16.exe	OpenCV-4.4.0-vc15.exe	OpenCV-4.4.0-vc14.exe
OpenCV-4.1.0	OpenCV-4.1.0-vc16.exe	OpenCV-4.1.0-vc15.exe	OpenCV-4.1.0-vc14.exe

