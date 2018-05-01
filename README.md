## Mapbox GL Geocoder

This control is customized to use Mecklenburg County's geocoding API rather than Mapbox's, as well as fetch/promise polyfills.

Use the optional `searchTypes` option to specify the search types for Mecklenburg's API. Default is "address".

```javascript
var geocoder = new MapboxGeocoder({
  searchTypes: ["address", "park"]
});
```
