.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM. ÄÖÜäöüß

.. include:: Includes.txt

.. _start:

======================================================
Offizieller TYPO3 Extbase Guide (Entwurf)
======================================================

:Author:          Stefan Frömken <froemken@gmail.com>
:Buildinfo:       `Make folder <_make>`_
:Copyright:       2013 up to now
:Description:     ...
:Language:        de
:License:         `CC BY-SA 3.0 <http://creativecommons.org/licenses/by-sa/3.0/>`_
:Rendered:        |today|

License
=======

`CC BY-SA 3.0 <http://creativecommons.org/licenses/by-sa/3.0/>`_ 
Creative Commons Attribution-ShareAlike 3.0 Unported.
You are free
- to share: to copy, distribute and transmit the work
- to remix: to adapt the work
- to make commercial use of the work

Extbase
=======

What is Extbase?
----------------

Extbase is a framework for TYPO3 extension development. It was introduced with
TYPO 4.3 in 2009 and is bound to entirely replace the classic way of writing
TYPO3 extension (pibase). Most important it is a gateway for TYPO3 4.x/6.x to
version Phoenix as it is a backport of FLOW3 technology.

Should I use Extbase?
---------------------

If you develop an extension for TYPO3 you should most definitely use Extbase.
The days of piBased extensions are numbered. Extbase gives you the benefit of a
modern, clear and highly structured way of PHP development with a hidden bonus:
If you know Extbase, getting into FLOW3 will be much, much easier for you. Another
bonus: Porting Extbase extensions to Phoenix will be a walk in the park, whereas
porting a piBased extension to Phoenix will be incredibly laborious if possible at
all, and pobably a very bad experience for everyone involved.

How do I get started with Extbase?
----------------------------------

* You should definitively check out the Extbase documentation section.
* The TYPO3 extension repository (TER) already holds lots of extensions based on
  Extbase, inspect the code.
* Also check out how to get Extbase support.

Want to contribute?
-------------------

Do you want to take part in making Extbase, TYPO3, and the world an even better
place/project? We would love to welcome you to the team if you want to contribute
in a substantial way. Click here for more info.

TYPO3 Extbase
=============

In diesem Guide zeigen wir Euch, wie Ihr eine einfach Extbase Extension erstellen könnt und erklären Euch die
wichtigsten Objekte Schritt für Schritt.

**Inhaltsverzeichnis**

.. toctree::
   :maxdepth: 1
   :titlesonly:
   :glob:

   FirstExtbaseExtension
   ExtendExtbaseExtension
   Step1Introduction/Index
   Step2SystemCheck/Index
   Step3Documentation/Index
   Targets