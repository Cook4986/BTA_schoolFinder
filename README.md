# BTA_schoolFinder
[Black Teacher Archive](https://curiosity.lib.harvard.edu/black-teacher-archive) historic school search automation

## Functionality
Takes [historic school names tables](https://iiif.lib.harvard.edu/manifests/view/drs:494225847$14b) and returns:
* Latitude/Longitude
* [GeoNames](https://www.geonames.org/) or [Historical Marker Database](https://www.hmdb.org/) placename
* [Feature Code](https://www.geonames.org/export/codes.html)

## Requirements
* Python 3.8
* [Pandas](https://pandas.pydata.org/docs/index.html)
* [Selenium](https://www.selenium.dev/documentation/webdriver/getting_started/)
* [Requests](https://github.com/psf/requests)

## Usage
In the Jupyter notebook, customize local (CSV) input and ["fuzzy_value"](https://lucene.apache.org/core/7_3_1/core/org/apache/lucene/search/FuzzyQuery.html)

## TO DO:
* Find Nearest Address (GeoNames):
* Error message details (HMDB)
* https://www.geonames.org/maps/us-reverse-geocoder.html#findNearestAddress
* Select table image OCR tool ("pre-prep")

### Cook 2024
