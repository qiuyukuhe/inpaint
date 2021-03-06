# Inpaint

**Inpaint** is a C++ library providing implementations of image inpainting and image completion methods. Image inpainting is the process of recovering or restoring image regions in a way that is non-detectable for an observer who does not know the original image. 

While inpainting refers to restoring rather small regions such as scratches and other video artefacts, image completion deals with removal / restoring of large image parts.

**Inpaint** focuses on the task of object removal and is therefore optimized to work with large areas of reconstruction. Below is a side-by-side view of two images. On the left the original image, on the right the modified image as produced by **Inpaint**, after the user selected the rope to be removed.

| Original        | Inpainted     |
| :-------------: |:-------------:|
| ![Original Image](/photos/bungee.jpg?raw=true) | ![Inpainted image](/photos/bungee_criminisi.png?raw=true) |


## Building from source
To build **Inpaint** from source you need the following prerequisites
 - [CMake](www.cmake.org) - for generating cross plattform build files
 - [OpenCV](www.opencv.org) - for image processing related functions
 
Although **Inpaint** should build accross multiple platforms and architectures, tests are carried out on these systems
 - Windows 7/8 MSVC10 x86

If the build should fail for a specific platform, don't hestitate to create an issue. I'm also happy to accept any pull requests.

## License
```
   Copyright Christoph Heindl 2014

   Inpaint is free software: you can redistribute it and/or modify
   it under the terms of the GNU General Public License as published by
   the Free Software Foundation, either version 3 of the License, or
   (at your option) any later version.
   
   Inpaint is distributed in the hope that it will be useful,
   but WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
   GNU General Public License for more details.
   
   You should have received a copy of the GNU General Public License
   along with Inpaint.  If not, see <http://www.gnu.org/licenses/>.
```
