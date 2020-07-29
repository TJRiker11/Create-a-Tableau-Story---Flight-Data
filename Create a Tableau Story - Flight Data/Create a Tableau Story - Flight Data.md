# Create a Tableau Story - Flight Data

> Full Tableau profile can be seen [Here](https://public.tableau.com/profile/trikerdev).

> This dataset is collected from the United States Department of Transportation on flight delays from January 2010 to December 2019. The original dataset can be seen and download from [Here, On-Time Arrival Performance
National (January, 2010 - December, 2019)](https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp?pn=1).

> The full dataset used and all other project files can be seen in [This Github Repository](https://github.com/TrikerDev/Create-a-Tableau-Story---Flight-Data).

[Rough Draft](https://public.tableau.com/profile/trikerdev#!/vizhome/AirlineDataRoughDraft/DelayTypes)

[Final](https://public.tableau.com/profile/trikerdev#!/vizhome/AirlineDataFinal/FinalStory)

## Causes of Delay

Airlines that report monthly numbers of flight delays to the BTS began reporting information on causes of delays in June 2003. The airlines report the causes of delays in five broad categories:

>* **Air Carrier**: The cause of the cancellation or delay was due to circumstances within the airline's control (e.g. maintenance or crew problems, aircraft cleaning, baggage loading, fueling, etc.).

>* **Extreme Weather**: Significant meteorological conditions (actual or forecasted) that, in the judgment of the carrier, delays or prevents the operation of a flight such as tornado, blizzard or hurricane.

>* **National Aviation System (NAS)**: Delays and cancellations attributable to the national aviation system that refer to a broad set of conditions, such as non-extreme weather conditions, airport operations, heavy traffic volume, and air traffic control.

>* **Late-arriving aircraft**: A previous flight with same aircraft arrived late, causing the present flight to depart late.

>* **Security**: Delays or cancellations caused by evacuation of a terminal or concourse, re-boarding of aircraft because of security breach, inoperative screening equipment and/or long lines in excess of 29 minutes at screening areas.

How are flight delays calculated?

> A flight is counted as "on time" if it operated less than 15 minutes later than the scheduled time shown in the carriers' Computerized Reservations Systems (CRS). Arrival performance is based on arrival at the gate. Departure performance is based on departure from the gate.

> A flight is considered delayed when it arrived 15 or more minutes later than the scheduled time. Delayed minutes are calculated for delayed flights only. When multiple causes are assigned to one delayed flight, each cause is prorated based on the delayed minutes it is responsible for. The displayed numbers are rounded and may not add up to the total.

## Feedback from Rough Draft

What do you notice in the visualization?

> The things that catch my eye the most are the map views and the bubble charts. Some of the other data visualizations are more bland and could be added to.

What questions do you have about the data?

> Why does Southwest have so many late flights? Is it just because they have more flights than all the others, or is there actually something else causing a higher volume of late flights?

What relationships do you notice?

> This is back on Southwest airlines. Why are there so many late flights? Is it just because they have more flights? So More Flights = More Late Flights? Or what else is happening? Its very cool to see which areas have more weather delays and cancellations and which areas dont. Seeing how the actual geography and weather areas affect the airports is neat. Seeing which carriers call off the most flights for carrier reasons is intersting.

What do you think is the main takeaway from this visualization?

> I think the questions that were asked about the data were answered. There could just be more detail and cleaner data visualizations.

Is there something you don’t understand in the graphic?

> The map view of the United States is cool and informative but its only the mainland US and there are other areas that are excluded from the view. The filters are too messy and take up too much room on the page. The legends dont properly explain the data.

## Changes

> The changes I made based on the feedback was a lot of cleaning things up and making them more readable. First, I put everything into a story presentation view so it would be easier to view and understand as the user clicks through the pages. I streched the graphs to get as much detail as possible on the page to see. Added and changed legends to explain more detail of the graphs. Changed the filters so one filter controls an entire page of charts, rather than one filer per chart. This was you can change the filter in one place, and it affects all graphs. Added more details to possibly explain certain outcomes, like more flights per carrier could equate to more delays etc. Added more details to maps and more map views. Added a percentage view to the late airlines data to show that some carriers have a higher or lower percentage of total late flights, no matter how many total flights they have. Added text data numbers for each data point explored, so along with the visualizations, there are also hard data numbers to reference and compare.

## Purpose : The Questions

> I had several questions that I wanted to answer when I started this project. Those questions were:
>* What are the main causes of delay by year and month?
>* Which areas get the most weather delays?
>* Which carriers call the most carrier cancellations and delays?
>* Which carriers have the most late aircraft?

## Answers

What are the main causes of delay by year and month?

> The main cause of delay over all time periods are Late Aircraft delays. These make up the vast majority of all delays. Next comes Carrier delays, followed NAS delays, followed by Weather delays. Then the most uncommon type of delay is a Security delay. This order remains constant over all time periods of months and years. There is an increase in weather delays around winter months, December - February or so, but it is really not much of an increase and does not change the order of any types of delays. Late Aircraft delays are always the most common.

Which areas get the most weather delays?

> The three airports with the most weather delays are Chicago O'Hare, Dallas/Fort Worth, and Hartsfield-Jackson. These three airports have actually the vast majority of all weather delays and cancellations out of all airports reported. The top 4 airports for weather delays, which includes Denver International as well, are the only 4 airports to have over 1 million weather delays. Chichago O'Hare is actually only 65,000 delays away from 2 million total, at the time of reporting.

Which carriers call the most carrier cancellations and delays?

> The carrier that calls the most delays and cancellations is Southwest Airlines. They have had 34.5 million delays at the time of reporting, compared to 2nd most Delta Airlines at 28.2 million.

Which carriers have the most late aircraft?

> The carrier with the most late aircraft by far is Southwest Airlines, which also takes up a significant portion of the percentage for late aircraft - 27%. SkyWest airlines also makes a jump here, having many late aircraft in relation to their total flights. SkyWest has typically been 4th on the list but makes a jump up to 2nd for the total number of Late Aircraft. Southwest has by far the most at 61.4 million, but SkyWest makes the jump to second at 34.5 million.
