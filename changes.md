Change Log
==========

### changes in "7.0-SNAPSHOT"


### changes in "6.0"

* update to scala 2.13.3
* update to "stixtoneolib-0.6" which uses "scalastix-1.1" all using scala 2.13.3

### changes in 5.0

* update to "stixtoneolib-0.5" which uses "scalastix-1.0"

---> no longer providing a ready to use jar file. 
    Use "sbt assembly" to generate a self contained jar file "stixtoneo-5.0.jar".

### changes in 4.0

* update scala, sbt and stixtoneolib

### changes in 3.0

* update stixtoneolib to 0.3 version

### changes in 2.0

* use stixtoneolib-0.2 library for processing 
* change the usage options with:
*** -f for file of json format, catering for both text and zip files 
*** -x for the large files, catering for both text and zip files 

### changes in 1.0

* remove all circe dependencies
* add Play json dependency
* replace all circe code with Play json code
* added counting the nodes
* added custom properties
* added the missing hashes of ExternalReference
* remove description from ObservablesMaker
* added custom (for custom properties x_...) to ObservablesMaker
* update to scalastix-0.7, for STIX-2.0 specs 
* due to STIX-2.0 specs, 
** modify object_refs as optional for Report
** comment out the lang and confidence parameters.

* updated scala, sbt, plugins