# Public Transit Information with Python

## Talk from notPyconIL 2018

[Slides](https://docs.google.com/presentation/d/176MNR3kg9o-ExYpEA2aaabFboUvuU1pXkHMojeT9qUk/edit?usp=sharing)

[curlbus.app](https://curlbus.app)

Look at the Jupyter Notebooks for the code and live demos.

For the database based examples to work, setup a PostgreSQL database run the models, and then run `update_feed.sh`.

Note:
for the realtime example to work you have to create an instance of the SIRI client with the user ID and password you got from the Ministry of Transportation.

## Resources:

### Static data

* [MoT GTFS documentation](https://www.gov.il/he/Departments/General/gtfs_general_transit_feed_specifications)
* [GTFS Specification](https://developers.google.com/transit/gtfs/reference/)
* MoT GTFS FTP Server - ftp://gtfs.mot.gov.il/

### Realtime data

Check siri.py for implementation or [the async version in curlbus](https://github.com/elad661/curlbus/blob/master/curlbus/siri.py)

[MoT SIRI-SM realtime API](https://www.gov.il/he/Departments/General/real_time_information_siri)


