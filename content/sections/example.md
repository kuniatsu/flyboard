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
<script src="https://maps.google.com/maps/api/js?key=AIzaSyASolxHXUI2r1377h26yWShGFaVqbD6XR4&language=ja"><script>
<script>
    console.log("test2");
    var dom = document.getElementById('map');
    var MyLatLng = new google.maps.LatLng(35.6811673, 139.7670516);
    var Options = {
    zoom: 15,      //地図の縮尺値
    center: MyLatLng,    //地図の中心座標
    mapTypeId: 'roadmap'   //地図の種類
    };
    var map = new google.maps.Map(dom, Options);
    console.dir(map);
</script>
