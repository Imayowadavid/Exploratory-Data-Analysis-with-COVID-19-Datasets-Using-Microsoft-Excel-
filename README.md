Exploratory Data Analysis Of Global COVID 19 Dataset .
Analysis of Covid 19 Dashboard that comprises 3 datsets for  Confirmed cases,Death cases, Death rate from year 2020-2022 globally on different ms excel worksheets in an excel workbook .
Datasets Author : Chimerezie Iwuoha (Linkedln) , @chimeXdata( Twitter)
Power query for Data transformation of data from year (2020-2022) before loading into  Ms.excel workspace
Pivot Tables was used to create Charts from Consolidated Data created after transformation 
Basic excel functions ( subtraction, sum) were used for final analysis of confirmed, Death, cases and Death rate from 2020-2022 in different countries.  
Guides,steps,insights on Datasets used and  Dashboard created goes thus;
(i). Open a fresh/new  Ms. excel worksheet so as to import the 3 Datasets used . Data ribbon>Get Data>From File>From workbook> Select multiple  items ( click on Confirmed , Recovered, Death then Transform Data; so as to go to Power Query Editor)
(ii) . On Power Query Editor ; The columns of the Datasets were extremely  wide I.e majority  of the Columns were extended as rows or there were more of columns attached as rows.Hence the need to Unpivot.
(iii). Go to Home (ribbon ) > At Datatype:Text( use first row as Headers ) to promote the Header( ensure Province/state,country/Region , Lat.,Long. are the columns Headers).
(iv) Since all the other columns to be "UNPIVOT" are all at the R.H.S(after Province/state,Country/region,Lat.,Long.) click on the First four(4) column then right click on "unpivot other columns" 
(v). Rename the Last two(2) columns ( " Attributes " & "Value") as "date" & "Confirmed" respectively. 
(vi). On the L.H.S Click on Recovered Table and carry out steps (ii)-(v) and ensure that the Province/state ,country/Region,Lat.,Long., are promoted to Headers then rename the newly created "Attributes" & "Values" columns as "date" & "Recovered" respectively. 
(vii). on the L.H.S , click on the Death Table and carry out steps (ii)-(v) and rename the newly created "Attributes" & "Value" as "date" & "Death" respectively. 
Merge the 3 tables on the L.H.S( Confirmed,Recovered, Death together as I.e Consolidate the Data) . Since it's impossible to merge 3 tables together at once,merge the First two(2) Tables(confirmed & Recovered) then merge the lastly merged table with the last table(Death) to create a Consolidated Data. while on the Confirmed table go to Home>Merge Queries(merge queries as New) then Select the other table (Recovered); press Ctrl to select& merge columns( province/state, country/Region, date ) Since the Lat.,Long. are the same then ok.
On the L.H.S "Merge 1" Table is created while on the R.H.S ,  newly created column  named "Recovered" wass created.. At the "Recovered" column on the R.H.S ( Click the direction icon to unselect "All columns", check "Recovered",uncheck the "original column name as prefix" then ok. Hence newly "Recovered.1" column is created then rename it to "Recovered"
Merge the  "Merge.1" Table on the L.H.S  with the Death Table using the same procedure above then rename the "Death.1" created column as "Death" .
Rename the "Merge.1" Table as "ConsolidatedData"
Use the Text column Function  on date column so as to split the date and create separate columns for day, month,year respectively 
Use Pivot Table to generate every feature on the Dashboard 
You can be creative by applying all the steps above to create a different Dashboard using the Dataset  located on this repository files


