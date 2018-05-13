# geolocate

This is a command line tool to get the geographical location of an IP or URL.

To use it, just do `geolocate [IP_ADDRESS]` or `geolocate [URL]`, and the geographical information will be fetched, formatted, and printed.

For example, `geolocate whitehouse.gov` gives the following output:
```
IP Address: 104.103.84.193
Location Name: Amsterdam, NH, Netherlands
Lat, Long: (52.3500, 4.9167)
```

`geolocate 123.123.123.123` gives the following output:
```
IP Address: 123.123.123.123
Location Name: Beijing, BJ, China
Lat, Long: (39.9289, 116.3883)
```
