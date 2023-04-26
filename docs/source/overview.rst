Overview
=====
sCubed is a spreadsheet application that aims to help researchers detail of how scientific experiments were conducted. sCubed was developed in unison with its underlying, platform-independent framework, `Share Science <https://ssquared-docs.readthedocs.io/en/latest/ssquared_tab.html>`_.

Use few sheets to capture complex information
-------
sCubed includes four or five sheets to capture metadata, depending on what granularity of information the researcher wants to capture. The four core sheets are implemented regardless of granularity:

* **conceptDefinition** enables reserachers to capture a diverse range of conceptual entities, ranging studies to items.
* **materialDefinition** eases detailing physical material by permitting reserachers to relate unique instances of physical material to items previously described in *conceptDefinition*.
* **processDefinition** allows reserchers to capture the conditions for experimental processes, like temperature of storage, and reuse these descriptions to either summarize experiments or detail individual activities.
* **workflowManagment** enables researchers to define standard sequences of process types and planned processes to either summarize experimental activities or guide themselves through reporting a standard sequence of activities via the *processExecution* sheet.

In addition to the four core sheets, researchers may employ a fifth sheet, **processExecution**, to describe individual research activities.

Streamline capturing information with key features
-------
To transform how researchers capture information in sheets, sCubed introduces a few key features:

Column visibility
~~~~~~~~~~
The **column visibility** shows the researcher only columns that are relevant to the immediate entry. *Column visibility* causes the sheets to dynamically respond to the researcher's entries:  *Column visibility* displays columns that are relevant to the researcher's entry and hides columns that are irrelevant. In this way, researchers can capture a diversity of information in one sheet without navigating a multitude of columns.

Mini tables
~~~~~~~~~~
The **mini table** feature helps researchers accuratly reflect one-to-many relationships without redundancy. Via mini tables, researchers minimize
the time required to capture complex relationships and machines can recognize mini tables.

Reporting workflows
~~~~~~~~~~
The **reporting workflow** feature enables researchers to document a standard sequence of process types and reuse the workflow to either summarize experiments or guide themselves through reporting a standard sequence of activities.

To complement *column visibility*, *mini tables*, and *reporting workflows*, sCubed employs features that are native to Google Sheets:

* **Data validation** restricts the entries that researchers make, e.g. select an item from a list of controlled vocabularies.

* **Value formatting** dictates how values are displayed and mitigates unwanted transformations to information, e.g. gene names being converted to dates.

* **Conditional formatting** changes the background colors of cells to indicate which fields are required, optional, completed, or not applicable.

* **Simple help text**, implmented using the Google Sheets feature *notes*, provides key information about what is expected of entries.

Summary
-------
Through five sheets and a combination of features that are novel and native to Google Sheets, sCubed honors the preferance of many researchers to collaborate in spreadsheets. Simulaltaneously, sCubed targets the challenge to make complex, scientific information in spreadsheets trustworthy and machine-actionaable.

