# DevTest2

Changed the type of SalesTotalInfo from string to StringBuilder. 
Moved the count and sales total sum into the same linq query where we get customer details. Getting all the data in one single linq query will reduce the time to get data instead of connecting to database multiple times.
Instead of writing response to web page for each record or each loop, all the data is appended to a SalesTotalInfo object and final string is written to webpage. This saves write time.
