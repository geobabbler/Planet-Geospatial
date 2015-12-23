# Planet-Geospatial
Geo aggregator

usage: python planetgs.py {path_to_subscription_file} {number_of_hours_to_query} {output_file}

First argument is the path to a file containing a list of subscription URLs. See 'geospatial.txt' for example.
Second argument is the number of hours to query back (from current time) in each feed.
Third argument if the name/path to the output HTML file.

Example checking the last 24 hours: python planetgs.py geospatial.txt 24 geospatial.html
