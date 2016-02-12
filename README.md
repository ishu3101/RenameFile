RenameFile
==========

A Sublime Text 2 Plugin that lets you rename currently opened files.

Installation
============

The plugin can be installed manually using one of the following
methods.

Using Git
---------
Go to your Sublime Text Packages directory and clone the repository
using the command below:

    $ git clone https://github.com/ishu3101/RenameFile

Manual Download
---------------

* Download the files using the .zip download option
* Unzip the files (and rename the folder to RenameFile if needed)
* Copy the folder to your Sublime Text Packages directory

Usage
-----

Add the following to your `User Key Bindings` Preference file.

`{ "keys": ["f2"], "command": "rename_file", "args": { "paths": ["$file"] } }`

Now when you want to rename the currently opened file, press the key combination you entered above (`f2` in this example).