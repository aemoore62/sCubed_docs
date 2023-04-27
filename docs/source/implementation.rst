Implementation
=====

Here, we relay key knowledge about how sCubed is implemented and in a non-technical manner that is accessible to both users and developers.

Data types
------------
To promote trustworthy information, sCubed applies data validation and value formatting to every column in the sCubed Sheets. In Google Sheets, 
data validation and value formatting (called *Number* format) perform two different roles: 

* Data validation places constraints on what value can be entered into a cell. 
* Value formatting affects how the entered value is displayed. 

Often, when developers specify data types we often specify them based on a combination of the "thing" that we are describing and the attribute (column), e.g. the ``name`` 
attribute of ``Person`` has a data type of string or, more specifically, variable character with a maximum length of 255 characters. 

In the current implementation of sCubed, we assign data types based on a combination of the *sheet* and the column, not the "thing" and the column. For
example, the column ``material_supplier`` in the ``conceptDefinition`` Sheet may be used to associate an organization with multiple different "things" like a batch of cells, a container,
or a chemical substance. In this example, we reuse the ``material_supplier`` for all types of items. By reusing columns where viable, we reduce the 
total number of cells in the Sheets. (At the time of writing, Google Sheets supports a `maximum of 10 million cells or 18,278 columns for spreadsheets [files] <https://support.google.com/drive/answer/37603?sjid=6546980186700351095-NA>`_.)

.. note::
   The precursor to sCubed included a MySQL database so many of the data types used in sCubed were originated to be compatible with a relational database.

