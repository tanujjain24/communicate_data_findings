# Bay Wheels Bike Sharing System  2018

## Dataset
[Bay Wheels](https://en.wikipedia.org/wiki/Bay_Wheels) (previously known as Ford GoBike) is a regional public bike sharing system in California's San Francisco Bay Area. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States with nearly 500,000 rides since the launch in 2017 and had about 10,000 annual subscribers as of January 2018. The dataset used for this exploratory analysis consists of monthly individual [trip data](https://www.lyft.com/bikes/bay-wheels/system-data) from January 2018 to December 2018 in CSV format covering the greater San Francisco Bay area, also available [here](https://s3.amazonaws.com/baywheels-data/index.html).


## Summary of Findings
During the exploration it was observed that the most number of trips peaked around 8-9 am and 5-6 pm during the day, there were more trips on workdays (Mon-Fri) compared to weekends. Summer was the most popular season of the year, likely due to the weather. The riding trips tend to be shorter on Monday through Friday compared to weekends. It indicates a pretty stable and efficient usage of the bike-sharing system on normal workdays, while more casual flexible use on weekends. There is more Subscriber usage than customers. The riding habit/pattern varies a lot between Subscribers and Customers. Subscribers use the bike-sharing system for work commute thus most trips were on workdays (Mon-Fri) and especially during rush hours (when going to work in the morning and getting off work in the afternoon), whereas Customers tend to ride for fun in the afternoon or early evenings over weekends. Subscriber usage peaks out on typical rush hours when people go to work in the morning and getting off work in the afternoon, which strengthened their usage purpose and goal of riding. A similar pattern was not observed among Customers who tend to ride mostly in the afternoon or early evening for a different purpose than the subscribers.

## Key Insights for Presentation
Different usage patterns between the two types of riders were seen from the exploration. Subscribers use the system heavily on workdays i.e. Monday through Friday whereas Customers ride a lot on the weekends, especially in the afternoon. Many trips concentrated around 8-9 am and 5-6 pm on workdays for Subscribers, yet Customers tend to use more in the late afternoon around 5 pm Monday to Friday. The efficient/short period of usage for Subscribers corresponds to their high concentration on rush hours Monday through Friday, indicating the use is primarily for the work commute. The more relaxing and flexible pattern of customer use shows that they're taking advantage of the bike-sharing system quite different from the subscribers, heavily over weekends and in the afternoon, for city tour or leisure purpose probably.

## Webliography
- [Bay Wheels](https://en.wikipedia.org/wiki/Bay_Wheels)
- [Udacity Dataset Options](https://docs.google.com/document/d/e/2PACX-1vQmkX4iOT6Rcrin42vslquX2_wQCjIa_hbwD0xmxrERPSOJYDtpNc_3wwK_p9_KpOsfA6QVyEHdxxq7/pub?embedded=True)
- [Data Descrition](https://www.lyft.com/bikes/bay-wheels/system-data)
- [Dataset Source](https://s3.amazonaws.com/baywheels-data/index.html)
- [pandas](https://pandas.pydata.org/docs/)
- [Seaborn](https://seaborn.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [StackOverflow](https://stackoverflow.com/)
- [Udacity Knowledge Center](https://www.udacity.com/)