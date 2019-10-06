---
title : ""
description: ""
weight: 0
---



<script>
console.log("map log");
var map;
function initMap() {
    map = new google.maps.Map(document.getElementById('sample'), { // #sampleに地図を埋め込む
        center: { // 地図の中心を指定
            lat: 34.7019399, // 緯度
            lng: 135.51002519999997 // 経度
        },
        zoom: 19 // 地図のズームを指定
    });
    console.dir(map);
}
console.dir(map);
</script>
<script src="https://maps.googleapis.com/maps/api/js?callback=initMap"></script>

<hr />
<h2 id="experience">フライボード ・ホバーボードを体験する</h2>

関東で体験できるフライボード・ホバーボードアクティビティ

<div id="sample"></div>







<h2 id="enter">フライボード ・ホバーボードを体験する</h2>

関東で体験できるフライボード・ホバーボードアクティビティ

<button>ここのGoogleMap</button>

