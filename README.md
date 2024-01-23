# HOSPITALITY MANAGEMENT

Analysis of Revenue Loss in AtliQ Grands' Five-Star Hotels

<\br>

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


