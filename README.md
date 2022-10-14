
Name:F1 Pitstop prediction using Time ditributed LTSM regression
==================================================================


Description
============



 The project as you see it works to calculate the racing line of a particular corner of an f1 track.It's uses can include F1 TV graphics and racing games that are easily moddable such as Asseto Corsa.
The racing line calculator also works to caluclate the racing line for any new track mathematically isntead of using machine learning.

The project also includes the prediction for whether a team should pit or not depending on the number of laps done on the stint, circuit etc.Used time series LTSM ( a type of nerual network) to create this.

Requirements
==============

geopandas 
geojsonio
matplotlib
glob
numpy
shapely
pandas

recommend using the newest versions

To check your version simply paste and edit this in your terminal

PackageName.__version__

OR

Run this code in your development environment

import Package
print(Package.__version__)

Acknowledgements
=================

Refer to this link for the centre lines of the used tracks

https://github.com/TUMFTM/racetrack-database

License
========
I have used the MIT Lisence for this project

Copyright 2022 Parth Khurana

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Project status
===============

Completed the prit stop predction model, but would still appreciate if anyone is willing to collab and add frequent commits.

Working on displaying the geojson output on an html page.





