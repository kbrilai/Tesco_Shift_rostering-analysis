# Tesco_Shift_rostering-analysis

I've Noticed the Business process on scheduling shifts to actually doing payroll has a lot of unnecessary steps, causing innacuracies in payroll on payday, requiring a lot of consolidation. This project is to demonstrate a proof of concept to see if my current store staff would buy into a more efficient model and reduce the amount of administrative time spend on paperwork. 


Current Workflow:
Team Leader plans roster on a week by week basis. adjusts numbers on a word file, calculates the total number of hours each staff has, and if we have sufficient coverage of 4 staffs per shift on any overlapping time of day manually. 


Proposed Proof of concept workflow: 
PowerBI Dashboard 



Input: Local SQL database, create temp table, insert shifts in temp table, if accurate at end of week, execute store procedure to store it in the main DB store on shifts actually logged. this can more accurately reflect timing and overtimes. 

database: local SQL server 
data cleaning: SSMS
Visualisation: PowerBI
