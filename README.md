UTM2LatLong
===========

A Python script that converts NAD83 UTM Coordinates to Latitude/Longitude (WGS84).  Based on "node-coordinator" by Larry Moore.  I converted his modular JavaScript code to one Python for the sole purpose of converting UTM X,Y to Lat/Long.

Using
=====

The script is pretty simple - when it is run it asks for Northing, Easting, and the UTM Zone then spits out the latitude/longitude.  Remove the print and input stuff and you can integrate it into some other process.

This is based on the "node-coordinator" project by beatgammit (https://github.com/beatgammit/node-coordinator).

Updates
=======

I'm not a great programmer, so don't expect many updates or fixes.  This was more of a "one-off" for something I was doing.  However, fork this or contribute if you'd like to improve it!

Cheers,
Kevin
