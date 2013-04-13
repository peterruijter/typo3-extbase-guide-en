.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM. ÄÖÜäöüß

.. include:: ../Includes.txt

Introduction
==========

TYPO3 programming with piBase is getting more and more complicated and unstructured. There is no clear strategy for programming. So that TYPO3 developers started to search for a new System for TYPO3. There are a lot of frameworks but everyone with own deficites. The desicision was clear, we need a own framework. This was the beginning of FLOW3.

Dieses FLOW3 wird bzw. ist schon die Basis des neuen TYPO3 5, welches derzeit unter
dem Namen Phoenix durch die TYPO3-Gemeinde wandert. Da FLOW3 eine völlig neue Basis
und auch völlig anders aufgebaut ist, kann FLOW3 nicht von jetzt auf gleich den
derzeitigen TYPO3 4.3 Core ersetzten. Damit aber schon heute Extensions auf Basis des
neuen Systems programmiert werden können, hat man Teile des FLOW3-Systems als
Sysextension. So entstanden die Extensions extbase und fluid. Auf extbase basierende
Extensions laufen auf TYPO3-Versionen ab 4.3 und können später mit nur wenig
Änderungen auf das TYPO3 5 System portiert werden.