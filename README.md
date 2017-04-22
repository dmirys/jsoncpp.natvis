jsoncpp.natvis
==============
It is a file, which sets some rules for Visual Studio debugger
and instucts it to visualize JsonCpp (https://github.com/open-source-parsers/jsoncpp) 
objects in a special manner.
With such visualizer reading of the debugging JSON values became
much easier, because of compact data representation.

![Example view on jsoncpp test JSON file](https://raw.githubusercontent.com/dmirys/jsoncpp.natvis/master/img/jsoncpp.natvis.png)

Supported Versions
------------------
I've tested it with jsoncpp 0.6.0-rc2 on Visual Studio 2015 SP3
and currently have no information could it be run on other versions.

How to install
--------------
There are several ways to deploy natvis file. The easiest one
is to copy jsoncpp.natvis to the %USERPROFILE%\My Documents\Visual Studio 2015\Visualizers.
You have to create Visualizaers folder if it does not exist.

Other methods are described in the following article:
https://msdn.microsoft.com/en-us/library/jj620914.aspx#Anchor_3

More information about creation of custom views
-----------------------------------------------
https://msdn.microsoft.com/en-us/library/jj620914.aspx
