.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. ==================================================
.. DEFINE SOME TEXTROLES
.. --------------------------------------------------
.. role::   underline
.. role::   typoscript(code)
.. role::   ts(typoscript)
   :class:  typoscript
.. role::   php(code)

.. include:: Images.txt

Introduction
============



What does it do?
----------------

This extension implements the jquery supersized plugin - full screen
background slideshow (http://buildinternet.com/project/supersized/ -
MIT License / GPL License // Github: https://github.com/buildinternet/supersized).

- Can be used for a full sreen background / background slideshow and a
  background banner / banner slideshow.

- based on Extbase and Fluid

- Fully configurable via TS and Flexform (Frontend plugin).

- Realized with easy adaptable fluid templates for header data
  (javascript / css) and html output.

- Depending on the settings in TS and/or the frontend plugin the fluid
  templates automatically changes the header data (javascript / css) and
  html output to the needed code. Normally you don't have to adapt the
  fluid templates.

- The extension includes the complete Supersized plugin code v3.2.7,
  which includes the jQuery Library v1.7.2 .

- The Supersized plugin (from v1.1.0) now works properly even with the
  newest jQuery Library (v3.3.1 at the moment). Some little modification
  in the supersized.3.2.7.js were necessary. So the jQuery Library
  v3.3.1 is included too in this extension and set to default in typoScript.

- Some live demos: `http://demo.frankfrewer.de/supersized/
  <http://demo.frankfrewer.de/supersized/>`_

- frsupersized now on Github: https://github.com/ffrewer/frsupersized

Since v0.2.0 this manual is implemented with ReST (http://wiki.typo3.org/ReST). The documentation file 'manual.sxw' is not provided anymore. The new manual was produced with the sphinx extension - many thanks to the author of this extension, Xavier Perseguers.


Screenshots
-----------

Supersized Demo.
^^^^^^^^^^^^^^^^

|img-3|

|

Plugin Settings "General"
^^^^^^^^^^^^^^^^^^^^^^^^^

|img-4|

|

Plugin Settings "Full background"
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

|img-5|

|

Plugin Settings "Slideshow"
^^^^^^^^^^^^^^^^^^^^^^^^^^^

|img-6|

|

Plugin Settings "Banner"
^^^^^^^^^^^^^^^^^^^^^^^^

|img-7|

|


