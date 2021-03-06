# weatherapp
Simple python based web server and client which calls the DarkSky Weather API. This was a university project.

[Working Example/Demo](http://weather.jamespayne.net.au)

## Aim

* Further improve my python programming skills.
* Introduction to using web APIs.
* Ensure proper exception handling is used.

## Language/Technology Used

* Python
* Darksky Weather Forecasting API

## Dependencies

The only non core module used in this app is dateutil which can be installed using pip:
  
  pip install python-dateutil

I may remove this dependency and update the code to achive the same functionality with a core module in the future.

## Data Sources

**Local**

PTV Timetable and Geographic Information - GTFS

The data source for station locations is from Public Transport Victoria and only uses one file which is located at /google_transit/stops.txt. This data has been included for demonstration purposes only. For the most current data, please visit the PTV Timetable and Geographic Information - GTFS datasource page which can be found [here](https://www.data.vic.gov.au/data/dataset/ptv-timetable-and-geographic-information-2015-gtfs)

## Notes

You will need an api key from Darksky to run this application. The key should be stored in a file called forecastKey (no extension) in the root directory. This file has not been included for security reasons.
