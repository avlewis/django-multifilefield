django-multifilefield
=====================

This is django implementation for html5 multiple file upload.
All files data damps to json object for saving into the database.

Installation
============
::
    $ pip install django-multifilefield

Usage
=====
::
    >>from multifilefield.models import MultiFileField
    or
    >>from multifilefield.forms import MultiFileField

    And then you can use this fields as usual for forms and models:

    >>file = MultiFileField()

All your saved data - it's a regular File objects and all his properties and methods
are available for this objects.
