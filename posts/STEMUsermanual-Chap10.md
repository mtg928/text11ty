---
title: STEM User Manual - Chapter 10
description: Introduction to STEM software ETA
date: 2023-04-08
tags:
  - STEM ETA software
  - STEM User manual
  - FAQ
  - STEM Training courses
  - Technical support
  - eleventy
layout: layouts/post.njk
---


# 10	Event Tree (ETA) Module

The Event Tree Analysis (ETA) module allows the development of an Event tree (ET) model. To start the ETA module, click on the ET ICON on the left side menu bar.  This will display the ETA input screen to develop the input data sheet for the ETA model. The blank ET input sheet can be developed that can be developed as described in the sections below.

## 10.1	ETA Component inputs menu

The Event tree (ET) Summary tab is a calculation input tab that shows the key summary information supporting the ET model. The summary tab menu is illustrated in Figure 58. 

Figure 58: STEM ETA menu Toolbar


HOLD FIGURE Here



The ET functions in the horizontal menu bar used to manage the input data is detailed in Table 25. 


Table 25: ETA horizontal menu buttons description

ADD TABLE HERE -

|Button|Function  |
|:--- | :---:|
center text
|**Add**	|Add an ETA calculation sheet to the ETA summary	|
|**Edit**	|Edit a row in the ETA summary sheet	|
|**Remove**	|Remove an ETA calculation sheet from the ETA summary sheet	|
|**Refresh** |Refreshes the ETA summary sheet	|




## 10.2	Event Tree summary tab

The Event Tree summary tab setups the calculation inputs for the ET calculation. Users can track their ET calculations by filename, as shown in Figure 59. Table 26 outlines the fields used in the ET input summary tab.


Figure 59: ET Input Summary page

HOLD FIGURE Here


Table 26: ET Input summary description



|Parameters|Description  |
|:--- | :---|
|No | Line Number|
|Calculation Id | Internal calculation file Id used to identify the calculation record (for internal use)|
|Event Name | Event tree name|
|Event Type | Type of event tree (e.g. safety, reliability)|
|Initiating event |Initiating event name|
|Initiating value |Initiating event value|
|Unit | Unit of the initiating event value|
|Hazard | Hazard reference|



## 10.3	ET input summary operation

The Event Tree summary tab enables users to add, edit, and remove the ET project summary details for the ETA calculator. 
Users can also copy and paste data from one ETA or from a text file into the popup panel when the ‘Edit ETA’ button is selected 

• Note

Users can copy and paste data only through the popup option in Edit Event button to enable these features.


## 10.3.1	Creating a new ETA template

STEM enables users to create a new ETA template for developing models. A new ETA template is created by selecting the ‘Add ETA’ button in the ETA summary input sheet, see Figure 58. Basic ET calculation information, including event name, event type, hazard, reference to other calculation files, initiating event, initial value of the initiating event and comments can be entered into the new ET options page as illustrated in the figure below.
Users can create their own event or link the imitating event to an existing calculation, such as an FTA.  This is described further in section 12. 


HOLD FIGURE Here

Figure 60: Add ET option page


## 10.3.2	Editing an ET project summary

To edit an ET record from the ET input summary page, select the row then click the ‘Edit ETA’ button in the menu bar, see Figure 59. 

## 10.3.3	Remove an ETA project summary record

To remove an ET project summary record from the ET input sheet select the row in the ETA input sheet and then click the ‘Remove ETA’ button in the menu bar, see Figure 59. A warning message will appear when you perform this operation. Select ‘Yes’ to perform the operation or ‘No’ to stop the deletion, as shown below.




HOLD FIGURE Here
Figure 61: ETA deletion warning message


! Note.

Warning: This operation will delete the row of data associated with the ETA. Check that you intend to delete the data, as this operation will delete the data permanently.


## 10.4	View ETA details

To view the event tree model, click the ‘View Details’ button on the right side of the summary sheet. This opens the ET calculator, which is shown by the event tree model tab, where the user can build the ET models, see  Figure 59.

