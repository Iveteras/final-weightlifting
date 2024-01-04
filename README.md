# A Study about Weightlifting

This is a simple study about weightlifting and its main datas.

##  Technologies used

- Pandas: data manipulation
- Selenium and Beautifulsoup: web scraping
- Excel: data storage
- Power Bi: dashboards

## Logic about the project

**Phase 1 (folder - scripts):**

- **First step (script - event_year_scraping):** it was necessary to create a dataframe with each event id so that when I have to collect information about the events in the main dataframe, I can use the id as the key of the both dicts.
- **Second step (script - scraping):** basically i studded the html structure of the page and than i made a loop for search two types of URL (the old and the category), using the ids of the data frame made on the step above. After that i created the main dataframe.

**Phase 2 (folder - analytics):**

- **First step (script - preparing_df):** nothing much, just fixed and added some data that was out of order
- **Second step (script - analytics):** i calculated the correlation between each lift and total with age and body weight

**Phase 3 (folder - dashboard):**

- Built the dashboard

## Dashboards

This first screen shows a summary with the main placements and achievements of each athlete. You can search for one athlete at a time, but you can search for any professional athlete in the world.

![main dashboard](https://github.com/Iveteras/final-weightlifting/assets/111463787/638dee37-bb7c-4c18-8e64-78b4317032d7)

This second screen shows some insights about the weightlifting evolution and the correlation between total weight lifted between bodyweight and age. It also shows the relationship between the weight lifted divided by bodyweight.

![second dashboard](https://github.com/Iveteras/final-weightlifting/assets/111463787/9971cfb3-22cb-41fe-9a93-49df07cd1fdc)

## Conclusion

- **First conclusion**: the greater the body weight, the greater the weight-bearing capacity, but efficiency decreases as body weight increases (indicator in the second panel)
- **Second conclusion**: its possible to state that there is a correlation between the body weight and the amount of lifted weight (arround 0.68)
- **Third conclusion**: after the age of 40 we can observe a lack of consistency among weightlifters
- **Fourth conclusion**: the average of weight lifted is stable since late 90´s (firsts dates of study)
  
## Credits

All the data in this project was scrapped from the official [IWF](https://beta.iwf.sport/) (international weightlifting federation).
