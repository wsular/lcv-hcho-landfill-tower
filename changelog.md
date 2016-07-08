Changelog for LCV-HCHO Landfill Met Tower
=========================================

next release
------------

### Issues Fixed

* Initialize final storage variables to NAN to prevent default value ("0") from
  being stored or included in aggregate values
* Check for sensor-specific NAN representations from CS215 temp/RH probe
  (`0` and `-100`) and, if found, store `NAN` instead


v0.1.1 (2016-07-07)
-------------------

### Issues Fixed

* Increase data retention period from 1 day to 28 days; also, enable output to
  CompactFlash memory card


v0.1 (2016-06-21)
-----------------

First version deployed.

