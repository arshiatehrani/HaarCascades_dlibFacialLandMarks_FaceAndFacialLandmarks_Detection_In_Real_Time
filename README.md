# HaarCascades_dlibFacialLandMarks_FaceAndFacialLandmarks_Detection_In_Real_Time

Haar cascades, first introduced by Viola and Jones in their seminal 2001 publication, Rapid Object Detection using a Boosted Cascade of Simple Features, are arguably OpenCV’s most famous object detection algorithm.
Sure, many algorithms are more accurate than Haar cascades (HOG + Linear SVM, SSDs, Faster R-CNN, YOLO, to name a few), but they are still relevant and valuable today.
One of the primary benefits of Haar cascades is that they are so fast that it’s hard to beat their speed.
The downside to Haar cascades is that they tend to be prone to false-positive detections, require parameter tuning when applied for inference/detection, and, generally, are not as accurate as the more “modern” algorithms we use today.
That said, Haar cascades are:
1.	An essential part of the computer vision and image processing literature
2.	Still used with OpenCV
3.	Still valid, mainly when working in resource-constrained devices when we cannot afford to use more computationally expensive object detectors


## Implementation

#### Cloning this repository onto your Computer

To install git:

    opkg install git

Then clone this repository using `git clone <git repo URL>`.

### How to run the Program

1. Install Python
2. Install OpenCV and it's related Libraries
3. Install Numpy
4. Install MatPlotLib (optional) but very useful
     For a complete step by step tutorial for setting up OpenCV visit :

     [OpenCV Setup Windows](http://docs.opencv.org/3.0-beta/doc/py_tutorials/py_setup/py_setup_in_windows/py_setup_in_windows.html#install-opencv-python-in-windows)

     [OpenCV Setup Fedora(Linux)](http://docs.opencv.org/3.0-beta/doc/py_tutorials/py_setup/py_setup_in_fedora/py_setup_in_fedora.html#install-opencv-python-in-fedora)

5. Add python from the installation directory to the set of Environment Variables ( for Windows). (Make sure you installed Python 2 and not 3)
6. From cmd or Powershell go to the directory where the Repository was cloned
7. Type :

   ` For each script, type the command from the batch file or, run the batch file. `

8. Congratulations! You now can see the results of the programs.

Enjoy!

# Real-time facial landmark detection with OpenCV, Python, and dlib

We will use dlib and OpenCV to detect facial landmarks in an image.
Facial landmarks are used to localize and represent salient regions of the face, such as:
•	Eyes
•	Eyebrows
•	Nose
•	Mouth
•	Jawline
Facial landmarks have been successfully applied to face alignment, head pose estimation, face swapping, blink detection, and much more.

## Necessary Libraries and Packages to install

### dlib

Developed by Davis King, the dlib C++ library is a cross-platform package for threading, networking, numerical operations, machine learning, computer vision, and compression, emphasizing extremely high-quality and portable code. The documentation for dlib is also quite fantastic.
From a computer vision perspective, dlib has several state-of-the-art implementations, including:
•	Facial landmark detection
•	Correlation tracking
•	Deep metric learning
•	Face alignment
•	Face recognition
•	Face verification
and many more.

### dlib prerequisites

#### Boost
Boost is a collection of peer-reviewed (i.e., very high quality) C++ libraries that help programmers not get caught up in reinventing the wheel. Boost provides implementations for linear algebra, multithreading, basic image processing, unit testing, and …

#### Boost.Python
As the name of this library suggests, Boost. Python provides interoperability between the C++ and Python programming languages.

#### CMake
CMake is a cross-platform open-source build system. It is used to build and test software.

#### X11/XQuartx
X11 is a UNIX-like operating system that is used to develop graphical user interfaces.

### Installing above packages on linux

6. From cmd or Powershell
7. Type :

   ` sudo apt-get install build-essential cmake `
   ` sudo apt-get install libgtk-3-dev `
   ` sudo apt-get install libboost-all-dev `
   ` pip install numpy `
   ` pip install scipy `
   ` pip install scikit-image `
   And finally, type :
   ` pip install dlib `

### How to run the Program

1. From cmd or Powershell go to the directory where the Repository was cloned
2. Type :

   ` For each script, type the command from the batch file or, run the batch file. `



Enjoy!

## Original Author

Adrian Rosebrock
Website :- [Pyimagesearch](https://pyimagesearch.com/)