The functions of the vertical button used to view the ETA worksheet is shown in Table 27. 


Table 27: ETA vertical button description



|Button | Function|
|:--- | :---|
| | View the ETA worksheet|




## 10.5	ETA Model

The Event Tree (ET) model tab allows users to enter the build the event tree model. The following sections describe the features available in the STEM FTA App to build an event tree model.





## 10.6	ET Horizontal Toolbar

The horizontal toolbar buttons contain a set of icons that gives short-cut access to the ET calculation utility options, as shown in Figure 62. Table 28 presents a list of the ET menu options and shortcuts.



HOLD FIGURE Here

Figure 62: ET Horizontal Toolbar


Table 28: ET Toolbar Tab Options


|Parameters | Icon| Description|
|:--- | :---|
| Insert event| |Inserts node|
| Edit caption| |Edit heading captions|
| Edit cell| |Inserts node|
| Delete| |Delete a node|
| Delete| |Delete a caption|
| Calculate| |Calculates the model|
|Zoom In| |Zooms into the model|
| Zoom Out| |Zooms out of the model|
| Save All| |Saves all data in the model|


• Note.

The names of the ET icons are revealed when the user places the cursor over the icon. 


## 10.7	ET Model Operations

Users can Add, Edit, delete and save components or generate the calculation in the event tree model clicking on the ICONs in the menu. The event options menu will be displayed, as shown in Figure 62.


## 10.7.1	Insert node

To add a new node in the ET model, select the Insert node ICON in the toolbar or by right clicking on the node in the model. This will open the pull-down menu, see Figure 63. Basic node information, including barrier or control heading name, node value and end label tag names can be entered into the new ET node options page as illustrated in the figure below.


HOLD FIGURE Here

Figure 63: ET Node options page


## 10.7.2	Insert / edit caption

To add a new caption to the ET model, select the Insert node ICON in the menu bar as described in 10.7.1. This will open the pull-down menu, see Figure 63. 
Caption headings can be edited by selecting the edit caption ICON in the Toobar. The user can amend the barrier or control heading name information for all headings, see the figure below.



Figure 64: ET Insert Caption options page

HOLD FIGURE Here


## 10.7.3	Delete a node

To delete a node from the ET model:
 * Select the delete ICON in the toolbar, see Table 28, or by specific node on the ET model and right clicking the mouse to activate the pull-down menu and select the delete option

The component will be removed in the ET model.


## 10.7.4	Delete a caption

To delete a caption from the ET model:
 * Select the delete ICON in the toolbar, see Table 28, or by specific node on the ET model and right clicking the mouse to activate the pull-down menu and select the delete option

The component will be removed in the ET model.


## 10.7.5	Calculate

This option recalculates the ET data and all base event results in the ET model.

## 10.7.6	Zoom in

To Zoom into the model and increase magnification, click of the Zoom in button in the menu bar.

## 10.7.7	Zoom out

To Zoom out of the model to decrease magnification, click of the Zoom out button in the menu bar.

## 10.7.8	Save All

To save data in the ET model:
 * Select the save all button in the toolbar, see Table 24, or by right clicking on  * The saved data will bed indicated by the document save message in the status bar, see Figure 53.

The ET data will be saved.

## 10.8	Calculation Options

The ET calculation results are described this section.

## 10.8.1	Calculate ET Model

To generate the ET model, select the calculate option button in the menu bar to recalculate the ET data result in the ET model, see the result table in Figure 65.

## 10.8.2	Generate ET File

Users can generate the event tree result by clicking the Calculate Icon in the Toolbar.
To export the event tree model, click on File, Export Report on the File menu bar or select shortcut CRTL + E. The export message will be displayed in a message box with the option to generate an ET model in a PDF or PNG format.


HOLD FIGURE Here



## 10.9	Linking ETA and FTA Models

The initiating event in the Event tree model can be linked to a fault tree model using the Calculation Management Module Linking Option, see section 12 for further details.  

• Tip 
You will need to have created a fault tree model before it can be successfully link to an event tree model.

