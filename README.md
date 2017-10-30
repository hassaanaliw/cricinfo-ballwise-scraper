# Cricinfo Scraper
This is a python script that I use for scraping ball by ball data not covered by [cricsheet](http://cricsheet.org/) . It converts the data into a csv format that I use for further analysis and integrates with the cricsheet data.

You can modify it as you want to suit your needs. It requires a excel file with each row of match data you want to scrape and atleast two columns:
1. Link for scorecard
2. Link for first innings commentary

It'll give you two files first containing ball-by-ball data and second containing match info data (in a weird format I know). It also gives mistakes in scraping due to commentary mistakes or wrong logic (rare and mostly in case of penalty runs). You can use it to load this data into R using my other [project](https://github.com/mudassirkhan19/cricsheet-data-analysis-stats) or use it in any other way you like.
