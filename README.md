<p align="center">
  <img src="header.png" width="800" height="300" />
</p>

# Air Flights Delay Data Analysis Project by tableau

## Summary:
Delay is one of the important problems that affect any transportation systems performance. This project focuses on airplane flights delays and tries to understand what's the factor affect this performance. Delay represented by the difference between actual and scheduled time of departure or arrival of a flight.
This dataset contains information on United State flight delays and performance comes from RITA. 
[Source](https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp?pn=1)

## Main findings :
    1. The flight delay time is changed over the year. The maximum percentage comes
    from 2007 by 9.33% and the minimum comes from 2003 by 2.17%.
    2. There is a significant difference between the total of canceled and diverted flights.
    3. The highest factor affects the flight delay is the arrival delay and the lowest is
    security.
    4. The highest airport in total delay time is Chicago international airport.
    5. The highest carrier in the total delay time is Southwest Airlines.

## Design:
### The first version :
     1) In this version, I try to ask any question that will be answered during visualization.
        ● How is the general flight performance over the years? Are this performance increased or decreased?
        ● What're the factors effect by this performance? what is the highest affect factor?
        ● What are the factors affect the airports?
        ● What is the factors effect on the carrier?
    2) I started the project by changing the column names to make it easy to read.
    3) There are 4 dashboards represented as story pages :
        ● The first one contains general information about the project and the dataset.
        ● The second page contains 2 charts ( delay over the year in the minute) and (causes
          of delay filtered by the year)
        ● The third page contains 2 charts ( causes of delay in the airport ) and ( causes of delay in the carrier)
        ● The last page contains a map that represents the airports as points and the size of this point represent the total amount of delay.
    4) I decided to design the charts without providing any information and get feedback about it to sure if it readable and easy or not.
[The version link:](https://public.tableau.com/profile/malak8698#!/vizhome/v2_62/Story1)

### The final version :
#### Changes: 
##### Chart1:
    1) Change the minute to hours to make the comparison easier to read and understand.
    2) Change title (Delay over the year in hours).
    3) Mention the note ( Hover on the line to see more details ).
##### Chart2:
    1) Change the Average to percentage.
##### Chart3:
    1) Change the Average to percentage.
    2) Mention the note ( you can filter the result by using airport name and year).
##### Chart4:
    1) Change the Average to percentage.
    2) Mention the note ( you can filter the result by using carrier name and year ) .
##### Chart5:
    1) Add description about the airport map.
    2) Mention the note (The bigger point the represent the high total time).

##### Change in chart 2 and 3 and 4 the axis name ( value ) to appropriate name

### Additions:
    1) Change the story title to project title.
    2) Add titles and more descriptions.
    3) Add the note (Please choose one box from the filter) on the map.
    4) Add the note (Sorry, there is no data for this filter)
    5) Add the chart canceled and diverted flights number over the years.
    6) Add chart represents the most 10 airports in the delay filtered by year.
    7) Add cancelled and diverted flight number based on the airport.
    8) Add chart represents the most 10 carrier in the delay filtered by year.
    9) Add map represent weather affect.
        - The weather is affected by the geographic location so this map represents the relationship between the weather delay and airport location.


### Design decisions:
    1) Change the story background.
    Many feedback mention the full white space make the light of the page strong, so I changed the story background to light blue because         the blue is a cold color that makes the page look good.
    2) I chose the red color to represent the flights delayed and canceled because the red color mean the error or worst scenario.
    3) I filtered the Airports and Carrier data color to make it easy to the comparison.
    
[The version before review link:](https://public.tableau.com/profile/malak8698#!/vizhome/Finalv/AirFlightsDelayDataAnalysisProject)

[The version after review link:]( https://public.tableau.com/profile/malak8698#!/vizhome/Afterreview/AirFlightsDelayDataAnalysisProject)


## Feedback:
In this stage, I tried to ask many people with differences in educational background, age, the experience of data analysis, gender. This decision helps me to cover a larger area of the project problems. The table below shows some of the feedback :

| Person | General Information                                                     | Q1:What do you notice inthe visualization?                                                                                                                                                                                                          | Q2:Is there something youdon’t understand in thegraphic?                                                                                                                                                                                       | Q3:If I give you this datawhat's the first thingyou want to know                                                                                                                                                                              |
|--------|-------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  1     | High school Age:44 No experience of data analysis Female                | The delay changed over the year. The most factor effect on delay is (arrival delay)                                                                                                                                                                 | What is the size of the points of the map? is this size represent airport size?                                                                                                                                                                | Knowing the problem is not enough I want to make a decision about how can we handle this problem.                                                                                                                                             |
| 2      | Master degree Age:34 Some experience of accounting data analysis Female | Delay increased and decreased over the years,2010 have the least amount of the delay,The most factor effect on delay is (arrival delay) and the least wither and security.,There are a list of Airports and Carrier and the factors affect on them. | What is the security mean? Airplane security (maintenance time) for Airport security? or both?                                                                                                                                                 | I want to know what is the worst Airport and investigate the reason of this delay based on the airport characteristic if the airport is local definitely the dealy time is less the international  airport. What are the costs of this delay? |
| 3      | PhD Age: 32 Expert on medical data analysis Male                        | -                                                                                                                                                                                                                                                   | Why you use the minute as a scale in the  calculation? Why you used theaverage on the calculation?                                                                                                                                             |  Is the geographical location of the airport affect on the flight delay? What is the quality of the carrier services? is there any improvement of their services over the years?                                                              |
| 4      | High school Age: 18 No experience of data analysis Male                 | -                                                                                                                                                                                                                                                   |  In chart 4 (causes of delay in the carrier) why there is a carrier delay bar? The x-axis tick title is not clear until hover it He mentions it is difficult to read the chart when the background color is white inside the chart and out it. |  What are the services that carrier provided to the passengers when the flight delay?  What is happening when the delay time is long is the flight canceled or changed to another time?                                                       |

## Resources:
[transtats.bts.gov](https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp?pn=1)

[transtats.bts.gov](https://www.bts.dot.gov/explore-topics-and-geography/topics/airline-time-performance-and-causes-flight-delays)

[wikipedia](https://en.wikipedia.org/wiki/Chicago)

[wikipedia](https://en.wikipedia.org/wiki/Southwest_Airlines)


