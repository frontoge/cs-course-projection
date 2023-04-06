# Enrollment Projection Software
This software is a simple java CLI application that takes URLs containing ODU CS course enrollment data as well as the current enrollment period dates to make projections about the current enrollment period. 

## Building 
***Building with a JDK version higher than 11 has not been tested and may not work***
Run by running `./gradlew` followed by `./gradlew shadowJar`

This will create an executable jar file called `app-all.jar` in `app/build/libs/`

## Running
*Required URLs to properly execute this application are not publicly available at this time.*

### Parameters
- An unlimited number of semester data can be passed in semester by semester as a URL for historical assistance on projections. 
- The second to last parameter is a text file that provides the start of the current enrollment period and the enrollment deadline for the current semester.
- The last parameter is the output location of the csv file of projection data. This can be a URL on a remote host or a local path.
