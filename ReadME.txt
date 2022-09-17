

Data: stations.csv
The stations.csv file contains bike share data in Comma-Separated Values (CSV) format. See below for detailed information on the file format. This file has sample data for testing the functions provided



The Data
Each row of this file (stations.csv) contains the following information about a single bike rental station, in the order listed:
    • station ID: the unique identification (ID) number of the station
    • station name: the name of the station (not necessarily unique)
    • latitude: the latitude of the station location
    • longitude: the longitude of the station location
    • capacity: the total number of bike docks (empty or with bike) at the station
    • bikes available: the number of bikes currently available to rent at the station
    • docks available: the number of empty and working docks at the station
Note: While the sum of the number of bikes available at a station and the number of docks available at a station will usually equal the station's capacity, this need not be the case. When a bike or a dock is broken, the sum of the two availability numbers will not match the capacity.
Another feature of a bike rental station is whether or not it has a kiosk. A kiosk allows a renter to pay for their bike rental using a credit card. Without a kiosk, renters can only pay for their bike rental through an app. Stations that are app-only (that is, that do not have a kiosk) have the string 'SMART' somewhere in their station name. (The bike share system could later change 'SMART' to some other phrase, so, when coding, you should use the constant NO_KIOSK that refers to the used string instead of the string 'SMART', so that if the bike share system changes the string and used a different one your code still works.)

