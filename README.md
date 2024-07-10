# SSIS_Tasks:
Using Microsoft SQL Server and the SSIS tool.


## Task One:
+ Consume any REST API and load the response into the database.

## Task Two:
+ Implement SCD Type 4 for the 'Employee_Q2' table, focusing on the 'City' and 'Email' fields.
+ This requires creating two target tables: one for storing the latest version of each record and another for maintaining historical changes.
+ The source data should be read using Incremental Load to capture updates.

## Task Three:
+ Implement a versioning system to load source data from the 'Employee_Q3' table into a target table.
+ The target table should reflect the current version of each record and maintain historical versions.
+ For each run on the same day, increment the version number and mark previous records as inactive.
+ Reset the version number to 1 for the first run on a new day, regardless of changes in the source data.

## Task Four:
+ Read attendance data from a device and load it into a target table with fields like Employee ID, Date, Time In, Time Out, Worked Hours, and State.
+ The state descriptions range from 'Arrived on time and worked more than 8 hours' to 'No check-out record for the employee.'
+ Implement logic to handle multiple check-ins/outs and ensure accurate recording of work hours and states.


## Contributors:
- [Sara Adel](https://github.com/saraadel6)
- [Mariam Ramadan](https://github.com/Mariamramdan)
