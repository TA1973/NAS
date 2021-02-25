# Assessment 
National Weather Service 

## Assignment
Write an ASP.Net web application that will consume an API from the National Weather Service to display weather information for NYC:
1.	Your page layouts and format should be displayed using a CSS
2.	Create a login page with username/password
3.	Retrieve the predefined username/password, as a bonus retrieve the username/password from a database of your choice
4.	Authenticate the credentials, if successful move to the next page, if not successful display an error message
5.	Consume the following API from the National Weather Service: https://api.weather.gov/gridpoints/TOP/33,36/forecast
6.	Display the temperature, temperature unit, windspeed, windDirection for the third period (number:3)
7.	Have a Logout button that will return you back to the login screen
8.	upload the code to your GitHub for review by an Audubon Engineer


### Solution
Solution and Project are contained within the Zip file and can be opened with Visual Studio
Local Database was utilized for Registration and Login mdf file is included in zip file as well as
I didn't really know how to include the database. The connection string is in the Web.Config file if the
database is recreated and the connection string needs changed. It is pretty generic for a localDB using Visual Studio.
Data Source=(localdb)\MSSQLLocalDB;Initial Catalog=NationalWeatherService;Integrated Security=True" />
Script to recreate the table is also included in case you want to put the table in your own database instead.

#### Timing
I worked on this throughout the day and unfortunately due to a hit and run causing property damage at my house 
I did not have time to do it all in one sitting but overall I spent approximately 45 minutes doing the assignment
The assignment contains what was asked for - At the last minute I threw in some extra javascript functionality and
the abiity to change what number of weather you are looking for. 

````
