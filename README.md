# Dockerfile for Android Projects

This is a Dockerfile to make minimum images for Android projects.
No `ant`, `maven`, nor `android-ndk` are included.

## Included

* OpenJDK 8
* Android SDK
* Android Support Libraries
* Google Play Services

## Maintainance

* Just rebuild it for minor updates
* Update components for major updates
  * You can find component ids by `android list sdk --all --extended`

# License

The MIT License.

Original work Copyright (c) 2015 FUJI Goro <g.psy.va+github@gmail.com>.
Modified work Copyright (c) 2016 Phillip Warren <phillip.warren@gmail.com>.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION

