3005_2014
=========

## Notable Features

* Scripted Autonomous using a basic space delimited spreadsheet format. Simple parsing done using the Read Spreadsheet File VI. Files downloaded to the robot over FTP and selected by the driver station

* Modular code for all subsystems allowing easy access to repeatable functions

* Use of simple test benches for each module

* Modification of several core VIs from the WPI library for 6 CIM motor CAN control. Refactored functions showed ~15% increase in performance

* Vision moved to the dashboard, which takes one picture at a selectable time to determine which hot goal to target