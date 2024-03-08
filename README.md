# sqlalchemy-challenge

This is a SQLAlhcemy challenge that tests skills in using ORM queries, pandas, and Matplotlib. The challenge analyzes two files hawaii stations and hawaii measurements that looks at station information, precipitation, and weather. 

The skills and tools used include creating engines and using functions like autobase to read databases and conduct analyses on the tables using python. A challenge I ran into was plotting the precipitation analysis. The x-ticks were overlapping and did not show the date. After receiving some assistance from a fellow class member, the solution was to divide the variable storing the yearly data over by 5 to create bins that each data point will fit into. This also allowes me show fewer dates. 

The other analysis was station analysis. Ultimately, we looked at the frequency of the weather over a period of time of the station with the most records. There was no issues plotting this data compared to the precipitation analysis.
