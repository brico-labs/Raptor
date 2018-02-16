# Raptor

This is the Raptor project repository

A followline robot with N20 motors, 16340 batteries, arduino pro micro and TB6612 or Raspberry Pi Zero.

This repository evolved
from [fstdp/openscad](https://github.com/fstdp/openscad), all openscad
files from the old repo are now on `openscad_misc`directory

# META

This repo
uses [BricoLabs KiCAD](https://github.com/brico-labs/bl_kicad_library)
Library as a submodule.

When cloning this repo you must:

~~~~{bash}
git clone https://github.com/brico-labs/Raptor
cd Raptor
git submodule init
git submodule update
~~~~

or just with one command:

~~~~{bash}
git clone --recursive https://github.com/brico-labs/Raptor
~~~~


# openscad_misc directory

variety of OpenSCAD things from different projects

- SpeedyGonZero, rearwing & ballcaster38 for Raspberry Pi Zero robot


# License MIT

Copyright 2017 Félix Sánchez-Tembleque

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
