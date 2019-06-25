SOLUTION STRATEGY

To solve this problem, I shall be using datasets sourced from a wikipedia page which
provides good information and a list of neighbourhoods with associated postal codes in Toronto.
This data would captured and scrapped using either BeautifulSoup web scrapping tool or Pandas DataFrame
HTML reader object.The data is in table format with 3 attributes (Postcode, Borough 
and Neighbourhour) and 103 distinct records or postal codes.
(source: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M)

The Second dataset is a CSV file. This datasets has 3 attributes (Postcode, Longitute, Latitute cordinates)
and 103 records.
For the purpose of accuracy and cohesiveness, these two datasets would be merged base on their Postcodes.
The final dataset would contain 5 attributes and 103 records.

The next strategy would required me to get list of different venues in the Toronto
neighbourhood and this would be done using the Foursquare API to make calls to endpoints
so as to explore the different venues(physicals spots eg. hotels, Restaurans, Touristic sites, ...) in each neighbourhood.
Using the Foursquare geolocation data, with the first data, i shall be exporing ane analyzing
which solution best meets the need of the problem considering the policies and preferences of XYZ Corporation.
