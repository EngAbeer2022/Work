## Clusterd Data Warehouse:
*Author:* Abeer Abu Mutawi <br>
*Created:* 20/06/2022

In this project I implement the - Clustered Data Warehouse - customer story: validate requested 
fields(DealUniqueID, FromCurrency, ToCurrency and DealAmount) and 
presits them into the DealDetails table. <br> <br>
To Do this I follow these steps:
1. Check if inserted Deal already exits - if yes the redirect to the Error page. <br>
2. Validate the deal details content - if invalid then redirect to the Error page.<br>
3. Insert the new deal details record and save it to the DB.
---
In this project we try to do the following:
1. Connecting to the DB using the Pros file.So When you want to run the application you need to 
configure the DataBase proprty file located at - src folder.
2. Create business rule named CDWHValidator to make some business logic
3. Use the - Log4j - to log the activity during the business cycle
4. Connection pool to use limit number of connection to manage resource usage.
5. Some Utilities to serve a specific functionality
