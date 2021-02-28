# Building-ViSP3-with-Visual-Studio-from-source-on-Windows
In this tutorial I will show yow how to install ViSP from source on Windows 10 with Visual C++. These steps have been tested on Windows 10 (64 bit), with CMake 3.19.4 and Visual Studio Community 2019.

# Install prerequisites
1.Visual Studio
-------------
Visual Studio Community 2019 could be downloaded from https://www.visualstudio.com/downloads/. During a fresh installation enable "Desktop development with C++" workload and check box "Windows 10 SDK" to enable usage of the Graphical Device Interface (GDI) useful to display images in a window thanks to vpDisplayGDI class. After a fresh installation, start Visual Studio and create an empty C++ project to install the common tools for Visual C++ 2019.

If you already have Visual Studio Community 2019, you can check if "Desktop Development with C++" workload is activated and if "Windows 10 SDK" is enabled following instructions given here that we resume:

Find the Visual Studio Installer on your computer. Select Start, and then scroll to the letter V, where it's listed as Visual Studio Installer
Click or tap to start the installer, and then choose "Modify"
From the Workloads screen, check if "Desktop Development with C++" workload is activated and if "Windows 10 SDK" is enabled like in the following image
