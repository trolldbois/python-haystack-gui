# python-haystack memory forensics

[![Build Status](https://travis-ci.org/trolldbois/python-haystack-gui.svg?branch=master)](https://travis-ci.org/trolldbois/python-haystack-gui)
[![Coverage Status](https://coveralls.io/repos/trolldbois/python-haystack-gui/badge.svg?branch=master&service=github)](https://coveralls.io/github/trolldbois/python-haystack-gui?branch=master)
[![Code Health](https://landscape.io/github/trolldbois/python-haystack-gui/master/landscape.svg?style=flat)](https://landscape.io/github/trolldbois/python-haystack-gui/master)
[![pypi](https://img.shields.io/pypi/dm/haystack-gui.svg)](https://pypi.python.org/pypi/haystack-gui)

Quick Start:
============
You might want to look into the base libary [python-haystack](https://github.com/trolldbois/python-haystack/).

Run
 `haystack-gui`

Introduction:
=============

python-haystack is an heap analysis framework, focused on searching and reversing of
C structure in allocated memory.

this is an attempt at a GUI.

**This is not working right now**

Dump the process, then you can open it in the GUI::

    $ haystack-gui # ( and Ctrl-O , click click)
    $ haystack-gui --dumpname dumps/myssh.dump

You can the search a structure from the heap of that memory mapping.

You have to import your extensions before that to have them listed in
the search dialog.


Dependencies :
--------------

- python-haystack
- PyQt
