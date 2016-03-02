Element Sensor
===================

Element Sensor detects html element size change by constructing subtle html structure inside target element, so that it indirectly triggers scroll event when resized.

The latest version also compatible with older browesrs by checking intermittently.

Element Sensor is stolen from Marc J. Schmidt's [Element Queries component](https://github.com/marcj/css-element-queries), I refactored the code to make it consume less memory and be slightly faster by reduce the number of function instances. Also by separate it from the original repo, it will be much easier to be reused.

Usage
=====

`new ResizeSensor(targetElement, callback)`

License
-------
MIT license. Copyright [Marc J. Schmidt](http://marcjschmidt.de/).
