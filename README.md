Coda 2 - jQuery Custom Syntax Mode
==================================

This repository contains a custom syntax mode for jQuery in Coda 2. The mode includes the following:
* Standard Javascript syntax highlighting
* jQuery code completion
* A snippet clip set for standard jQuery and noConflict()

Installation
------------
To install this mode you must navigate to the Coda 2 install directory and copy the .mode file into the Modes folder.

Open Terminal and run the following command:

    cd ~/Library/Application\ Support/Coda\ 2/

Then, to open the directory in Finder enter this command:

    open .

When Finder opens, you will see multiple folders. Drag jQuery.mode into the Modes folder. 

If you would like to use the jQuery clips you can also add them here by dragging the jQuery.clips file into the Clips directory. If you use jQuery in noConflict mode, only drag the jQuery_NoConflict.clips file into the Clips directory, not both. If you dont know whether or not you are using jQuery in noConflict mode, you are probably not using noConflict - just use the standard jQuery.clips file.

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
| $equalheight | Creates a snippet that makes all selected elements the same height (the largest height element) |

