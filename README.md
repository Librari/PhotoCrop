# PhotoCrop
[![Build Status](https://travis-ci.org/albinmathew/PhotoCrop.svg?branch=master)](https://travis-ci.org/albinmathew/PhotoCrop)  [![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-PhotoCrop-brightgreen.svg?style=flat)](http://android-arsenal.com/details/1/2046) 

![alt text](https://raw.githubusercontent.com/albinmathew/PhotoCrop/master/screenshots/pic1.png)

The PhotoCrop is an image cropping tool. It provides a way to set an image in XML and programmatically, and displays a resizable
crop window on top of the image.Calling the method getCroppedImage() will then return the Bitmap marked by the crop window.

It gives the feature of cropping an image where image can resize,zoom whereas cropper window remains static similar to facebook
Users can get both circularly cropped and rectangular cropped images.Cropping window also takes circular and rectangular shapes.

## Features
- Out of the box zooming, using multi-touch and double-tap.
- Scrolling, with smooth scrolling fling.
- Works perfectly when using used in a scrolling parent (such as ViewPager).
- Allows the application to be notified when the displayed Matrix has changed. Useful for when you need to update your UI based on the current zoom/scroll position.
- Allows the application to be notified when the user taps on the Photo.


# Credits

The library is made by combining two libraries

1. https://github.com/chrisbanes/PhotoView
2. https://github.com/edmodo/cropper

## License

    Copyright 2015 Albin Mathew

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
