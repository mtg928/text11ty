---
title: STEM User Manual - Chapter 7
description: Introduction to STEM software FMECA
date: 2023-04-08
tags:
  - STEM FMECA software
  - STEM User manual
  - FAQ
  - STEM Training courses
  - Technical support
  - eleventy
layout: layouts/post.njk
---


# 8	Failure Modes Effects Criticality Analysis (FMEA) Module
To start the FMECA Module, click on the FMECA icon on the left side menu bar. A blank FMECA input sheet is displayed allowing the User to develop. This is described in sections below.

## 8.1	FMECA menu

The FMECA calculator contains information tabs showing the information summary and the FMECA calculation sheet that is illustrated in Figure 32.

Figure 32: STEM FMECA menu Toolbar

HOLD FIGURE HERE


The functions of the horizontal menu bar used to manage the input data is detailed in Table 12. 

Table 12: FMECA input worksheet description


|Button|Function  |
|:--- | :---:|
center text
|**Add**	|Add a FMECA component to the FMEA summary	|
|**Edit**	|Edit a row in the FMECA summary sheet	|
|**Remove**	|Add a FMECA component to the FMECA summary	|
|**Refresh** |Refreshes the FMECA summary sheet	|



## 8.2	FMECA summary tab

The FMECA summary tab lists all the inputs for the FMECA calculation. Users can track their FMECA calculations by filename, as shown in Figure 33.  Table 13 outlines the fields used in the FMECA input summary tab.



HOLD FIGURE HERE
Figure 33: FMECA Input Summary page



Table 13: FMECA Worksheet description


|Parameters|Description  |
|:--- | :---|
|No | Line Number|
|Component Id | Id reference of the component|
|FMECA Name | Name of FMECA|
|Main Product Group (MPG) Type | Main product group type|
|CMM id |Internal calculation file Id used to identify the calculation record for the FMECA|
|CMM Name | Calculation name|
|Standards | Standard template used for the FMECA|
|Comments | Commentary section.|




## 8.3	FMECA input operation

The FMECA input calculator enables users can add, edit, and remove project calculation details in the sheet. Users can also copy and paste data from one FMECA or from a text file. There is a refresh function to refresh the FMECA calculator data.  To access the menu list, right click on the FMECA calculator sheet, which displays the dropdown menu.


## 8.3.1	Building a new FMECA template

Users can develop a new FMECA template by selecting the ‘Add FMECA’ button in the FMECA summary input sheet which opens a new page, see Figure 34.  Basic calculation information, including function name, calculation file, MPG type and template can be entered into the new FMECA options page as illustrated in the figure below.


Figure 34: Add FMECA option page




## 8.3.2	Editing an FMECA template

To edit an FMECA record from the FMECA record in the row then click the Edit FMECA button in the menu bar, see Figure 33.

## 8.3.3	Remove an FMECA record

To remove an FMECA record from the FMECA input sheet, select the row in the FMECA and then click the Remove FMECA button in the menu bar, see Figure 33. A warning message will appear when you perform this operation. Select ‘Yes’ to perform operation or ‘No’ to stop the deletion.


! Note.

Warning: This operation will delete not only the record but also the functions and components associated with the FMECA. A warning message will appear when you perform this operation. The data deleted cannot be recovered!


## 8.3.4	View FMECA details

To view the FMECA worksheet, click the View Details button on the right side of the summary sheet. This opens the FMECA calculator, which is in the FMECA calculator tab, where the user can build the FMECA models see Figure 20. 

The functions of the vertical button used to view the FMECA worksheet is shown in Table 6. 

Table 14: FMECA vertical button description


|Button | Function|
|:--- | :---|
| | View the FMECA worksheet|



• Tip 
The worksheet columns can be adjusted by dragging the edge of the cell.


## 8.4	FMECA calculator 

The FMECA calculator tab allows users to build the FMECA from the input calculator sheet. The features of the FMECA worksheets are shown in the Figure 22. Two calculator templates are available to the user, the qualitative RPN method and quantitative versions of the FMECA.
Further details of the functions and components for both methods are described in s 7.6.1 and s7.6.2. 

Figure 35: FMEA Calculator page


HOLD FIGURE HERE




Table 15: FMECA options - pt1


|Parameter | Description|
|:--- | :---|
Failure identification
| Subsystem Breakdown code|References id for the main component or subsystem |
|CSubsystem / Component |Name of the main component |
|Function |Subsystem / component function |
|Phase |Operational phase |
|Failure mode |The manner in which a component fails |
|Failure cause |Likely cause for each failure mode |
|Severity Class |Severity classification |
|Failure rate data source |The conditional probability that the failure effect will result in the identified criticality classification, given that the failure mode occurs |


Table 16: FMECA components options - pt2




|Parameter | Description|
|:--- | :---|
Detection and recovery measures
|Failure mode ratio |The fraction of the part failure rate based on a specific failure mode under consideration |
|Failure rate |Part failure rate |
| Operating time| Time or the number of operating cycles of the item in the mission s|
|Failure Item Criticality |Criticality number for the item |
|Failure mode Criticality |The value of the failure mode criticality.  This is a product of the conditional probability of mission loss, failure mode ratio, part failure rate and time or the number of operating cycles of the item in the mission |
|Remarks |Commentary section |


• Tip 
Adding a component will update the calculation management database immediately.
This bottom-up approach is made when the user is in the FMEA worksheet





