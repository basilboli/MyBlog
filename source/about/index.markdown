---
layout: page
title: "about"
date: 2013-03-12 14:55
comments: true
sharing: true
footer: true
---

I’m Vasyl Vaskul, and I’m a software developer in Paris. 
While not coding, traveling or bloging I travel, blog and code.
I do love simple and cool products in any domain of the human nature.

##Drop an instant glance on my photos
<style>.ig-b- { display: inline-block; }
.ig-b- img { visibility: hidden; }
.ig-b-:hover { background-position: 0 -60px; } .ig-b-:active { background-position: 0 -120px; }
.ig-b-v-24 { width: 137px; height: 24px; background: url(//badges.instagram.com/static/images/ig-badge-view-sprite-24.png) no-repeat 0 0; }
@media only screen and (-webkit-min-device-pixel-ratio: 2), only screen and (min--moz-device-pixel-ratio: 2), only screen and (-o-min-device-pixel-ratio: 2 / 1), only screen and (min-device-pixel-ratio: 2), only screen and (min-resolution: 192dpi), only screen and (min-resolution: 2dppx) {
.ig-b-v-24 { background-image: url(//badges.instagram.com/static/images/ig-badge-view-sprite-24@2x.png); background-size: 160px 178px; } }</style>
<a href="http://instagram.com/basilboli?ref=badge" class="ig-b- ig-b-v-24"><img src="//badges.instagram.com/static/images/ig-badge-view-24.png" alt="Instagram" /></a>

##My projects
<iframe src="http://githubbadge.appspot.com/badge/basilboli" style="border: 0;height: 142px;width: 200px;overflow: hidden;" frameBorder=0></iframe>

##What I am usually doing during the WEEK and the WEEKEND
<canvas id="canvas" height="450" width="450"></canvas>

<script>
var radarChartData = {
    labels : ["Eating","Drinking","Sleeping","Traveling","Coding","Partying","Tennis"],
    datasets : [
        {
            fillColor : "rgba(220,220,220,0.5)",
            strokeColor : "rgba(220,220,220,1)",
            pointColor : "rgba(220,220,220,1)",
            pointStrokeColor : "#fff",
            data : [65,59,90,81,56,55,40]
        },
        {
            fillColor : "rgba(151,187,205,0.5)",
            strokeColor : "rgba(151,187,205,1)",
            pointColor : "rgba(151,187,205,1)",
            pointStrokeColor : "#fff",
            data : [28,48,40,19,96,27,100]
        }
    ]
}

var myRadar = new Chart(document.getElementById("canvas").getContext("2d")).Radar(radarChartData,{scaleShowLabels : false,pointLabelFontSize : 10});
</script>


