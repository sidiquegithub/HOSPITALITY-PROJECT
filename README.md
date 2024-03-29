# HOSPITALITY MANAGEMENT

Analysis of Revenue Loss in AtliQ Grands' Five-Star Hotels

![image](https://github.com/sidiquegithub/HOSPITALITY-PROJECT/assets/110783832/9d717eca-398e-4a56-bbcf-98af7d700bae)





## OVERVIEW
AtliQ Grands, a prominent player in the hospitality industry, is currently experiencing a decline in revenue for its five-star hotels. This analysis aims to thoroughly investigate and understand the factors contributing to this revenue loss, enabling stakeholders to make informed decisions for strategic improvements.

## AtliQ Grands
Atliq Grands owns a collection of 25 five-star hotels situated in Mumbai, Delhi, Hyderabad, and Bangalore of India.

### Peoperties
<body>

  <table>
    <thead>
      <!-- Add a large row with the title "PROPERTY ID" above the header row -->
      <tr>
        <td colspan="8" style="font-weight: bold; text-align: center; color: blue;"> PROPERTY ID</td>
      </tr>
      <!-- Existing rows -->
   </thead>
    <tbody>
      <tr>
        <th></th>
        <th colspan="4">LUXURY</th>
        <th colspan="3">BUSINESS</th>
      </tr>
      <tr>
        <td rowspan="2">Property Name / City</td>
        <td rowspan="2">Atliq Grands</td>
        <td rowspan="2">Atliq Exotica</td>
        <td rowspan="2">Atliq Blu</td>
        <td rowspan="2">Atliq Bay</td>
        <td rowspan="2">Atliq City</td>
        <td rowspan="2">Atliq Palace</td>
        <td rowspan="2">Atliq Seasons</td>
      </tr>
      <tr></tr>
      <tr>
        <td>Delhi</td>
        <td>16558</td>
        <td></td>
        <td>16561</td>
        <td>16562</td>
        <td>16560</td>
        <td>16563</td>
        <td></td>
      </tr>
      <tr>
        <td>Mumbai</td>
        <td>17558</td>
        <td>16559,17559	</td>
        <td>17561</td>
        <td>17562</td>
        <td>17560</td>
        <td>175634</td>
        <td>17564</td>
      </tr>
      <tr>
        <td>Hyderabad</td>
        <td>18558</td>
        <td>18559</td>
        <td>18561</td>
        <td>18562</td>
        <td>18560</td>
        <td>18563</td>
        <td></td>
      </tr>
      <tr>
        <td>Bangalore</td>
        <td>19558</td>
        <td>19559</td>
        <td>19561</td>
        <td>19562</td>
        <td>19560</td>
        <td>19563</td>
        <td></td>
      </tr>
    </tbody>
  </table>

</body>


### Types of available rooms

<body>

  <table>
    <thead>
      <tr>
        <th>Room ID</th>
        <th>Room Class</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>RT1</td>
        <td>Standard</td>
      </tr>
      <tr>
        <td>RT2</td>
        <td>Elite</td>
      </tr>
      <tr>
        <td>RT3</td>
        <td>Premium</td>
      </tr>
      <tr>
        <td>RT4</td>
        <td>Presidential</td>
      </tr>
    </tbody>
  </table>

</body>






## THE DATA SETS 

### Revenue
We can mainly use two datasets. One of the datasets contains information on both the revenue generated and the revenue realized from each property from May to June. Additionally, it includes data on the booking status, indicating from which platform customers booked the hotel. 

### Booking Details
The other datasets presents details on hotel bookings, capturing the count of successful bookings and the total room capacity for each room category within various properties on a daily basis. 
- [fact_aggregated_bookings.csv](https://github.com/sidiquegithub/HOSPITALITY-PROJECT/blob/main/DATA/fact_aggregated_bookings.csv)

  



## ANALYSIS (PYTHON CODE)
### Analysis On Revenue
Explore the code at the following links for analyzing total revenue, encompassing both generated and realized figures across cities, properties, and room categories. 

The following assessment provides both monthly breakdowns and an overall summary for the three-month period from May to July.
- [Revenue Month.ipynb](https://github.com/sidiquegithub/HOSPITALITY-PROJECT/blob/main/CODE/INITIAL%20ANALYSIS.ipynb)

The following will provide week wise analysis
- [Revenue Week.ipynb](https://github.com/sidiquegithub/HOSPITALITY-PROJECT/blob/main/CODE/ANALYSIS%20.ipynb)






## RESULTS AND SUGGESTIONS FROM ANALYSIS

## REVENUE FOR THREE MONTHS


#### Results 1: Revenue Genrated By Each City In Three Months
---------------------------------------------------------------------------------------


![download](https://github.com/sidiquegithub/HOSPITALITY-PROJECT/assets/110783832/93d1a158-11a9-4176-9216-c4de01b5ef2a)

Mumbai generated highest revenue followed by Banglore, Hyderabad, Delhi.

Each city generated an average revenue of 427192807.25 for the three months.


###### Consistency in Percentage of Revenue Realized:

Across all cities (Bangalore, Delhi, Hyderabad, Mumbai), the percentage of revenue realized with respect to revenue generated is consistently around 85%. This suggests a common trend of achieving approximately 85% realization of the generated revenue.


#### Suggestions
The 85% benchmark can serve as a reference for evaluating future performance. Cities with percentages below this benchmark may need attention to enhance their revenue realization processes.

Analyzing the factors contributing to the 15% difference between generated and realized revenue could uncover opportunities for optimization. 



#### Results 2: Revenue Genrated By Each Property In Three Months
-----------------------------------------------------------------------------------

![download](https://github.com/sidiquegithub/HOSPITALITY-PROJECT/assets/110783832/9a75f139-a3a7-44b5-bc22-bb6b03054394)

Atliq Exotica in Mumbai generated the highest revenue for the three months.
Atliq Grands in Delhi generated the lowest revenue for the three monnths.

The mean revenue generated by each property for the three months is 80301848.6

###### Distribution of revenue realised with respect to revenue generated for each property
![download](https://github.com/sidiquegithub/HOSPITALITY-PROJECT/assets/110783832/29c0786b-31e7-4ec7-9dbf-19c88f7a213f)


The percentage of revenue realized with respect to revenue generated is low for the following properties
 <body>

  <table>
    <thead>
      <tr>
        <th>Property ID</th>
        <th>Property Name</th>
        <th>Category</th>
        <th>City</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>3</td>
        <td>16561</td>
        <td>Atliq Blu</td>
        <td>Delhi</td>
      </tr>
      <tr>
        <td>5</td>
        <td>16563</td>
        <td>Atliq Palace</td>
        <td>Delhi</td>
      </tr>
      <tr>
        <td>6</td>
        <td>17558</td>
        <td>Atliq Grands</td>
        <td>Mumbai</td>
      </tr>
      <tr>
        <td>8</td>
        <td>17560</td>
        <td>Atliq City</td>
        <td>Mumbai</td>
      </tr>
      <tr>
        <td>10</td>
        <td>17562</td>
        <td>Atliq Bay</td>
        <td>Mumbai</td>
      </tr>
      <tr>
        <td>17</td>
        <td>18563</td>
        <td>Atliq Palace</td>
        <td>Hyderabad</td>
      </tr>
      <tr>
        <td>20</td>
        <td>19560</td>
        <td>Atliq City</td>
        <td>Bangalore</td>
      </tr>
      <tr>
        <td>23</td>
        <td>19563</td>
        <td>Atliq Palace</td>
        <td>Bangalore</td>
      </tr>
    </tbody>
  </table>

</body>




#### Result 3: Revenue From Each Room For Three Months
----------------------------------------------------------------------------------------
![download](https://github.com/sidiquegithub/HOSPITALITY-PROJECT/assets/110783832/f40f655a-b1ab-4211-82f4-f358f60792ec) 

RT2 and RT3 (Elite and Premium) are the best performing room categories, while RT1 (Standard) is the least performing one.

Mean revenue generated by each room catagory for the three month is  427192807.25

-------------------------------------------------
## REVENUE FOR EACH MONTHS
------------------------------------------------------

#### Result 4: Total Revenue In Each Month
------------------------
<table>
    <thead>
        <tr>
            <th>Month</th>
            <th>Revenue Generated</th>
            <th>Revenue Realized</th>
            <th>Revenue Difference</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>May</td>
            <td>683,882,555</td>
            <td>581,930,666</td>
            <td>101,951,889</td>
        </tr>
        <tr>
            <td>June</td>
            <td>651,939,535</td>
            <td>553,932,355</td>
            <td>98,007,180</td>
        </tr>
        <tr>
            <td>July</td>
            <td>671,724,125</td>
            <td>572,908,208</td>
            <td>98,815,917</td>
        </tr>
    </tbody>
</table>

The revenue difference in the month of May is quite high compared to that of June and July.


#### Result 5: Revenue  by each city, each property, and each room category on a monthly basis
------------------------
![download](https://github.com/sidiquegithub/HOSPITALITY-PROJECT/assets/110783832/cb93ff64-9c51-43a3-b3ed-382c6332e0aa) 



![download](https://github.com/sidiquegithub/HOSPITALITY-PROJECT/assets/110783832/c6866eb6-8380-4dcb-b186-ae844e22c1e9)

![download](https://github.com/sidiquegithub/HOSPITALITY-PROJECT/assets/110783832/d51b2fc7-aac8-4ef1-adb9-427c1339e631)

We observe a consistent pattern in the monthly revenue across each city, property, and room category: revenue peaks in May, dips in June, and then settles at a level between the two in July
