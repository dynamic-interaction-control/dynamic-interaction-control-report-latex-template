DIC Report LaTeX template
==========================

This repository contains the template for DIC reports. 
It also contains an example of a LaTeX CMake-based build system
using [UseLATEX](http://www.cmake.org/Wiki/CMakeUserUseLATEX).
Using CMake it is possible to avoid some limitations of LaTeX builds,
for example enabling out-of-source builds.

### Build the Document

### Linux/OS X
~~~
git clone https://github.com/dynamic-interaction-control/dynamic-interaction-control-report-latex-template
cd dynamic-interaction-control-report-latex-template
mkdir build
cd build
ccmake ..
make pdf
~~~

### Dependencies 

For building the document you need CMake, LaTeX and also some additional LaTeX packages.
Depending on you operating systems there are different ways to obtain the required software.

#### Windows 


#### OS X


#### Debian/Ubuntu
~~~
sudo apt-get install cmake texlive-latex-recommended texlive-fonts-recommended texlive-latex-extra texlive-publishers texlive-science
~~~
