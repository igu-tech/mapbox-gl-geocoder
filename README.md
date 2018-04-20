## Mapbox GL Geocoder [![CircleCI](https://circleci.com/gh/mapbox/mapbox-gl-geocoder.svg?style=svg)](https://circleci.com/gh/mapbox/mapbox-gl-geocoder)

This control is customized to use Mecklenburg County's geocoding API rather than Mapbox's, as well as fetch/promise polyfills.

I added a `searchTypes` option to specify the search types for our API. Default is "address".

```javascript
var geocoder = new MapboxGeocoder({
  searchTypes: ["address", "park"]
});
```