## 8.5	FMECA calculator operations 

Users can Add, Edit, delete and save components in the FMECA Calculator. Users can also copy and paste data from one FMECA or from a text file. The Refresh function allows the user to refresh the FMECA data. Users can access the menu list by Right clicking on the FMECA calculator sheet.

## 8.5.1	Add a single row of data

To add a new component to the FMECA input sheet:
 * Select the cell or row on the FMECA worksheet and right click to open the menu list.  the component from the list of systems and main product group
 * Select Add FMECA component button from the list. An input panel will be displayed for the user to enter details, see Figure 24.
 * Click the radio button to select the specific component.
 * Click on the add button to include the selection to the FMECA input calculation sheet.

The panel enables users to amend any row of data on the FMEA worksheet. The failure identification and failure effects which defined by the user are presented in Table 7. Table 8 describes detection measures.

If you require all subsystems in the analysis:
 * Click on the Select All button
 * Click on the add button.

Figure 36: Add FMECA components page





## 8.5.2	Copy and paste data

Users can apply the copy and feature in STEM by using the mouse. Users can select the desired cell on the worksheet by clicking on it and then hold down the left mouse button.  To obtain specific information, click on Edit, on the File menu bar and select Copy from the pull-down menu. Alternatively, select Ctrl – C on the keyboard to copy the object. 

Selected objects can be pasted within the worksheet by selecting Ctrl – P on the keyboard to paste the object.


## 8.5.3	Edit a single row of FMECA data

To edit an existing row from the FMECA worksheet:
 * Click on the Select the Edit button, or
 * Select the row in the sheet


You get a Popup to edit the information.  The following image show the FMECA add Popup based on the MIL standards.

The popup filled with previously entered information. You can edit the details and click save button to save the changes, see Figure 26.


Figure 37: FMEA popup box

Users can modify the data without using the “Edit Single Row” option by clicking the cell in the FMECA worksheet to edit the information directly.

• Tip 

Components information ("Id", "Subsystem Breakdown Code", "Subsystem/ Component" and "Failure mode") can only be modified in the FMECA summary tab section.





8.6	Save FMECA File

FMECA files may either be saved using the current case name or under a new name.

To save a file using the current file name, do one of the following:
 * Search the system from the list
 * Select Export report from the File menu, or
 * Use the key combination Ctrl + A.


To save a file using a new name, enter the following:
 * Select Export report from the File menu, or
 * Use the key combination Ctrl + A.

The dialog box with be displayed to save the file name as shown in Figure ??? for the FMECA file where the case file is saved for the first time or with a new name.

The user should clear the filename field, then type the new filename of the case and click the OK button. 


[ADD FIG HERE]


Figure 39: Exporting a data file


HOLD FIGURE HERE

• Tip 
STEM software will automatically save the file extension, so Users do not need to enter it in the file dialog box.






8.7	Delete a component

To delete a component from the FMECA input sheet:
 * Select the row containing the component in the FMECA input table.
 * Click the Remove FMECA component button to delete the component from the FMEA input sheet.
 * Click the Refresh button.

The component in the selected row will be removed in the current FMECA input sheet.



! Note.

Warning: This operation will delete the row of data associated with the FMEA. A warning message will appear when you perform this operation. The data deleted cannot be recovered!





8.7.1	Import an FMEA template
[HOLD SECTION ---18.12.21]

[HOLD: This function is currently unavailable with the current STEM Version]. Project sharing feature in the Cloud under review - HOLD]


8.7.2	Merge calculation data

The option will synchronise the FMEA data in the calculation file at the “local” App level with the data in the CMM. You can use this option to apply the changes to the FMEA. 
Figure 40: FMEA Calculation Worksheet – RPN method



8.8	Calculation Options

The two calculation templates are described this section.

8.8.1	Calculate RPN

The Risk Priority Number (RPN) is calculated by multiplying the severity of the effect of failure, the probability of occurrence, and the ability of detection for each failure mode.


• Note.

The RPN does not play an important part in the choice of an action against failure modes but will help in indicating the threshold values used to evaluate critical areas.




Table 17: FMECA worksheet description for the RPN method

Parameters	Description


ADD TABLE HERE -

8.8.2	Refresh calculation data

The STEM software will synchronise the FMECA data with the database.


[ADD FIG HERE]


Figure 41: FMEA Calculation Worksheet – RPN method



8.8.3	MIL Std calculation

The MIL Standard FMECA template can be used by the user by choosing the template option in the menu. 

Table 10 lists the worksheet parameters generated by the MIL Std FMECA template.

Table 19: FMECA worksheet description for the Mil Std method

[To add table here]


## 8.9	FMECA Results

[HOLD SECTION ---08.01.22]

[HOLD: Feature currently unavailable with the current STEM Version]
The FMECA results screen allows the ordering of FMECA data within the project.  This can be viewed by clicking the results icon in the navigation bar.

The summary of the FMECA results summary allows the user for the data to be screened as shown in the Table 11.


The tabulated FMECA results can be viewed by clicking the View icon in the navigation bar, refer to Figure ???.


Table 20: FMECA results worksheet description


ADD TABLE HERE -




Figure 42: FMECA Results Table

[HOLD – MISSING FIGURE FMECA Results Table missing]



Figure 43: FMECA results worksheet description


[HOLD – MISSING FIGURE FMECA Results Table missing]


_Figure 19: FMECA Results Table _



HOLD FIGURE HERE


