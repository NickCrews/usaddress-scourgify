Changelog
=========
UNRELEASED
------------------
* BREAKING: Make `geocoder` an optional dependency.

0.2.3 [2020-05-06]
------------------
* Valid OccupancyType bug fix for OccupancyType that is already valid abbreviation

0.2.1 [2020-05-06]
------------------
* Corrected for late OccupancyType additions and allowed # OccpancyType to pass through

0.2.0 [2020-05-06]
------------------
* potentially breaking change. Non-standard unit numbers now converted to a default.
This is based on a real life incident; the original
behavior to allow non-standard unit types to pass through resulted
in an address validation service also allowing the address to pass
through even though no unit should have existed on the home.

0.1.3 [2018-09-09]
------------------
* python 3.7.0 compatibility

0.1.0 [2018-02-16]
------------------
* OpenSource release
