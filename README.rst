==================================================================
OpenCV (Open Source Computer Vision) Haar Cascade Face Detection
==================================================================

Prerequisite(s) Hardware:
-------------------------

- Raspberry Pi 3 Model B+
- HDMI -> TV/Monitor Screen
- Micro USB Power Cable -> 2A-5V Power Adopter
- USB Keyboard
- Pi Camera or USB Camera

Prerequisite(s) Software:
-------------------------

- Python 3.5>
- pip
- numpy
- Open CV
- imutils
- PIL

.. _Prerequisites Installation Guide: https://github.com/ammar-khan/raspberry-pi-3-model-b-plus

`Prerequisites Installation Guide`_

Introduction:
-------------
This is a very basic tutorial to learn OpenCV haar cascade face detection on Raspberry Pi 3 Model B+ efficiently.
This example is using http streaming which make it easy to preview in browser.

Configuration:
--------------
You need to change configuration files as per your environments:

- ``src/common/package/config``
- ``src/opencv/package/config``

Execute:
--------
>>> python3.5 main.py

Streaming:
----------
Open ``http://localhost:8000`` in browser

Copyright & License
-------------------

- Copyright (c) 2018, Ammar Ali Khan
- License: MIT

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
