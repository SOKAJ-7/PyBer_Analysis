# PyBer_Analysis

## Project Overview
The purpose of this project is to perform exploratory data analysis on a data set for a ride-sharing company named 'PyBer'. The analysis was centered on visualizing the relationship between ride fares and other variables such as city type, date, driver counts, and ride counts. Using this data, we were able to create and visualize a pivot table which demonstrated the average fare payed by PyBer customers over the course of January through April in 2019. The fares were distinguished based on the type of city each ride occurred in: rural, suburban, or urban. This data provides a starting point to analyzing which times of the year may see the highest revenues from fares and adjust business strategy accordingly.

## Results
Upon looking at the 'pyber_summary_df' created in this project, it is clear that urban cities provide the most revenue through fares. Interestingly, the average fare per driver and average fare per ride are also the least expensive in urban areas. In Rural areas this relationship is reversed. Total fares are much lower compared to that of urban areas but average fares are comparatively higher. The suburban ride data represents a good intermediate between the rural and urban data. 

The relationship between city type and average fares seem to be influenced by the total driver counts as well as ride counts. In areas where the total number of drivers and rides are lower, average ride fares tend to be higher which may disuade customers to use ride-sharing apps such as 'PyBer'. This is a likely cause for why total fares are significantly lower in rural areas and to a lesser degree, suburban areas when compared to the total fares seen in urban areas. A table summarizing these trends can be seen below (Figure 1).

![Pyber_summary_good](https://user-images.githubusercontent.com/93050931/144760401-597863e1-4c72-48d2-85d7-43715942e6f5.PNG)


(Figure 1)


## Summary
The main cause of the disparity between rural and urban areas seem to be caused by the factors referenced above in the 'Results' section. One way to combat this issue is to slighly increase the fares in urban areas in order to subsidize lower fares in rural areas. In urban areas, 'PyBer' is rather well-established and unlikely to lose much business over a slight increase in fare prices. However, in rural areas the newly decreased fares could help in getting 'PyBer' to gain popularity and be seen as a more inexpensive way to get around the city compared to other alternatives.

Another reason that could be causing rural areas to have lower total fares is that the number of drivers are significantly lower in rural areas when rural areas are already larger in general than urban areas. So, not only are rides more expensive in rural areas, it may also take more time to actually be picked up by one's driver. This may cause potential customers to see 'PyBer' as not only expensive but also inconvenient. This can be changed by increasing driver recruitment in rural areas to decrease wait times for rural customers. This policy may not be popular amongst drivers as there will initially be increased competition for rides, thus affecting their earning potential. If this policy is enacted, it may be worthwhile to implement a basic hourly wage so that drivers can maintain their earnings while 'PyBer' gains popularity in rural areas. I believe this may be neccessary as if it becomes too much of a burden to drive for 'PyBer', we could see increased demand for ride-sharing but have nobody willing to carry out our service. Further data will be needed to analyze the costs and benefits of this suggestion.

Another solution worth exploring is a marketing campaign in rural areas. Customers may not see the benefit of our service when most people in rural areas already own their own vehicles due to the sparse nature of their cities. With that in mind, it's likely that most of PyBer's business in rural areas will be from people who are unable to drive, oftentimes from being intoxicated. If 'PyBer' were able to get data regarding the number of impaired driving charges by region. We could tailor advertisements to focus on decreasing the incidence of impaired driving. We could also run promotions where fares will be lower on weekends when impaired driving is more likely to be seen. Not only does this solution have the potential benefit of increasing revenes in rural areas. It hopefully will also contribute to increasing the safety of the neighborhoods in which we operate, therby generating public goodwill for PyBer.



