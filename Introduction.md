Introduction
========================================================
author: Sixiang Hu
date: 18th Jun, 2015

Wanted
========================================================
left: 70%
- Name      :   Sixiang Hu (Steven) 
- Gender    :   Male
- From      :   Wuhan, China (middle part of China)
- Major (UG):   Maths in Wuhan University 
- Major (PG):   Actuarial Science in Heroit-Watt University

***
![wanted](Introduction-figure/me.jpg)



Where is so called "middle part of China"?
========================================================

<!-- Map generated in R 3.2.0 by googleVis 0.5.8 package -->
<!-- Wed Jun 17 00:08:57 2015 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataMapID11d863d51ec7 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 30.35,
114.17,
"This is Wuhan in Hubei Province" 
] 
];
data.addColumn('number','Latitude');
data.addColumn('number','Longitude');
data.addColumn('string','Tip');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartMapID11d863d51ec7() {
var data = gvisDataMapID11d863d51ec7();
var options = {};
options["showTip"] = true;
options["showLine"] = true;
options["enableScrollWheel"] = true;
options["mapType"] = "terrain";
options["width"] = "800px";
options["height"] = "600px";
options["zoomLevel"] =      4;
options["useMapTypeControl"] = true;

    var chart = new google.visualization.Map(
    document.getElementById('MapID11d863d51ec7')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "map";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartMapID11d863d51ec7);
})();
function displayChartMapID11d863d51ec7() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartMapID11d863d51ec7"></script>
 
<!-- divChart -->
  
<div id="MapID11d863d51ec7" 
  style="width: 800px; height: 600px;">
</div>

Hobbies
========================================================
left: 70%
- Programming (C, C++, WPF, R, SAS,SQL, JavaScript, etc.)
- Classical Music (Piano)
- PC Games (Adventure, e.g. [Nancy Drew](https://en.wikipedia.org/wiki/Nancy_Drew))
- Travel (e.g. National trusts, Edinburgh Castel, Arudal Castel, Windsor Castel, etc.)
- And, of cause, R!

***
  ![Nancy Drew](https://upload.wikimedia.org/wikipedia/en/thumb/b/bf/ND1tsotoc.JPG/220px-ND1tsotoc.JPG)
  
========================================================
<div align="center">
<img src="Introduction-figure/20150607_141205.png" width=1000 height=800>
</div>
