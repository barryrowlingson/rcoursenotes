Spatial Analysis in R Workshop
===============================

Preparing Yourself (and your computer)
-----------------------------------------

For the workshop you will need a computer running a recent version of
R and some add-on packages that can be downloaded from the
internet. Sample data for exercises can be downloaded on the workshop
day.

Feel free to bring along some of your own data to play with during
the workshop. 


Installing Base R
-------------------

R runs on Windows, Mac, and Linux computers. If you have any problems
installing R then first check the documentation on the R web site
(www.r-project.org).

### Windows

Download the exe file installer from here and run it:

http://cran.rstudio.com/bin/windows/base/

### MacOS

Get the latest .pkg file installer from here:

http://cran.rstudio.com/bin/macosx/

### Ubuntu Linux

The official instructions here:

http://cran.rstudio.com/bin/linux/ubuntu/

leave a bit to be desired. There are some clearer instructions here:

http://craig-russell.co.uk/2012/05/08/install-r-on-ubuntu.html


Interfaces
------------

Now you should have a basic R system.

For beginners and all Windows users I recommend the RStudio IDE, which
comes with a graphical user interface with an editor and data
browser. You need to install R first, and then get the RStudio IDE
from here:

http://www.rstudio.com/ide/download/desktop

The RStudio IDE works on Windows, Mac, and Linux platforms.


Add-on packages
-----------------

### Windows

Start R (or start RStudio) and from the R prompt, use
'install.packages' to get the packages we need:

> install.packages(c("sp","rgdal","raster","rgeos","ggplot2","maptools"))

That should also pull in a lot other dependent packages. If that all
works without error messages (you may have to ignore some warnings)
then everything should be all set.


### MacOS

MacOS packages are supplied in the same way as Windows packages. Start
R (or RStudio), and do:

> install.packages(c("sp","rgdal","raster","rgeos","ggplot2","maptools"))



### Linux

Installing additional packages in Linux can be tricky. You can either:

 * add Michael Rutter's PPA (personal package archive)
   https://launchpad.net/~marutter/+archive/c2d4u to your sources and
   install via Ubuntu's package management

 * install development tools and libraries and install from source
   code via install.packages.

