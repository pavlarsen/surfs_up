# Surfs Up

## Overview of Project

### Evaluated the viability of the project Surfs Up: opening a new site for a business focused on Surf and Ice Cream parlor. Analyzed weather data to be sure the place will have the best temperature to attract visitors. For this project I used SQLite, analyzed the data in Jupyter Notebook, transformed the data into Pandas Data Frame for better appreciation of the data and performed queries to extract specific information regarding the months of June and December.

---

## Analysis Results

Key findings summary:

![Captura de pantalla 2022-11-19 a la(s) 12 24 56](https://user-images.githubusercontent.com/113866707/202902882-55cae7b0-f772-4d49-82df-c2b029d97917.png)

![Captura de pantalla 2022-11-19 a la(s) 12 25 06](https://user-images.githubusercontent.com/113866707/202902898-49d0ca4e-4e60-4f0d-8925-ab6595328286.png)

So, June and December are the most important months for Hawaii to receive tourists due to the vacation period from mainland. For the new Surfs Up site to succeed it would be important that it can get visitors and maximize attendance during peak season. Fortunately, for this new site, we can conclude that regarding temperature (which is one of the main factors for visitors to choose a surf place) is relatively standard comparing June and December. June has an average temperature of almost 75 degrees while in December we have 71 degrees. Historic max temperatures also rely within the same range: 85 degrees for June and 83 degrees for December. December could get a little colder than June, we can see this when evaluating the minimum historical temperature which is 8 degrees lower than the minimum historical temperature from June.

    
---

## Summary

The location selected for the new project, in terms of temperature, benefits from a similar weather during the most important periods of the year for visitors: June and July. With samples above 1500 of historical weather data, we can conclude that the temperature is quite similar on both months. In both months, historical average temperature is above 70 degrees. In order to analyze other important factors, I would suggest these two queries:

- Waves heights query: In order to evaluate one of the important aspects for surfers which is waves heights, it would be important to query information regarding wind speed, wind duration and fetch from the site during these two months. This way the company can be sure the location also keeps its attractive natural resource running all year long.

- Precipitation query: Surfers typically do not mind surfing during rainy days, however for the Ice Cream business, it would be important to determine how rainy is the site and how it will affect ice cream sales. This information would also help them determine how much of the product to buy and be more cost effective during slower season for ice cream.
