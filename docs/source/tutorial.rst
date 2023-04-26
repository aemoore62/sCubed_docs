Tutorial
=====

Configure sCubed Sheets
-------

#. Initiate core Sheets.
#. Add core data validation and formatting.
#. Select granularity of provenance.
#. Add provenance data validation and formatting.
#. Add another package.

Install onEdit trigger
-------
#. From the sCubed menu, select ``Install onEdit trigger``.

Access simple help text
-------
#. Hover the pointer over a column name to reveal the simple help text.

Add a controlled term
-------
Controlled can only be added via drop-down lists that include the key phrase ``Add controlled term``.
#. From the drop-down list, select ``Add controlled term`.
#. In the form, enter the term name.
#. In the form, specify if the term is an ontology.
#. Enter a link to the ontology term or an ontology term that's closest.

Create a planned process
-------
To create a planned process, you must have created at least one procees type
#. Select the ``processDefinition`` Sheets (tab).
#. In the first column, select a process type from the list.
#. In the column ``process_id``, enter a process ID.

Create a reporting workflow with the onEdit trigger
-------

#. Select the ``workflowManagement`` Sheets (tab).
#. In the first column, select ``reporting workflow`` from the list.
#. In the column ``reporting_workflow_name``, enter the reporting workflow name.
#. On the same row used in the previous step and in the column ``process_type``, enter a process type.
#. On the same row used in the previous step and in the column ``workflow_sequence_number``, enter the sequence number.
#. On the next row down and in in the column ``process_type``, enter a process type.
#. On the same row as the previous step and in in the column ``workflow_sequence_number``, enter the sequence number.
#. Continue repeating the previous two steps until your reporting workflow is complete.

Create a reporting workflow without the onEdit trigger
-------

#. Select the ``workflowManagement`` Sheets (tab).
#. In the first column, select ``reporting workflow`` from the list. Keep this cell active before moving to the next step!
#. From the sCubed menu, select ``Change view``.
#. From the sCubed menu, select ``Start mini table``.
#. Enter the number of steps in your reporting workflow into the form.
#. Click the ``submit`` button. Now a mini table should appear with the number of rows that you specified (number of steps).
#. Enter the reporting workflow name in the column ``reporting_workflow_name``.
#. On the same row used in the previous step and in in the column ``process_type``, enter a process type.
#. Continue on the same row used in the previous step and in the column ``workflow_sequence_number``, enter the sequence number.
#. On the next row down in the column ``process_type``, enter a process type.
#. On the same row as the previous step and in the column ``workflow_sequence_number``, enter the sequence number.
#. Continue repeating the previous two steps until your reporting workflow is complete.

Create a process specification with the onEdit trigger
-------
To create a process specification, you must have already 

* entered at least one reporting workflow and
* entered at least one planned process.

#. Select the ``workflowManagement`` Sheets (tab).
#. In the first column, select ``process specification`` from the list.
#. In the column ``reporting_workflow_name_reference``, select a reporting workflow from the list.
#. Enter the process specification name in the column ``process_specification_name``.
#. On the same row used in the previous step and in the column ``process_id``, enter a process ID.
#. On the next row down and in the column ``process_type``, enter a process ID.
#. On the same row and in as the previous step and in the column ``workflow_sequence_number``, enter the sequence number .
#. Continue repeating the previous two steps until your reporting workflow is complete.

Create a process specification without the onEdit trigger
-------
To create a process specification, you must have already 

* entered at least one reporting workflow and
* entered at least one planned process.

#. Select the ``workflowManagement`` Sheets (tab).
#. In the first column, select ``process specification`` from the list.
#. From the sCubed menu, select ``Change view``.
#. From the sCubed menu, select ``Start mini table``.
#. Enter the number of steps in your reporting workflow into the form.
#. Click the ``submit`` button. Now a mini table should appear with the number of rows that you specified (number of steps).
#. In the column ``reporting_workflow_name_reference``, select a reporting workflow from the list.
#. Enter the process specification name in the column ``process_specification_name``.
#. On the same row used in the previous step and in the column ``process_id``, enter a process ID.
#. On the next row down and in the column ``process_type``, enter a process ID.
#. On the same row and in as the previous step and in the column ``workflow_sequence_number``, enter the sequence number .
#. Continue repeating the previous two steps until your reporting workflow is complete.


Change visibility of columns without onEdit trigger
-------
If you install the onEdit trigger, the visibility of columns will automatically change based on edits. Regardless of the onEdit trigger, you can change
the visibility of columns via the add-on.

#. Click the cell that contains the value for which you would like display columns.
#. From the sCubed menu, select ``Change view``.

Enter activites using a reporting workflow
-------

Summarize provenance
-------
