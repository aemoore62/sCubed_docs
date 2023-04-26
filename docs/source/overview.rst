Overview
=====
sCubed is a spreadsheet application that aims to help researchers capture details of how scientific experiments were conducted. 

Sheets
-------
sCubed includes four or five sheets to capture metadata, depending on what granularity of information the researcher wants to capture. The four core sheets are implemented regardles of granularity:
* **conceptDefinition** enables reserachers to capture a diverse range of conceptual entities, ranging studies to items.
* **materialDefinition** eases detailing physical material by permitting reserachers to relate unique instances of physical material to items preveiously described in *conceptDefinition*.
* **processDefinition** allows reserchers to capture the conditions for experimental processes like temperature of storage and reuse these descriptions to either summarize experiments or detail individual activities.
* **workflowManagment** enables researchers to define standard sequences of process types and planned processes to either summarize experimental activities or guide themselves through reporting a standard sequence of activities via the *processExecution* sheet.

In addition to the four core sheets, researchers may employ a fifth sheet, *processExecution* to describe individual research activities.

Features
-------
To transform how researchers capture information in sheets, sCubed introduces a few key features:

Column visibility
~~~~~~~~~~
The **column visibility** feature enables the sheets to dynamically respond to the researcher's entries by displaying columns that are relevant
to the researcher's entry and hiding columns that are irrelevant. In this way, researchers can capture a diversity of information in one sheet without
navigating a multitude of columns.

Mini tables
~~~~~~~~~~
The **mini table** feature enables researchers to accuratly reflect one-to-many relationships without redundancy. Via mini tables, researchers minimize
the time required to capture complex relationships and machines can recognize mini tables.

Reporting workflows
~~~~~~~~~~
The **reporting workflow** feature enables researchers to document a standard sequence of process types. With reporting workflows researchers can either directly relate workflow to physical material as means to summarize experimental activities. Alternatively, reporting workflows can be populated into the
sheets to guide reserachers through reporting a standard sequence of activities. In this way, researchers determine what experimental steps are most important to report and at what level of granularity, as a summary or individual activities.
a physical material to summarize.

sCubed not only introduces new features to the realm of capturing complex, scientific information in spreadshets but sCubed also employs features that are native to Google Sheets:

Data validation
-------
**Data validation** restricts the entries that researchers can make, e.g. select an item from a list of controlled vocabularies.

Value formatting
-------
**Value formatting** dictates how values are displayed and mitigates unwanted transformations to information like gene names being converted to dates.

Conditional formatting
-------
**Conditional formatting** changes the background colors of cells to indicate which fields are required, optional, completed, or not applicable.

Simple help text
-------
**Simple help text**, implmented using the Google Sheets feature *notes*, provide key information about what is expected of entries.

Through five sheets and a combination of features that are novel and native to Google Sheets, sCubed honors the preferance of many researchers to capture and share metadata. Simulaltaneously, sCubed targets the challenge to make complex, scientific information in spreadsheets trustworthy and machine-actionaable.

