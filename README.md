# Analyzing Public Data on Rec Center Customers

Data used (not included in the github project) is available [here](https://open-data.bouldercolorado.gov/datasets/121a6643af894314bd02ea42544ce9d9_0).  

Data Dictionary is:  

|Column Name|Description|
|:-----|:-----|
|geographic_area_id|Two options, Resident and Nonresident.  Resident equals patron lives within the city of Boulder Boundaries and received the discounted resident rate for memberships and activities.  Nonresident identified patrons outside the city boundaries.|
|city|City which patron resides in|
|state|State patron resides in|
|zipcode|Zip code patron resides in|
|age|Age (in years) of customer at the time of calculation and publishing. Calculated by subtracting the year of birth from 2017. 'n/a' values indicate the birthdate was blank in the system.|
|entrydate|Date patron used membership to enter facility|
|gender|Gender identified by patron|
|resident|In reference to geographic area, if resident field equals yes, if nonresident field equals no|
|retired|Patrons account is no longer active in our database|
|Package1|First type membership patrons has been assigned or purchased|
|Package2|Additional type of membership patrons has been assigned or purchased|
|Package3|Additional type of membership patrons has been assigned or purchased|
|Package4|Additional type of membership patrons has been assigned or purchased|
|Package5|Additional type of membership patrons has been assigned or purchased|
|Package6|Additional type of membership patrons has been assigned or purchased|
|Package7|Additional type of membership patrons has been assigned or purchased|

Part of Data Scientist Nanodegree at Udacity
