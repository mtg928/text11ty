---
title: STEM User Manual - Chapter 9
description: Introduction to STEM software FTA
date: 2023-04-08
tags:
  - STEM FTAsoftware
  - STEM User manual
  - FAQ
  - STEM Training courses
  - Technical support
  - eleventy
layout: layouts/post.njk
---

# 9	Fault Tree Analysis (FTA) Module
To start the Fault Tree Analysis (FTA) Module, click on the FTA ICON on the left side toolbox.  The FTA summary screen will be displayed to develop the input data sheet for the FTA model. The blank FTA summary sheet can be developed as described in sections below.

## 9.1	FTA Component Inputs Menu

The Fault Tree summary tab contains information tabs showing the information summary and the FTA calculation sheet that is illustrated in Figure 44. 

Figure 44: STEM FTA menu buttons

HOLD FIGURE HERE


The functions of the FTA horizontal buttons used to manage the input data is detailed in Table 21. 


Table 21: FTA horizontal menu buttons description



ADD TABLE HERE -




## 9.2	Fault Tree summary tab

The Fault Tree summary tab setups the calculation inputs for the FTA calculation. The FTA calculations can be tracked by filename, as shown in  Figure 44. Table 22 outlines the fields used in the FTA input summary tab.



HOLD FIGURE Here


Figure 45: FTA Input Summary page




Table 22: FTA Input summary description


ADD TABLE HERE -



## 9.3	FTA Input summary operation

Fault Tree summary tab enables users to add, edit, and remove the FTA summary details for the FT calculator. Users can also copy and paste data from one FTA or from a text file into the popup panel when the ‘Edit FTA’ button is selected 


• Note

Users can copy and paste data through the popup option to enable the features, Ctrl + C to copy and Ctrl + V to paste.



## 9.3.1	Creating a new FTA project summary
A new FTA project summary (template) is created when users select the ‘Add FTA’ button in the summary input sheet, see Figure 45 and Figure 46. Basic calculation information, including function name, CMM file, MPG type and comments can be entered into the popup FTA options page as illustrated in the figure below.


HOLD FIGURE Here

Figure 46: Add FTA option page


## 9.3.2	Editing an FTA project summary

To edit an FTA project summary record in the FTA Input summary tab, select the row then click the ‘Edit FTA’ button in the menu bar, see Figure 45.

## 9.3.3	Remove an FTA project summary record

To remove an FTA project summary record, select the row in the FTA input sheet and then click the ‘Remove FTA’ button in the menu bar, see Figure 45. A warning message will appear when you perform this operation. Select ‘Yes’ to perform the operation or ‘No’ to stop the deletion, as shown below.



HOLD FIGURE Here

Figure 47: FTA deletion warning message


! Note.

Warning: This operation will delete the row of data associated with the FTA. Check that you intend to delete the data, as this operation will delete the data permanently.




## 9.3.4	View FTA details

To view the FTA model, click the ‘View Details’ button on the right side of the summary sheet. This opens the FTA calculator, which is shown by the Fault Tree Model tab, where the user can build the FTA models, see Figure 45.

The functions of the vertical button used to view the FTA worksheet is shown in Table 23. 

Table 23: FTA vertical button description


ADD TABLE HERE -




## 9.4	FTA Model 
The Fault Tree (FT) model tab allows users to enter the build the Fault Tree model. The following sections describe the features available in the STEM FTA App to build a Fault Tree model.

9.5	FT Horizontal toolbar
The horizontal toolbar buttons contain a set of icons that gives short-cut access to the FT calculation utility options, as shown in Figure 48.  Table 24 presents a list of the FT menu options and shortcuts.


HOLD FIGURE Here

Figure 48: FT Horizontal Toolbar




Table 24: FT Toolbar Tab Options


ADD TABLE HERE -


• Note*.

To insert, edit or delete an FT object, the user will need to select the object in the FT model to enable the buttons. 


• Note.

The names of the FT icons are revealed when the user places the cursor over the icon. 



## 9.6	FT Model operations 

Users can Add, Edit, delete and save components or generate the model calculation in the FT Model clicking on the ICONs in the menu or by right clicking or double clicking on the object in the model. The event options menu will be displayed, as shown in Figure 48.
Users can enter event id, type, link to a document reference or a value. Comments can also be added. The update button allows the user to refresh the FTA data. 

