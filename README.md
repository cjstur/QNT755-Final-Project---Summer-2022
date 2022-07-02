# QNT755-Final-Project---Summer-2022
Final Group Project

Project members:  Matthieu Bouteillier, Cynthia Eisnor, Michael Scarborough

Project Specifications:

Project will include analysis of data provided by the World Health Organization (WHO).  The WHO was founded in 1948 with the main purpose of promoting health and keeping the world safe.  

The WHO has been collecting data on COVID-19 since December 2019.  Data includes number of cases, number of deaths as well as vaccinations administered.  Our project will answer questions like:

 - What is the death rate by country
 - What is the vaccination rate by country
 - What country had the highest number of vaccination types
 - What country had the fewest number of vaccination types
 - What was the death rate pre-vaccination by country
 - What was the death rate post-vaccination by country
 
 Datafile includes the following fields:
 
  - Date Reported
  - Country Code
  - Country
  - WHO Region
  - New Cases
  - Cumulative Cases
  - New Deaths
  - Cumulative Deaths
  - Vax Type Count
  - Vax Rate
  - First Vax Date

Data was scrubbed as follows:

 - A new field was defined for Vax Type Count.  Instead of having all vaccine options, it was grouped by vaccines < 4 and vaccines >= 4
 - columns not needed for analysis were removed such as WHO Region, Country Code and Vax Type Count 
 - some columns changed names so it was more user friendly
 - created new columns for if the report date was pre or post vaccination release so we could also track the death rate pre and post vaccination



QNT755 Project Overview

[1] Selection of a dataset that is larger than 500MB: must have more than 5 rows and more than 100 million rows of data
[2] Must not be analysis ready, must have one or more of the following properties: (a) multi-valued columns (VCF is a good example) (b) multiple files to model the data (GTFS is a good example where you need at least three of the files to be able to figure out where and when a bus would be available) (c) raw text input (IE not a nice TSV, CSV, JSON or other standard dat format but is in raw text) and example of this would be something like grabbing tweets from the twitter API or doing data analysis on a text: http://www.gutenberg.org/files/11/11-0.txt
[3] Formulate an analysis plan: what quantities or qualitative questions do you have on the data?
[5] Has anyone else already completed this analysis? Were the results the same? Did they make their
code available to look at? If so what insights did you get from trying to read the code?
[6] Put your code on github.com so that you can either work with your partners or easily demonstrate that you have produce functioning code. Look at the short Week 5 github crash course materials.
[Extra credit] Visualize the resulting analysis using matplotlib (section for plotting is in the text)
