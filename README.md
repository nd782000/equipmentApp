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


####EquipmentViewController.swift
#####Complete
* Show equipment image
* Show equipment detail
* Change page title to equipment name
* Parts tableview
* Schedule tableview
* History tableview
* Table switcher
* Edit Button

#####To Do
* Edit functionality
* Full item information
* Improve layout and information spacing
* Load parts, schedule and history cells once data available.
