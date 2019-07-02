cutlist
=======


CutList plugin for Sketchup takes your model and produces a list of all selected components/groups and their dimensions helping you determine how much of each material you need to produce your design. It also has capabilities to layout these materials on stock sizes of material.


Two ways to install:

* Download the latest .rbz ( which is a zipped ruby file ) from the Sketchup extensions site
http://extensions.sketchup.com/content/cutlist and install through Sketchup :
Select Preferences on SketchUp Window menu (Window->Preferences), click on Extensions  and select "Install Extension".

* Then browse to and select the downloaded .rbz

* This will automatically unzip and install all necessary files in the correct locations for the version of Sketchup you are using.

or 

* you can go directly to Sketchup extension warehouse from within Sketchup: Select Extension Warehouse from the Window menu in Sketchup (Window->Extension Warehouse), search for cutlist and download and install.


# wine

There were made some efort in order to allow the use of cutlist installed in sketchup 2017 under wine.

Please see [WineHQ sketchup page](https://appdb.winehq.org/objectManager.php?sClass=version&iId=34500) for instruciont on sketchup 2017 
installation on Wine.

## Installation on sketchup under wine

Download this source code by git clone or whatever means you think it is better, then zip it's content in a file
and change it's extension to .rbz. 

After a successful installation of sketchup 2017 on wine, open the extension manager (Window > Extension manager)
and click on install extension then select the .rbz file.

Optionally you can just copy the files to the folder of your wine prefix in which it is installed your
sketchup or just creat a symbolic link to the main sr_cutlist.rb file and one to the sr_cutlist folder.
The folder may be located in the following location: 
~/<SKETCHUP_2017_PREFIX_FOLDER>/drive_c/users/username/Application\ Data/SketchUp/SketchUp\ 2017/SketchUp/Plugins/

