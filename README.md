jquery-placepicker
==================

A simple placepicker component for the google-maps api. 

Usage
-----


```html
<script type="text/javascript" src="https://maps.googleapis.com/maps/api/js?sensor=true&libraries=places"></script>
```

```js
$("#placepicker").placepicker();
```

Options
-------
<table>
  <tr>
    <th>Name</th><th>Description</th>
  </tr>
  <tr>
    <td>map</td><td>Map selector or map-element</td>
  </tr>
  <tr>
    <td>mapOptions</td><td>An object with google maps api options</td>
  </tr>
</table>

Methods
-------
<table>
  <tr>
    <th>Name</th><th>Description</th><th>Return</th>
  </tr>
  <tr>
    <td>reloadMap</td><td>Reloads map</td><td>void</td>
  </tr>
  <tr>
    <td>resizeMap</td><td>Resizes map</td><td>void</td>
  </tr>
  <tr>
    <td>geoLocation</td><td>Set value to html5 geo-location</td>
  </tr>
</table>
