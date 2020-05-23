# fast_ellipse_detector
This is the implementation in C++ of the paper: 'A fast and effective ellipse detector for embedded vision applications'.
It runs on Ubuntu 16.04 with OpenCV 2.4.13.  

Original author: mikispace (https://sourceforge.net/projects/yaed/)

Michele Fornaciari, Andrea Prati, Rita Cucchiara, 
"A fast and effective ellipse detector for embedded vision applications", Pattern Recognition, 2014

(http://www.sciencedirect.com/science/article/pii/S0031320314001976)

### How to compile:

- Linux
```sh
g++ Main.cpp EllipseDetectorYaed.cpp common.cpp -o ellipse_det -std=c++11 `pkg-config --cflags --libs opencv`
```
- Windows
```sh
g++ main.cpp -o demo -I C:\\OpenCv2\\include -L C:\\OpenCv2\\bin -llibopencv_core340 -llibopencv_highgui340 
```

### How to run:

```sh
./ellipse_det
```
