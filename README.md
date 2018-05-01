## Mapbox GL Geocoder

This control is customized to use [Mecklenburg County's API](https://github.com/tobinbradley/dirt-simple-postgis-http-api) rather than Mapbox's, as well as fetch/promise polyfills.

Use the optional `searchTypes` option to specify the search types for Mecklenburg's API. Default is "address". Search options are address, park, pid, library, school, and business. 

```javascript
var geocoder = new MapboxGeocoder({
  searchTypes: ["address", "park"]
});
```
