# Arduino-Time-Recording

DESCRIPTION:
============
The TimeRecord module is used to measure the execution time of a piece of code. In a real-time environment, since this measurement will be done several times, the class will be able to return not only the last time recorded, but the average time over the last 1000 measurements, and the maximum of all measurements since the object was initialized. All recorded times are in MICROSECONDS.

INSTALL:
============
1. Click on "Clone or Download" and then "Download ZIP".
2. Unzip the downloaded file.
3. Go to "path-to-Arduino-location/libraries/" and create a folder named "TimeRecord".
4. Copy the files unzipped before into the recently created "TimeRecord" folder.

OTHER COMMENTS
=====
The user can give some personalization to this module:
- To change the number of measurements over which the average time is computed, modify the variable "AVG_RECORDS" in "src/BXD_Controller/TimeRecord.h".
- To measure MILLISECONDS instead of MICROSECONDS, on the file "src/BXD_Controller/TimeRecord.cpp" change all "micros()" functions with "millis()".
