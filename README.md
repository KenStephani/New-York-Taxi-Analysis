# New York-Taxi-Analysis

Source of data:

https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page

Python:
import pyarrow.parquet as pq
trips = pq.read_table('trips.parquet')
trips = trips.to_pandas()


to refresh github ...

git add .
git commit -m "a comment"
git push 

What do you need to know about your data?

What are possible problems you want to look into?

	"bad data" - what does "bad" mean 
		can or should I delete data?
		
	"missing values" - what and how many are there
	
How are yu going to look for that information?
	
	look at all documentation at source web page ...
	apply techniques from her videos ...
	
	
	
	how to navigate microaggressions
	
	
	
