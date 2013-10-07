Coda 2 - jQuery Custom Syntax Mode
==================================

This repository contains a custom syntax mode for jQuery in Coda 2. The mode includes the following:
* Standard Javascript syntax highlighting
* jQuery code completion
* A snippet clip set for standard jQuery and noConflict()

Installation
------------
**To install this mode automatically** simply download the files, unzip them and open the .mode file with Coda 2. You can do the same with the clips - see note below.

**To install this mode manually** you must navigate to the Coda 2 install directory and copy the .mode file into the Modes folder.

Open Terminal and run the following command:

    cd ~/Library/Application\ Support/Coda\ 2/

Then, to open the directory in Finder enter this command:

    open .

When Finder opens, you will see multiple folders. Drag jQuery.mode into the Modes folder. 

If you would like to use the jQuery clips you can also add them here by dragging the jQuery.clips file into the Clips directory. 

Clip Instructions
-----------------

Clips are default functionality within Coda. I have created a few snippets to help speed up the development process. To use a clip simply type the clip shortcode and **press [TAB]**. You can also open the clips sidebar from Window > Clips and drag a clip to the document.

|Clip Shortcode|Output|
|--------------|------|
| $# | Creates a jQuery ID Selector |
| $. | Creates a jQuery Class Selector |
| $doc | Creates a function that fires when the DOM has loaded |
| $win | Creates a function that fires when the window has loaded |
| $ajax | Creates a standard AJAX call |
| $plugin | Creates a plugin template |

**NOTE**: If you are using jQuery in noConflict mode simply prepend a `j` before the clip. For example `$doc` would become `j$doc`.

If you have any additions you would like to make, you can either comment here, send a pull request or contact me on my website: www.matthewray.com

