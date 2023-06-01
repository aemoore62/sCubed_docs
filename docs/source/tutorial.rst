Tutorial
=====

Configure sCubed Sheets
-------

Start by configuring the sCubed forms. 
Navigate to the sCubed menu and then navigate to the item ``Configure forms``.

#. Select ``1. Create core forms`` to create the standard sheets.
#. Select ``2A. Enable summaries`` to enable summarizing the provenance of physical material OR ``2B. Enable activities`` to enable describe individual activities.
#. Select ``3. Add context packages`` and complete the form to add column based on your needs.
#. Select ``4. Apply core validation`` to apply data validation, value formatting, conditional formatting and simple help text to the core sheets.
#. If you presiously selected ``2B. Enable activities``, select ``5. Apply activity validation`` to apply data validation, value formatting, conditional formatting and simple help text to the processExecution sheet.

Install onEdit trigger
-------
#. From the sCubed menu, select ``Install onEdit trigger``.

Access simple help text
-------
#. Hover the pointer over a column name to reveal the simple help text.

Create a planned process
-------
To create a planned process, you must have added the ``CIDC`` context package via the custom menu ``Configure forms`` > ``Add context packages``.

#. Select the ``processDefinition`` Sheets (tab).
#. In the first column, select a process type from the list.
#. In the column ``process_id``, enter a process ID.

Create a reporting workflow 
-------

#. Select the ``workflowManagement`` Sheets (tab).
#. In the first column, select ``reporting workflow`` from the list.
#. In the column ``reporting_workflow_name``, enter the reporting workflow name.
#. On the same row used in the previous step and in the column ``process_type``, enter a process type.
#. On the same row used in the previous step and in the column ``workflow_sequence_number``, enter the sequence number.
#. On the next row down and in in the column ``process_type``, enter a process type.
#. On the same row as the previous step and in in the column ``workflow_sequence_number``, enter the sequence number.
#. Continue repeating the previous two steps until your reporting workflow is complete.

Create a process specification 
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

Change visibility of columns without onEdit trigger
-------
If you install the onEdit trigger, the visibility of columns will automatically change based on edits. Regardless of the onEdit trigger, you can change
the visibility of columns via the add-on.

#. Click the cell that contains the value for which you would like display columns.
#. From the sCubed menu, select ``Change view``.
