face-recognition.js
=============

Simple Node.js API for robust face detection and face recognition. This a Node.js wrapper library for the face detection and face recognition tools implemented in <a href="https://github.com/davisking/dlib"><b>dlib</b></a>.

## Examples

### Face Detection

![face-got](https://user-images.githubusercontent.com/31125521/34471083-636f939a-ef3f-11e7-91e0-f4308abb8011.jpg)
![faces](https://user-images.githubusercontent.com/31125521/34500565-9670989e-f00b-11e7-8c2d-012aa72b2de1.jpg)

### Face Landmarks

![landmark5](https://user-images.githubusercontent.com/31125521/34471086-63a74358-ef3f-11e7-9fe8-641bc8a3a2dd.jpg)
![landmark68](https://user-images.githubusercontent.com/31125521/34471087-63c3118c-ef3f-11e7-9e7c-a741bef3f4b2.jpg)


### Face Recognition
![facerec](https://user-images.githubusercontent.com/31125521/34644195-fca4a3b6-f331-11e7-85c9-04adc9c4e413.jpg)

## Install

### Requirements
- cmake
- windows users will need VS2017 build tools (not Visual Studio 2017) -> https://www.visualstudio.com/de/downloads/

### Auto build
Installing the package will build dlib for you and download the models. Note, this might take some time.
``` bash
npm install face-recognition
```

### Manual build
If you want to use an own build of <a href="https://github.com/davisking/dlib"><b>dlib</b></a>:
- set DLIB_INCLUDE_DIR to the source directory of dlib
- set DLIB_LIB_DIR to the file path to dlib.lib | dlib.so | dlib.dylib

If you set these environment variables, the package will use your own build instead of compiling dlib:
``` bash
npm install face-recognition
```