# auto-build-RTK
Automate the building of OpenRTK for a Linux machine.
It simply follows the installation tutorial that can be found [here](http://wiki.openrtk.org/index.php/Main_Page#Step_0_-_Getting_ITK).

Requirements:
- C/C++ compiler
- Cmake 
- Git
- fftw
- wget

How to use it: 
- Create an empty directory that will hosts all the OpenRTK and ITK sources.
- Enter to this folder.
- Download this [file](https://raw.githubusercontent.com/dannylessio/auto-build-RTK/master/auto_build_RTK.sh) with Wget:<br>
  ```
  wget https://raw.githubusercontent.com/dannylessio/auto-build-RTK/master/auto_build_RTK.sh
  ```
  <br>
- Give the execution privileges to the .sh script.<br>
 ```
 chmod +x auto_build_RTK.sh
 ```
 <br>
- Execute it.<br>
  ```
   ./auto_build_RTK.sh
  ```
  <br>
- Enter the number of cores of your processor, this is a tip for speedup the compilation process.
- Hope, and take a long coffee.

