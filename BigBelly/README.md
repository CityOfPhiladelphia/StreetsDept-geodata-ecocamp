# BigBelly

### Summary  

BigBelly receptacle data from January 1, 2014 through June 17, 2014.

### Description  

Each row represents one collection event for a given BigBelly at a given time and fullness level. There will be multiple rows for a BigBelly which constitutes all of the collections for that machine over the last 6 months. 

### Data Dictionary

| Field | Description  
| ----- | :----------:  
| SN |  The serial number of the BigBelly on the street. Each BigBelly has a unique SN
| StreamType |  The type of material the BigBelly holds. Typically in Philly, they are all Trash, but other customers have Single Stream, Bottles/Cans, Paper, etc.
| Lat |  Latitude of BigBelly location
| Long |  Longitude of BigBelly location
| Timestamp |  The Date/Time of the collection  
| Level |  The fullness of the bin when it was collected at the timestamp. We use a GREEN/YELLOW/RED system. GREEN is fairly empty (about 30 gallons of trash), YELLOW is full (about 90 Gallons) and RED is the highest (about 150 gallons).


### Credits  

2014 BigBelly Solar: The Smart Grid for Waste & Recycling TM

### Use Limitations  

The data will not be used for any other purpose than the ECO Camp Hackathon June 21-22 2014Upon request, BigBelly has access to view the resulting programs, application or tools created during the hackathon that have used this data set in whole or in partBigBelly is acknowledged for providing the data set to ECO Camp