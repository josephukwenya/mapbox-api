# HTML HEAD
script(src='https://api.mapbox.com/mapbox-gl-js/v2.13.0/mapbox-gl.js')
link(href='https://api.mapbox.com/mapbox-gl-js/v2.13.0/mapbox-gl.css' rel='stylesheet')

# JS SCRIPT
mapboxgl.accessToken =
  'pk.eyJ1Ijoiam9zZXBodWt3ZW55YSIsImEiOiJjbGZtY21zMmcwYWNoM3dvMWRlbGxxZ2pyIn0.350ZRmUSTjfbrHsNNZYGrA';
const map = new mapboxgl.Map({
  container: 'map', // container ID
  style: 'mapbox://styles/mapbox/streets-v12', // style URL
  center: [-74.5, 40], // starting position [lng, lat]
  zoom: 9, // starting zoom
});