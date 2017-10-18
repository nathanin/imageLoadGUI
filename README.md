# ImageLoadGUI

Simple interface for opening, viewing and saving cropped subsections of Whole Slide digital pathology images using the [openslide](openslide.org) python API. Built around summer 2015, since I couldn't find a good way to view SVS files without the ScanScope software. Major workflow limitation. Bad.


### Features
* Pop-up menu image selection
* Interface with the image pane by dragging a window to crop
* Refine the crop rectangle by specifying (top, top): (size, size)
    * Image pane rectangle should update accordingly
* Save the selected area to a new file in whatever formats suppored by `PIL`
* Multiple ways to quick-exit - even where you might not expect ;)
* **Tested with Aperio's SVS file type, should work for others... but info might not be as expected**

![Screenshot][ss]


### Some dependencies:
* Python 2.7
* numpy
* python-imaging-tk
* PIL
* Tkinter

### Planned improvements:
* Mouse-wheel zooming
* Zooming of any kind, really.

<!-- ### Possibly possible far-reaching goals:

* Web-facing interface
* Factor it and add a place for processing plugins
* Integration with histo-seg -->


### Contact
ing.nathany@gmail.com


[ss]: https://github.com/nathanin/imageLoadGUI/blob/master/screenshot.png
