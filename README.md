# Introduction

Author: [dreampuf](https://github.com/dreampuf/)
Maintainer: [Xe](https://github.com/Xe)

[GraphvizOnline](https://github.com/dreampuf/GraphvizOnline) could let you debug the graphviz languages online. This version has been edited to run as a progressive web app with full offline support.

See [here](https://graphviz.christine.website) for a live demo.

# How This was Implemented

- [viz.js](https://github.com/mdaines/viz.js) - This repo has compiled graphviz(C) to javascript via [emscripten](https://github.com/kripken/emscripten).
- [ACE-editor](http://ace.ajax.org/) - An amazing online editor.
- [Service Workers](https://github.com/Xe/GraphvizOnline/blob/master/sw.js)

# License

GraphvizOnline is licensed under a BSD-3 license. The dependencies are:

- [viz.js](https://github.com/mdaines/viz.js/blob/master/LICENSE) MIT
- [ACE-editor](https://github.com/ajaxorg/ace/blob/master/LICENSE) BSD-2


