---
title : ""
description: ""
weight: 0
---


<hr id="activity" />
<h2 id="experience">アクアボードを体験する</h2>

関東で体験できるアクアボードアクティビティ


<iframe id="location_map1" class="map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d17831.876712274356!2d139.54783839598667!3d35.29924991650879!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6018466de4bafa9b%3A0x5f31ccd3657aa086!2z44OV44Op44Kk44OV44Kj44O844Or44OJ6YCX5a2Q!5e0!3m2!1sja!2sjp!4v1570360331899!5m2!1sja!2sjp" frameborder="0" style="border:0;height: 450px;" allowfullscreen=""></iframe>

<iframe id="location_map2" class="map dispnone"  src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d13636.538198108998!2d139.55185346872906!3d35.300197864254876!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xcd93aad5e87ad65!2z44K444Kn44OD44OI44K544Kt44O844OX44Op44K26Y6M5YCJ!5e0!3m2!1sja!2sjp!4v1570363268935!5m2!1sja!2sjp" frameborder="0" style="border:0;height: 450px;" allowfullscreen=""></iframe>

<iframe id="location_map3" class="map dispnone"  src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3251.0285536038705!2d138.8948744146541!3d35.42932268025384!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xdb852c02c2433eec!2z5bGx5Lit5rmW44Oe44Oq44O844OK44Ko44Kk44OG44Kj44O844Oz!5e0!3m2!1sja!2sjp!4v1570363334395!5m2!1sja!2sjp" frameborder="0" style="border:0;height: 450px;" allowfullscreen=""></iframe>

<h3 id="location1" class="location bold"><a class="tel" href="tel:000-000-000">📞</a>   フライフィールド逗子 </h3>
<h3 id="location2" class="location"><a class="tel" href="tel:000-000-000">📞</a>   JSP鎌倉 </h3>
<h3 id="location3" class="location"><a class="tel" href="tel:000-000-000">📞</a>   マリーナエイティーン </h3>



<script>
location1.addEventListener('click', function(e){
    changeBold(location1,location3,location2);
    location_map1.classList.remove('dispnone');
    location_map2.classList.add('dispnone');
    location_map3.classList.add('dispnone');
});
location2.addEventListener('click', function(e){
    changeBold(location2,location1,location3);
    location_map2.classList.remove('dispnone');
    location_map1.classList.add('dispnone');
    location_map3.classList.add('dispnone');
});
location3.addEventListener('click', function(e){
    changeBold(location3,location1,location2);
    location_map3.classList.remove('dispnone');
    location_map1.classList.add('dispnone');
    location_map2.classList.add('dispnone');

});
function changeBold(add,rm1,rm2){
    add.classList.add('bold');
    rm1.classList.remove('bold');
    rm2.classList.remove('bold');
}
</script>


