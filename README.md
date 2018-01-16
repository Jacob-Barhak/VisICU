Visualize Intensive Care Unit Data
==================================

This project visualizes Intensive Care Unit (ICU) data for a single patient located in [UCI, Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/ICU). 

This work Handles: 

* Data Import – including cleaning and normalization
* Data Visualization – with the intent of explaining phenomenon that will improve understanding 
* Detecting outliers – the system uses several machine learning techniques to provide visual cues to the human viewer

The code and data here is explained in the paper titled: "Visualization and Pre-Processing of Intensive Care Unit Data Using Python Data Science Tools"


USAGE:
------

Download all files from this repository to a directory of choice and open a command prompt

Execute the command:
jupyter notebook VisICU.ipynb

From the menu select:
Cell -> Run Cells

The script will run and output the file:
VisualICU.html

Open this output file in a web browser, please make sure you are connected to the Internet to view the graphics.



DEPENDENCIES:
-------------

Dependant libraries are: pandas version 0.20.3, bokeh version 0.12.10, sklearn version 0.19.1. numpy version 1.13.3.

This code was tested on Windows 10 with python 2.7.14 on Anaconda 64 bit version 5.0.1

It is recommended you use Anaconda, yet other python environments and library versions may work as well.



FILES:
------

### Application file:
* README.md: the file you are reading now
* VisICU.ipynb: the jupyter notebook python code that creates the visualization


### Data Files copied from [UCI, Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/ICU):
* Domain-Description: Background information with lab data description, edited in the file Domain-Description-Edited.txt below
* Flowsheet-Data: text file with time series data from flowsheet
* Lab-Data: text file with time series data from lab
* Monitor-Data: text file with time series data from monitor
* Monitor-Data-Codes: text file with code description with units, edited in the file Monitor-Data-Codes-Edited.txt
* Patient-Description: text file with brief description of patient and treatment
* README-ICU: Data readme file - contains some obsolete email addresses and outdated material

### Modified Data Files Used by Codes
* Domain-Description-Edited.txt - Text file edited from Domain-Description to allow reading Lab codes by the program
* Monitor-Data-Codes-Edited.txt - Text file edited from Monitor-Data-Codes to allow reading Monitor codes by the program

### Output file
* VisualICU.html - the output of running VisICU.ipynb - download and open in browser to view visualization


VERSION HISTORY:
----------------
Development started on 27-Jul-2017.
Uploaded to Github on 17-Jan-2018 - no version number assigned


DEVELOPER CONTACT INFO:
-----------------------

Please pass questions to:

Jacob Barhak Ph.D.
Email: jacob.barhak@gmail.com
http://sites.google.com/site/jacobbarhak/



ACKNOWLEDGEMENTS:
-----------------

Thanks to Tadashi Kamio for the email correspondence that resulted in this work.


LICENSE
-------

The Data Files were extracted from the [UCI, Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/ICU) the only requirement stated for those files was attribution according to this [citation policy](https://archive.ics.uci.edu/ml/citation_policy.html)

The jupyter notebook python code is under the GPL License.

Copyright (C) 2018 Jacob Barhak
 
This file is part of the VisICU . VisICU is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

VisICU is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

See the GNU General Public License for more details.


