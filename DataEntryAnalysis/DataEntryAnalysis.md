### 1. Current Problems
* There are missing fields in the tempreature and some in diamter columns, which are not handled 
* Cuni and Chippo should be separated to the two datasheets
* Date should include timing e.g 6/4/11 and next column time 02:00 pm, since plankton change their distribution from day to night. Thus it is unknown when was the data collected.  
* Data is recorded in the 3 different spreadsheets and dates are unordered across them. 
* Fields namings are very consfusing can eventually lead to misinterpretation 
* Some fields are different accross three spreadsheets: in one of them Diamter is recorded as ColonySize and Colony Diameter in the another. 
* Chlorophyll is not recorded in the pond spreadsheet
* Column Depth is recorded as z in the pond spreadsheet. and Depth in zoop spreadsheet. 

### 2. Suggestion
* Cuni and chippo should be separated and recorded seprately. For example, 
##### Chippo
|   Date	|   Time	|   #L	|   Colony Size	|   Temp	|
|---	|---	|---	|---	|---	|
|   6/4/11	|   02:00	|   72	|   2.12	|   14.1	|
##### Cuni
|   Date	|   Time	|   #L	|   Colony Size	|   Temp	|
|---	|---	|---	|---	|---	|
|   6/4/11	|   02:00	|   72	|   2.12	|   14.1	|
* For missing data: possible solution is either take a mean of the column H, recorded as missing, or delete it completely.
* Add the time column for better surveillance  
* Unite the spreadsheets but, as stated above, separate by the species
* Column name inconsistencies must be corrected. Names should be universal and simple to understand.
