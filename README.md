## Copy created from ITCareerSwitch/CompanyDirectory ##

## Creates unique repo which enables user to clone this project if required, without having to clone the full ITCareerSwitch repo ##

Project 2 : Company Directory

The aim of this project was to practice and showcase basic Crud operations. 

It is a simple single page layout, with three tabs dealing with Company Personnel, Departments and Locations. 

When the page loads it:

  * calls a javascript function, which
  * uses ajax to make a call to a php routine
  * This routine connects with a mysql database set up on phpmyadmin (sourced from employees.csv file)
  * the call to the database returns employee data which is returned to the javascript and displayed.

this chain is the same for most of the operations, such as selecting the tabs.

Each entry in the tabs views has a pencil (edit) and trach (delete) icon, each opening a modal for the action required. 
The code was also required to protect the integrity of the data in these actions, not allowing the user to compromise it by deleting records with dependencies, such as a department with employees.

Other Actions;

Search bar: searces the current tab for the input provided, with displayed results updating as you type.

Top right bar

refresh icon: if the tabs have changed due to searching or filtering, the refresh button refreshes the table to show all the records

filter icon: Allows the user to filter the records on view

plus icon: allows you to add a new employee, department or location, depending on which tab you are in.

