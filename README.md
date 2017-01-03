#Geo-helpers
Helper methods for dealing with geolocation.

##Installation
```npm install geo-helpers```

##Methods
###geodesic(a, b[, max])
* latA - Float
* longA - Float
* latB - Float
* longB - Float
* max - Integer

If max parameter is excluded function returns the orthodromic distance between given coordinates a and b. Otherwise checks if orthodromic distance between a and b exceeds the max parameter and returns a boolean value.