# HOSPITALITY MANAGEMENT

Analysis of Revenue Loss in AtliQ Grands' Five-Star Hotels



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
    </tbody>
  </table>

</body>


## THE DATA SETS 

### Revenue
We can mainly use two datasets. One of the datasets contains information on both the revenue generated and the revenue realized from each property from May to June. Additionally, it includes data on the booking status, indicating from which platform customers booked the hotel. 

### Booking Details
The other datasets presents details on hotel bookings, capturing the count of successful bookings and the total room capacity for each room category within various properties on a daily basis. 
- [fact_aggregated_bookings.csv](https://github.com/sidiquegithub/HOSPITALITY-PROJECT/blob/main/DATA/fact_aggregated_bookings.csv)

  
## ANALYSIS
### Analysis On Revenue
Explore the code at the following links for analyzing total revenue, encompassing both generated and realized figures across cities, properties, and room categories. 

The following assessment provides both monthly breakdowns and an overall summary for the three-month period from May to July.
- [Revenue Month.ipynb](https://github.com/sidiquegithub/HOSPITALITY-PROJECT/blob/main/CODE/INITIAL%20ANALYSIS.ipynb)

The following will provide week wise analysis
- [Revenue Week.ipynb](https://github.com/sidiquegithub/HOSPITALITY-PROJECT/blob/main/CODE/ANALYSIS%20.ipynb)

## RESULTS AND SUGGESTIONS FROM ANALYSIS

### Revenue Genrated By Each City In Three Months


![download](https://github.com/sidiquegithub/HOSPITALITY-PROJECT/assets/110783832/93d1a158-11a9-4176-9216-c4de01b5ef2a)

Mumbai generated highest revenue followed by Banglore, Hyderabad, Delhi.

Each city generated an average revenue of 427192807.25 for the three months.

###### Consistency in Percentage of Revenue Realized:

Across all cities (Bangalore, Delhi, Hyderabad, Mumbai), the percentage of revenue realized with respect to revenue generated is consistently around 85%. This suggests a common trend of achieving approximately 85% realization of the generated revenue.

### SUGGETIONS
The 85% benchmark can serve as a reference for evaluating future performance. Cities with percentages below this benchmark may need attention to enhance their revenue realization processes.

Analyzing the factors contributing to the 15% difference between generated and realized revenue could uncover opportunities for optimization. 

### Revenue Genrated By Each Property In Three Months


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

