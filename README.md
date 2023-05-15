# Image-reading-writing-and-saving-with-opencv-in-python
Intrudiction to Opencv in Python 


![Opencv- Python Programming ](https://github.com/ElectronicEngineerr/Image-reading-writing-and-saving-with-opencv-in-python/blob/main/cars.jpg)

OpenCV (Open Source Computer Vision Library) is an open source library used for computer vision and image processing framework. It is written in the C++ programming language and has a build API with languages ​​such as Python, Java and MATLAB.

OpenCV has a large collection of functions that allow you to perform many different operations. For example, you can perform operations such as viewing, reading and writing, converting, playing, feature extraction, object detection, face recognition, stereo conversation, camera tracking. As such, it is a library used in image processing, computer vision, and machine learning projects.

OpenCV can be used with many different compilers and IDEs. Popular ones among these include compilers and development environments such as GCC (GNU Compiler Collection), Clang, Visual Studio, Xcode, and Eclipse. These compilers and IDEs provide support for different tablet systems and platforms.

A few of the key features of OpenCV:

Fast and efficient: OpenCV enables highly efficient image processing thanks to optimized C++ code.
Broad functionality: The library includes and includes many different image processing systems, making it easy to complex.
Cross-platform support: OpenCV can run on different tablet systems and platforms such as Windows, Linux, macOS and Android.
Community support: OpenCV has a large user community, which is constantly adding new features, fixing bugs and sharing resources.
Common uses for OpenCV include object detection, image processing-based automation, industrial applications, therapeutic imaging, robotics, security systems, and augmented reality.

!([](https://github.com/ElectronicEngineerr/Image-reading-writing-and-saving-with-opencv-in-python/blob/main/opencv_tutorial_header.jpg)


I am using the Pycharm compiler while developing my projects in the opencv library. I recommend you too. A platform with an easy and beautiful interface. You can download the Pycharm compiler by searching on google and downloading it easily from its home page and reading the library downloads from the necessary platforms. Generally, we will use opencv-python, numpy, matplotlib libraries in projects. But in this repository I want to show you how to read an image, how to print it and how to save it.

![PYCHARM ](https://github.com/ElectronicEngineerr/Image-reading-writing-and-saving-with-opencv-in-python/blob/main/PyCharm_IDE.jpg)


-In this application, it reads a file using the `cv2` (OpenCV) library, displays the image, and then looks at the same image in a different file.

-First, with the `cv2.imread('giris.jpg')` contest, we read a photo named "giris.jpg" from disk and assign it to a variable named image. The imread function reads the image BGR color format and represents that image as a NumPy array.

-Next, we show the image creatures on the screen using imshow organs with the `cv2.imshow('Input Image', image)` cutoff. The first parameter specifies the name of the window and the second parameter represents the image to be displayed.

-Next, the `cv2.waitKey(0)` command keeps the onscreen window open until a key is pressed. A value of 0 represents waiting for an infinite amount of time. This is how the computer works.

-Next, Using the `cv2.imwrite` command, we save the image to a file named "cikis.jpg". This happens before the cv2.destroyAllWindows() command.

After running the program, you will see the image on the screen and the window will close when you press any key. Next, the same image will be saved in a file named "cikis.jpg". Thus, you can both display the image on the screen and save it to a file on disk.

-Next, the destroyAllWindows function is a function in the OpenCV library to close a window. This function closes all windows opened for viewing.

The "destroyAllWindows" statement you mention specifically for the Windows OS is a common command when using OpenCV in Python. This command closes all open windows and frees resources.

For example, using the `cv2.destroyAllWindows()` command closes all open windows and ensures that the program terminates properly.


-Finally, we save the image manager to a file named "cikis.jpg" using the `cv2.imwrite('cikis.jpg', image)` cutout and imwrite files.
After running the program, it will display the image named "entry.jpg" in a window. When you press any key, the window will be closed and the same image will be saved in a file named "cikis.jpg".

This application is just an example to perform the basic image manipulation method using OpenCV. With the results of OpenCV you can discover many more functions and methods and use them to develop more complex projects.


Example code in Pycharm:


import cv2

# Reading to image
image = cv2.imread('giris.jpg')

# showing to image
cv2.imshow('Giriş Görüntüsü', image)
cv2.waitKey(0)
# saving to image
cv2.imwrite('cikis.jpg', image)

# close to all windows
cv2.destroyAllWindows()

