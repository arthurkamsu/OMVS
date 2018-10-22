# OMVS
The VehicleRegistration.rar file contains the solution

---------------------------------------------------
	OMVS DEVELOPER PRE-SCREEN
	Candidate: Arthur Kamsu Mbiydzenyuy
	arthur.kamsu.m@gmail.com
	641-451-4909
---------------------------------------------------

All the requested delivrables are included in the solution.
The solution is developed using Visual Studio 2015 professional
with MSSQL Server 2016. The solution include some additional projects that
i found interresting to include.
There is a backup of the database provided with the solution. 

The solution is a Desktop application divided into many layers. There are two features :
1. Check if two counties are adjacents (Shortcut: CTRL+N)
	This feature allow the user to type in the Atlas id of two counties, and the software
	tells him if those two counties are adjacents or not.
2. Show the adjacent counties to a selected counties (Shortcut: CTRL+O)
	Here the user select a county and the software show all the counties adjacent to it in an
	alphabetical order.

NB: 
- Not all the counties have been inserted in the database. Only these counties will produce an accurate 
result: Story, Greene and Tama (The Database should be restored using the backup). 
Some records have been inserted using the software and might not have a corresponding SQL Insertion command
in the Script.

- The Connection string for the database access is located in Web config files. Each layer that access the 
database have a Web.config file and the parameters of the connection string attribute have to be changed in it.
The concerned layers are: DAL_ObjectiveA, UI_ObjectiveB and TestProject.

- Not every thing has been handled in this solution due to the deadline, but the required job has been done.

- The Solution use MetroUI which is a framework for building attractive UIs on Winform. For more information about 
it, please visit https://github.com/dennismagno/metroframework-modern-ui
