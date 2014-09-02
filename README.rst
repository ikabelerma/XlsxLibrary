XLSX Library for Robot Framework
================================

Introduction
------------
XlsxLibrary is a library for reading (and soon, writing) spreadsheets saved as .xlsx files.
If you need to read .xls files, you might be looking for XlsLibrary_.

XlsLibrary is a Robot Framework wrapper for the OpenPyXL_ package.

Usage guidelines can be found in the `Keyword Documentation`_.

Installation
------------
Since this is not a complete python package yet, there is no installation needed. Although the openpyxl package is a pre-requisite:

::

    pip install openpyxl

Just import XlsLibrary as a normal user library in your project. More information on importing user libraries in the `Robot Framework User Guide`_.

::

    *** Settings ***
    Library    XlsxLibrary.py


.. _Keyword Documentation: http://ikabelerma.github.io/XlsxLibrary/ExcelXLibrary.html
.. _OpenPyXL: https://pythonhosted.org/openpyxl/
.. _XlsLibrary: https://github.com/ikabelerma/XlsLibrary
.. _Robot Framework User Guide: http://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#using-physical-path-to-library
