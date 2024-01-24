# Yulu - Hypothesis Testing

## About YULU

Yulu is India's leading micro-mobility service provider.
Founded with a mission to eliminate traffic congestion in India.
Offers unique and sustainable transportation solutions for daily commutes.
Provides shared electric cycles for a convenient and eco-friendly commute.
Yulu zones are strategically located at various points, including metro stations, bus stands, offices, residential areas, and corporate offices.
A user-friendly mobile app facilitates shared, solo, and sustainable commuting.
Active in the Indian market, contributing to the local transportation ecosystem.

## Insights and Recommendations

1) **EDA based insights** - 
    - Total 10,886 rows were present in the data set.
    - Neither missing values, nor duplicate rows were found.
    - 'temp' and 'atemp' columns were found to be highly correlated. Dropping one of them (atemp) to avoid multicollinearity.
    - 'count', 'casual' and 'registered' columns were highly correlated. Dropping casual & registered columns to avoid multicollinearity.
   - Outlier values were found in the 'count' column.
   - The total time period for which the data is given is '718 days 23:00:00'.
2) **Insights from hypothesis testing** -
   - There is no significant difference between the mean number of bike rides on weekdays and weekends
   - There is no significant difference between the mean number of bike rides on holidays and non-holidays
   - The demand of bicycles on rent differs under different weather conditions.
   - The demand of bicycles on rent is different during different seasons.
   - The weather conditions are surely dependent upon the ongoing season.
   - During sunny weather more number of bikes are rented compared to other weathers like rainy, cloudy, snow, cloud
   - During fall seasons more number of bikes are rented comared to winter, summer and spring
   
3) **Generic recommendations** -
     - Investigate whether certain weather conditions are more common during specific seasons due to geographical or climate factors.
    - The demand of bikes on rent are usually higher during Weekdays.
    - The demand of bikes on rent are usually higher during Regular days.
    - The chances of person renting a bike are usually higher during Season fall.
    - The chances of person renting a bike are usually higher during Weather condition 1.
    - We recommend the company to maintain the bike stocks accordingly.
    - Inform the general public about the statistical relationship between weather and seasons. This could be relevant for clothing retailers, outdoor activity organizers, and individuals planning seasonal events.
    
