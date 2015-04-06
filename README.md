# ALG Equipment App

![ALG Equipment App](http://www.atlanticlawnandgarden.com/cp/app/img/appLogo.png)

###Goal
The aim of this project is to create an equipment management application in swift targetting all iOS devices. The app will be able to display (filter, sort) all of the equipment items as well as display a detailed view of each item with maintenance schedule. From the schedule users will be able to view and modify equipment work orders. 


###Breakdown by Page

####EquipmentListViewController.swift
#####Complete
* Table View
* Menu Button
* New Button
* List Filters (Name, Status, Make, Crew)

#####To Do
* Reverse order on click already selected filter (Attempted, couldn't work it out.)
* Crew names rather than ID


####NewEquipmentViewController.swift
#####Complete
* Preload Type Picker
* Autolayout fields
* Camera Button
* Camera Functionality
* Back Button
* Preview Picture
* Progress Bar
* Form reset after successful submission

#####To Do
* Preload crew names for picker once available
* Date Selector keyboard for purchase date?
* Form validation methods
* Auto name generation


####EquipmentViewController.swift
#####Complete
* Show equipment image
* Change page title to equipment name
* Parts tableview
* Schedule tableview
* History tableview
* Table switcher
* Edit Button

#####To Do
* Edit functionality
* Show equipment detail (including new fields)
* Full item information
* Improve layout and information spacing
* Load parts, schedule and history cells once data available.


####ScheduleViewController.swift
#####Complete
* Main tableview
* Switcher

#####To Do
* Finish schedule table cell
* Load data from PHP
* Add icons to table cell


####WorkOrderViewController.swift
#####Complete
* Layout started
* Fields in place
* Edit layout

#####To Do
* Load data from PHP
* Pass data from edit back to PHP
* Neaten layout based on true value look


####ItemViewController.swift
#####Complete
* Field layout
* Edit mode layout

#####To Do
* Available to be passed a variable to control view settings based on labor or material
* Make task list
* Estimated quantity
* Link to usage screen
* Load data from PHP
* Pass from edit to PHP


####ItemListViewController.swift
#####Complete
* Layout
* Tableview
* Event listeners

#####To Do
* Load data from PHP


####TaskViewController.swift
#####Complete
* ..

#####To Do
* switch view/edit eit mode
* Task Description
* Display task images
* Task status



####UsageListViewController.swift
#####Complete
* ..

#####To Do
* Tableview
* Add entry button
* Summary text area (estimated vs actual)


####UsageEntryViewController.swift
#####Complete
* ..

#####To Do
* Two views (labor/material)
* Entry pickers, buttons etc. Start/Stop time and date
* Crew/Employee selector (Multi)

