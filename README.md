# NYC taxi

Data Visualization for NYC taxi all completed trip since 2009

## Getting Started

Follow the instructions will get you familiar with how to visuale the data. The open source dataset can be reached in the [NYC TLC Website](http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml). Due to large datasets and provider(130~ GBs), tools in this project include Google BigQuery and Google DataLab Notebook. Combining cloud services with data science can make the analysis procedure much efficient.

### Prerequisites

* [Here](https://cloud.google.com/bigquery/public-data/nyc-tlc-trips) is the sample SQL query instruction for Google BigQuery.
* [Here](https://cloud.google.com/bigquery/docs/visualize-datalab) is the notebook instruction for Google Datalab.

## Data Analysis

* Semi-periodical pattern & unusual patterns

Find yearly general patterns for NYC transportation. Visualize the total count of passengers among dataset for 2009, 2010, and 2014 in different figures. 

* Minimum point of NYC taxi

Find the minimum point of yearly NYC transportation. Visualize the 2011, 2012, and 2013 for further analysis.

## Hypothesis and reasons

For the general patterns, there are continuously periodical-fluctuated patterns. Hypothesize these patterns show the event or behavior people used to do. Most likely it represents something like **weekend or weekday**. Since it keeps happening, the suggestion for the total count of passenger fluctuate goes to weekend or weekday. 

For the anomaly patterns, there are two decrease for each year. Those findings can be referenced to **Martin Luther King Jr. Day** in the early of the year and **Christmas** in the end of the year. 

For the 2011, the minimum point was 8/28 and there were 37292 passengers. The reason for causing the trough was **Hurricane Irene** hits New York. For the 2012, the minimum point was 10/29 and there were 186901 passengers. The reason for causing the trough in this year was New York was severely affected by **Hurricane Sandy**. For the 2013, the minimum point was 8/4 and there were 283636 passengers. The reason for causing the trough was the **new regulation about green cabs** (boro taxis). 

The supporting visualization can be reached in the nyc_taxi notebook file.

## License

This project is licensed under the course project of CSCI585 at USC 
