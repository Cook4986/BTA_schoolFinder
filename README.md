# BTA_schoolFinder
[Black Teacher Archive](https://curiosity.lib.harvard.edu/black-teacher-archive) project code

## Functionality
Takes [historic school names table](https://iiif.lib.harvard.edu/manifests/view/drs:494225847$14b) and returns:
* Latitude/Longitude
* [GeoNames](https://www.geonames.org/) or [HMDB](https://www.hmdb.org/) name(s)
* [Feature Code](https://www.geonames.org/export/codes.html)
* [Feature Class](https://www.geonames.org/source-code/javadoc/org/geonames/FeatureClass.html)

## Requirements
* Python 3.8
* [Pandas](https://pandas.pydata.org/docs/index.html)
* Requests
* time
* [selenium](https://www.selenium.dev/documentation/webdriver/getting_started/)
* re

## Usage
In the Jupyter notebook, customize local (CSV) input, geonames username, and ["fuzzy_value"](https://lucene.apache.org/core/7_3_1/core/org/apache/lucene/search/FuzzyQuery.html)

## TO DO:
* [Find Nearest Address](https://www.geonames.org/maps/us-reverse-geocoder.html#findNearestAddress)
* Table image OCR workflow
* Process "State Association Black Schools" docs

#### Cook 2024
#### [mncook.net](https://www.mncook.net/)
