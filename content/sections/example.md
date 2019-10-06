---
title : ""
description: ""
weight: 0
---


<hr />
<h2 id="experience">フライボード ・ホバーボードを体験する</h2>

関東で体験できるフライボード・ホバーボードアクティビティ

<div id="map"></div>







<h2 id="enter">フライボード ・ホバーボードを体験する</h2>

関東で体験できるフライボード・ホバーボードアクティビティ

<button>ここのGoogleMap</button>




<style>
html { height: 100% }
body { height: 100% }
#map { height: 100%; width: 100%}
</style>
<script>
      var map_obj;
      function initMap() {
        console.log(map);
        map_obj = new google.maps.Map(map, {
          center: {lat: -34.397, lng: 150.644},
          zoom: 8
        });
      }
      console.dir(map_obj);
    </script>
<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyASolxHXUI2r1377h26yWShGFaVqbD6XR4&callback=initMap" async defer></script>