## 9.6.1	Insert gate event

To add a new gate event in the FT model, select the model tab and select the Top Event or Gate Event box then right click or double click on the object in the model. This will open the pull-down menu, see Figure 50. Basic gate event information, including event id, event name, Gate (type), Proof test interval (PTI) and reference can be entered into the new FT gate event options page as illustrated in the figure below.

HOLD FIGURE Here

Figure 49: FT Insert Options


HOLD FIGURE Here

Figure 50: FT Gate event options page


## 9.6.2	Insert base event

To add a new base component to the FTA model, select the model tab and select the Top Event or Gate Event box then right click or double click on the object in the model. This will open the pull-down menu, see Figure 51. Base event information, including component, data type, component id, component name, reference and probability can be entered into the new FT base event options page as illustrated in the figure below.


HOLD FIGURE Here

Figure 51: FT base event options page


## 9.6.3	Edit cell

To edit an FTA record from the FTA record in the row then click the Edit FTA button in the menu bar or select the model tab and select the Top Event or Gate Event box then right click or double click on the object in the model. This will open the pull-down menu, see Figure 50 and Figure 52. Basic gate event information, including event id, event name, Gate (type), Proof test interval (PTI) and reference can be entered into the new FT gate event options page as illustrated in the figure below.



HOLD FIGURE Here


Figure 52: FT Edit Option

## 9.6.4	Delete 

To delete an FTA component from the FTA model:
 * Select the delete ICON in the toolbar, see Table 24, or by right clicking on the FT sheet in the model to activate the pull-down menu and select the delete option

The component will be removed in the FTA model.

## 9.6.5	Refresh

To refresh the FT model:
 * Select the refresh ICON button in the toolbar, see Table 24, or by right clicking on the FT sheet in the model to activate the pull-down menu and select the refresh option.

The FT Top event result will be updated.



## 9.6.6	Merge

This option will synchronise the FTA data in the calculation tab at the “local” App level with the data in the CMM. You can use this option to apply the changes to the FTA gate data pulled from CMM.

## 9.6.7	Calculate

This option recalculates the FTA Top and all base event results in the FT model.

## 9.6.8	Zoom in

To Zoom into the model and increase magnification, click of the Zoom in button in the menu bar.

## 9.6.9	Zoom out

To Zoom out of the model to decrease magnification, click of the Zoom out button in the menu bar.

## 9.6.10	Save All

To save data in the FTA model:
 * Select the save all button in the toolbar, see Table 24, or by right clicking on the FT event in the model to activate the pull-down menu and select the save option.
 * The saved data will bed indicated by the document save message in the status bar, see Figure 53.

The FT data will be saved.



HOLD FIGURE Here

Figure 53: FT Save all option

## 9.6.11	Creating a new FTA model

STEM allows users to create a new FTA model for design. A new FTA model is created by selecting the ‘Add FTA’ button in the FTA summary input sheet, see Table 4.  Basic calculation information, including function name, calculation file, MPG type and template can be entered into the new FTA options page as illustrated in the figure below.


HOLD FIGURE Here

Figure 54: FT Model Example


## 9.7	Calculation Options

The FT calculation results are described this section.

## 9.7.1	Calculate FT Model

To generate the FT model, select the calculate option button in the menu bar to recalculate the FTA Top event result in the FT model.


## 9.7.2	Generate FT Model

Users can generate the Fault Tree Top event result by clicking the Calculate Icon in the Toolbar or activating the pull-down menu by selecting the Top event and then right clicking the mouse.
To export the Fault Tree model, click on File, Export Report on the File menu bar or select shortcut CRTL + E. The export message will be displayed in a message box with the option to generate a FT graph in a PDF or PNG format.

## 9.7.3	Generate FT Model data

You can export an FT data file as a table by selecting the calculate option button in the menu bar to download the data file as excel or MS access file, see Figure 56 and Figure 57.

• Tip 
STEM users will not be able to amend the data in the FT data tab. Data adjustments can be made in the FT model.


HOLD FIGURE Here

Figure 55: FT Model


HOLD FIGURE Here

Figure 56: FTA data export option



HOLD FIGURE Here

Figure 57: FTA data report


