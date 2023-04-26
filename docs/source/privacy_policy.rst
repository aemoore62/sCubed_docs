Privacy policy
=====
The sheets used in sCubed are implemented using Google Sheets. 

The sCubed custom menu is made available as a Google Sheets add-on.

The dynamic responses in sCubed are enabled by an `installable, onEdit() trigger <https://developers.google.com/apps-script/guides/triggers/installable>`_, 
which sCubed does not install until the user selects the item ``Install onEdit trigger`` from the sCubed add-on menu.

What authorizations and permissions are required?
-------
When you install sCubed, you will be prompted to authorize certain permissions:
* *View and manage your spreadsheets in Google Drive* is required for sCubed to create and configure Sheets (tabs) in the active spreadsheet (file)
and evaluate the Sheets in the active spreadsheet.
* *Display and run third-party web content in prompts and sidebars inside Google applications* is required for sCubed to display the form that 
autopopulates `reporting workflows and specifications <https://scubed-docs.readthedocs.io/en/latest/overview.html#reporting-workflows>`_.

What happens when I configure the sheets?
-------
When you select to configure the sheets, sCubed will add Sheets (tabs) to the active spreadsheet (file), if the necessary sheets are not present. 
With the four or five standard sCubed Sheets in the active file, configuration will
* add column names, add new columns as needed, and remove empty columns;
* apply data validation, conditional formatting, and value formatting (called `Number` format);
* add a note to the first cell in each column.

What happens when I auto-populate a reporting workflow or specification?
-------
When you use the form to auto-popoulate a reporting workflow or specification, sCubed will **insert values** into the active sheet. The inserted values are 
values that you entered into the form and values that were previously entered for the selected reporting workflow and/or specification.

What happens when I select `Change view` from the add-on menu?
-------
Change view will display columns in the active sheet, hide columns in the active sheet, or do nothing based upon the value in the active cell. sCubed 
determines what columns to display and hide based on the value in the active cell and the `framework <https://ssquared-docs.readthedocs.io/en/latest/index.html>`_ 
used by sCubed.

What happens when I make a mini table?
-------
If the conditions for a mini table are satified, sCubed will **insert** a globally unique ID into two columns in the active sheet that act as helpers 
to organize mini tables. You will the background color of cells change; this results from the conditional formatting that was applied upon configuring 
the sheets.

What does the installable onEdit trigger do?
-------
The optional installable onEdit trigger enables sCubed Sheets to dynamically respond to edits, including
* hiding and showing columns and
* initiating and preventing `mini tables <https://scubed-docs.readthedocs.io/en/latest/overview.html#mini-tables>`_. 

.. warning::
    The onEdit trigger will **delete** the value in the *active cell* if valid values are not present to support a valid record based upon the
    `framework <https://ssquared-docs.readthedocs.io/en/latest/index.html>`_ used by sCubed.

    If the conditions for a mini table are satified, the onEdit trigger will **insert** values in two columns in the active sheet that act as 
    helpers to organize mini tables.

The onEdit trigger runs any time you make an edit in the spreadsheet in which you installed the trigger. The onEdit trigger evalutes the 
value in the active cell and uses the value to determine if any columns should be displayed or hidden and determine if a mini table should be initiated 
or prevented. If columns should be dsiplayed or hidden or if a  mini table should be initiated, then sCubed displays columns, hides columns, or initiates 
a mini table. Finally, the onEdit trigger uses the value in the active cell to prevent you from initiating a mini table where a mini table is not permitted, 
which is based upon the value in the active cell and the `framework <https://ssquared-docs.readthedocs.io/en/latest/index.html>`_ used by 
sCubed allows for multiple values.

What does the sCubed add-on do with my information?
-------
The sCubed add-on needs to read information from the sCubed sheets to support features like column visibility, mini tables, and reporting workflows. 

* The sCubed add-on does not store any information captured within your sheets. 
* The sCubed add-on does not store any of your personal information. 
* The sCubed add-on does not track your usage.
* The sCubed add-on does not transmit your information to the developer of sCubed or her affiliates, the Edison Lab and the University of Georgia.
* The sCubed add-on does not transmit your information to any third party.

Is sCubed suitable for my private or sensitive data?
-------
You as the user own any data that are touched by the sCubed add-on. As the data owner, you are responsible for ensuring
that your data are handled in accordance with any regulations or policies relevant to your data.

Who developed sCubed?
-------
Development of sCubed was lead by `Abigail Elizabeth <https://orcid.org/0000-0001-8627-777X>`_ within the `Edison Lab <https://edisonomics.org/>`_
at the University of Georgia (UGA). sCubed was developed with feedback from members of the Edison Lab at UGA. 

Why was sCubed developed?
-------
sCubed was conceived to help researchers within the Edison Lab at UGA capture information about how scientific experiments are conducted. The sCubed 
add-on was developed to share our resources with other researchers and promotoe open science.


Please direct questions about the privay policy to our `GitHub repo <https://github.com/aemoore62/scubed_community>`_.
 
