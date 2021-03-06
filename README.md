# zed-matlab

**This sample is designed to work with the ZED stereo camera only and requires the ZED SDK. For more information: https://www.stereolabs.com**

It demonstrates how to use most of the ZED SDK functionalities with Matlab.

**Warning :**
 - This sample is not designed to operate in real time

This sample displays the both left and right images of the ZED as well as the normalized depth map.
This sample also retrieve the depth information and then compute thru Matlab the depth histogram.
Since we added tracking skills to the SDK, the position of the ZED camera is also displayed.

## Build the program
To get more detailed instructions (especially for Windows) check out the  [documentation](https://www.stereolabs.com/blog/index.php/2015/09/11/how-to-use-the-zed-sdk-with-matlab/).

Open a terminal in zed-matlab directory and execute the following command:

    $ export MATLAB_ROOT=/usr/local/MATLAB/R2012b # Change this with your actual Matlab path
    $ mkdir build
    $ cd build
    $ cmake ../src
    $ make
    $ make install


##Run the program
In the matlab directory, open the file ZED_Camera.m with Matlab and press run.


**Quit :**
Press any key to exit the program.

![](main.png)
