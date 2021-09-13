# US Domestic On-Time Performance by the Airlines, Origin Destination and by Days
## by Serdar Celebi


## Dataset

> The dataset consists of more than 7 million rows about the departue, landing, airtime, arrival delays, departure delays by origin and destination for the year of 2008. For the full 22 years of data between 1987 and 2008 make up 1.5GB of data so it is not possible for to be worked as a wholesome with the tools I have. 


## Summary of Findings

>I am most interested in figuring out if the delays are connected to a specific origin or destination also if there would be any attachment to a carrier or delays occur on a specific day of the week.

> There are 7,009,728 records of flight data in 2008 dataset recorded to show 29 different unique features of an on-time performance. Most variables are numeric time and time related variables recorded as floats should me converted to datetime type. Since the total size of all the files is 1.5 GB, despite trying to merge them under a single file was not successful. At this time it is not possible to do a time series analysis. Columns like CancellationCode, CarrierDelay, WeatherDelay, NASDelay, SecurityDelay, LateAircraftDelay missing around 5.5 million rows of data so even though they will not be in scope for this study, it is worth mentioning. DepTime (136246), ArrTime (151649),TailNum (83365), ActualElapsedTime (154699), AirTime (154699), ArrDelay (154699), DepDelay (136246), TaxiIn (151649), TaxiOut (137058) also amongst the columns that are missing data but not as bad as the first batch of the columns.

>DayOfWeek, DepTime, ArrTime, UniqueCarrier, AirTime, ArrDelay, DepDelay ,Distance, Origin and Dest columns would be the most important data for me to bring my analyses together.


## Key Insights for Presentation

> In the presentation, my main focus was "what" my features of interest (i.e delaying and canceling flights) are related to or may be affected by other features rather than "how" I come up with those visuals or conclusions.

## Data Glossary

### Variable descriptions

### Name	-----> Description
<p>1.	Year	1987-2008</p>
<p>2.	Month	1-12</p>
<p>3.	DayofMonth	1-31</p>
<p>4.	DayOfWeek	1 (Monday) - 7 (Sunday)</p>
<p>5.	DepTime	actual departure time (local, hhmm)</p>
<p>6.	CRSDepTime	scheduled departure time (local, hhmm)</p>
<p>7.	ArrTime	actual arrival time (local, hhmm)</p>
<p>8.	CRSArrTime	scheduled arrival time (local, hhmm)</p>
<p>9.	UniqueCarrier	unique carrier code</p>
<p>10.	FlightNum	flight number</p>
<p>11.	TailNum	plane tail number</p>
<p>12.	ActualElapsedTime	in minutes</p>
<p>13.	CRSElapsedTime	in minutes</p>
<p>14.	AirTime	in minutes</p>
<p>15.	ArrDelay	arrival delay, in minutes</p>
<p>16.	DepDelay	departure delay, in minutes</p>
<p>17.	Origin	origin IATA airport code</p>
<p>18.	Dest	destination IATA airport code</p>
<p>19.	Distance	in miles</p>
<p>20.	TaxiIn	taxi in time, in minutes</p>
<p>21.	TaxiOut	taxi out time in minutes</p>
<p>22.	Cancelled	was the flight cancelled?</p>
<p>23.	CancellationCode	reason for cancellation (A = carrier, B = weather, C = NAS, D = security)</p>
<p>24.	Diverted	1 = yes, 0 = no</p>
<p>25.	CarrierDelay	in minutes</p>
<p>26.	WeatherDelay	in minutes</p>
<p>27.	NASDelay	in minutes</p>
<p>28.	SecurityDelay	in minutes</p>
<p>29.	LateAircraftDelay	in minutes</p>
