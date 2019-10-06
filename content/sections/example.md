---
title : ""
description: ""
weight: 0
---


<script>
console.log("test2");
var map;
function initMap() {
 map = new google.maps.Map(document.getElementById('map'), { // #mapに地図を埋め込む
     center: { // 地図の中心を指定
           lat: 35.681236, // 緯度
          lng: 139.767125 // 経度
       },
      zoom: 15, // 地図のズームを指定
      mapTypeId: google.maps.MapTypeId.ROADMAP //表示する地図の形式を設定します。今回は道路地図を表示します。
   });
}
</script>
<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyASolxHXUI2r1377h26yWShGFaVqbD6XR4&callback=initMap"></script>

<hr />
<h2 id="experience">フライボード ・ホバーボードを体験する</h2>

関東で体験できるフライボード・ホバーボードアクティビティ

<div id="map"></div>







<h2 id="enter">フライボード ・ホバーボードを体験する</h2>

関東で体験できるフライボード・ホバーボードアクティビティ

<button>ここのGoogleMap</button>

