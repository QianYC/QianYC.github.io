# change cmake version of ROS
### 2019/12/17

## cause
Today I got an Azure Kinect DK, and wanted to use it in ROS. However, the SDK of the camera required cmake later than 3.10, which is greater than the cmake I used to build and install ROS Kinetic, 3.5.1. To fix this, I installed cmake 3.15.6 from source code, but the catkin_make seemed to still use the older cmake. So my ROS might somehow 'bind' to the cmake 3.5.1. I searched the Internet and found nothing about changing cmake version of ROS.

## solution

1. ran **whereis cmake**, the output was
```
cmake: /usr/bin/cmake /usr/lib/cmake /usr/local/bin/cmake /usr/local/lib/cmake
```

2. checked the cmakes' version by **/usr/bin/cmake --version** and **/usr/local/bin/cmake --version**

3. copied the 3.15.6 cmake to replace the 3.5.1 cmake: **sudo cp /usr/local/bin/cmake /usr/bin/**

4. catkin_make again, failed. Checked the error message:
```
CMake Error: Could not find CMAKE_ROOT !!!
CMake has most likely not been installed correctly.
Modules directory not found in
/usr/share/cmake-3.15
```

5. renamed /usr/share/cmake-3.5 to /usr/share/cmake-3.15: **mv /usr/share/cmake-3.5 /usr/share/cmake-3.15**

6. now the ROS uses cmake 3.15.6 to build nodes!
