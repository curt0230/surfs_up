# Surfs Up Surf Shop Weather Analysis
## Project overview
The purpose of this project was to perform an exploratory analysis of weather on the Hawaiian island of Oahu.  This information can be used  to determine the feasibility of opening a year-round surf shop.


## Resources
* Software:  Python 3.9.7, Anaconda 4.12.0, Jupyter Notebook 6.4.5, SQLite
* Data sources:  
  * [hawaii.sqlite](https://github.com/curt0230/surfs_up/blob/main/hawaii.sqlite)

## Analysis
Weather data collected and stored in a SQLite database format was used to perform this analysis.  This data was filtered by month and aggregated to create temperature statistics.  

## Results
The following summary of June temperatures and December temerpatures around Hawaii demonstrates a consistently comfortable temperature pattern year-round:

![summary.png](/summary.png)

Here are some key points:
* The mean temperature remains consistently in the low- to mid-seventies.
* Max temperatures are also similar in the low- to mid-eighties.
* Minimum temperatures, representing night time lows, mark the greatest difference at approximatly eight degrees.
* The temperatures 25th percentile are near those in the 50th percentile, indicating that those cold nights are few and far between.

Exploring trends over time we can see that temperatures remain fairly consistent in Hawaii year-round.  The biggest variance happens during the night time when the temperature drops with the sun.  This change would occur likely outside business hours and doesn't represent a threat to the business plan.

Overall, this analysis indicates a favorable weather outlook for driving business at a year-round surfing and ice cream shop.  However, additional weather data points that warrant further exploration include rainfall totals and cloud cover during the same period of time.  Hardcore surfers might don a wetsuit if it gets chilly, but storms may keep them out of the water.  Also, variances between weather stations could be compared to determine if there are any spots that are slightly sunnier.
