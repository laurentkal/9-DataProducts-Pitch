--- 

title       : Pitch for the Alcohol World Cup Shiny App
subtitle    : July 24, 2016
author      : Laurent Kalfon
framework   : io2012       # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [boostrap, quiz, interactive]
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides



--- &radio 

## Can you anwser this simple question?

In which country do people drink the most beer?

1. Brazil
2. Czech Republic
3. _Namibia_
4. China

*** .hint
It is a not a European country.

*** .explanation
It might seem weird, but yes, this is the correct answer!

--- 

## Had you run my app, you would have known it right from the start!

Thanks to my very cool shiny app you can visualize how and how much people drink in the world.
The pretty visualizations embedded in the app enable you to answer such questions as:
- Who drink the most alcohol per type of alcohol (beer, spirit, wine)?
- What is the breakdown of alcohol consumption per continent?
- Is there a relationship between alcohol consumption and life expectancy?
   
And last but not least, you will be able to show off your knowledge at every party.

--- &interactive

## Here is the kind of visualization you can get from the app

Map of the beer consumption across countries (serving units per person)
   

<!-- GeoChart generated in R 3.2.1 by googleVis 0.5.10 package -->
<!-- Sun Jan 24 19:07:31 2016 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataGeoChartID25786021e5 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "Afghanistan",
0 
],
[
 "Albania",
89 
],
[
 "Algeria",
25 
],
[
 "Andorra",
245 
],
[
 "Angola",
217 
],
[
 "Antigua & Barbuda",
102 
],
[
 "Argentina",
193 
],
[
 "Armenia",
21 
],
[
 "Australia",
261 
],
[
 "Austria",
279 
],
[
 "Azerbaijan",
21 
],
[
 "Bahamas",
122 
],
[
 "Bahrain",
42 
],
[
 "Bangladesh",
0 
],
[
 "Barbados",
143 
],
[
 "Belarus",
142 
],
[
 "Belgium",
295 
],
[
 "Belize",
263 
],
[
 "Benin",
34 
],
[
 "Bhutan",
23 
],
[
 "Bolivia",
167 
],
[
 "Bosnia-Herzegovina",
76 
],
[
 "Botswana",
173 
],
[
 "Brazil",
245 
],
[
 "Brunei",
31 
],
[
 "Bulgaria",
231 
],
[
 "Burkina Faso",
25 
],
[
 "Burundi",
88 
],
[
 "Cote d'Ivoire",
37 
],
[
 "Cabo Verde",
144 
],
[
 "Cambodia",
57 
],
[
 "Cameroon",
147 
],
[
 "Canada",
240 
],
[
 "Central African Republic",
17 
],
[
 "Chad",
15 
],
[
 "Chile",
130 
],
[
 "China",
79 
],
[
 "Colombia",
159 
],
[
 "Comoros",
1 
],
[
 "Congo",
76 
],
[
 "Cook Islands",
0 
],
[
 "Costa Rica",
149 
],
[
 "Croatia",
230 
],
[
 "Cuba",
93 
],
[
 "Cyprus",
192 
],
[
 "Czech Republic",
361 
],
[
 "North Korea",
0 
],
[
 "DR Congo",
32 
],
[
 "Denmark",
224 
],
[
 "Djibouti",
15 
],
[
 "Dominica",
52 
],
[
 "Dominican Republic",
193 
],
[
 "Ecuador",
162 
],
[
 "Egypt",
6 
],
[
 "El Salvador",
52 
],
[
 "Equatorial Guinea",
92 
],
[
 "Eritrea",
18 
],
[
 "Estonia",
224 
],
[
 "Ethiopia",
20 
],
[
 "Fiji",
77 
],
[
 "Finland",
263 
],
[
 "France",
127 
],
[
 "Gabon",
347 
],
[
 "Gambia",
8 
],
[
 "Georgia",
52 
],
[
 "Germany",
346 
],
[
 "Ghana",
31 
],
[
 "Greece",
133 
],
[
 "Grenada",
199 
],
[
 "Guatemala",
53 
],
[
 "Guinea",
9 
],
[
 "Guinea-Bissau",
28 
],
[
 "Guyana",
93 
],
[
 "Haiti",
1 
],
[
 "Honduras",
69 
],
[
 "Hungary",
234 
],
[
 "Iceland",
233 
],
[
 "India",
9 
],
[
 "Indonesia",
5 
],
[
 "Iran",
0 
],
[
 "Iraq",
9 
],
[
 "Ireland",
313 
],
[
 "Israel",
63 
],
[
 "Italy",
85 
],
[
 "Jamaica",
82 
],
[
 "Japan",
77 
],
[
 "Jordan",
6 
],
[
 "Kazakhstan",
124 
],
[
 "Kenya",
58 
],
[
 "Kiribati",
21 
],
[
 "Kuwait",
0 
],
[
 "Kyrgyzstan",
31 
],
[
 "Laos",
62 
],
[
 "Latvia",
281 
],
[
 "Lebanon",
20 
],
[
 "Lesotho",
82 
],
[
 "Liberia",
19 
],
[
 "Libya",
0 
],
[
 "Lithuania",
343 
],
[
 "Luxembourg",
236 
],
[
 "Madagascar",
26 
],
[
 "Malawi",
8 
],
[
 "Malaysia",
13 
],
[
 "Maldives",
0 
],
[
 "Mali",
5 
],
[
 "Malta",
149 
],
[
 "Marshall Islands",
0 
],
[
 "Mauritania",
0 
],
[
 "Mauritius",
98 
],
[
 "Mexico",
238 
],
[
 "Micronesia",
62 
],
[
 "Monaco",
0 
],
[
 "Mongolia",
77 
],
[
 "Montenegro",
31 
],
[
 "Morocco",
12 
],
[
 "Mozambique",
47 
],
[
 "Myanmar",
5 
],
[
 "Namibia",
376 
],
[
 "Nauru",
49 
],
[
 "Nepal",
5 
],
[
 "Netherlands",
251 
],
[
 "New Zealand",
203 
],
[
 "Nicaragua",
78 
],
[
 "Niger",
3 
],
[
 "Nigeria",
42 
],
[
 "Niue",
188 
],
[
 "Norway",
169 
],
[
 "Oman",
22 
],
[
 "Pakistan",
0 
],
[
 "Palau",
306 
],
[
 "Panama",
285 
],
[
 "Papua New Guinea",
44 
],
[
 "Paraguay",
213 
],
[
 "Peru",
163 
],
[
 "Philippines",
71 
],
[
 "Poland",
343 
],
[
 "Portugal",
194 
],
[
 "Qatar",
1 
],
[
 "South Korea",
140 
],
[
 "Moldova",
109 
],
[
 "Romania",
297 
],
[
 "Russian Federation",
247 
],
[
 "Rwanda",
43 
],
[
 "St. Kitts & Nevis",
194 
],
[
 "St. Lucia",
171 
],
[
 "St. Vincent & the Grenadines",
120 
],
[
 "Samoa",
105 
],
[
 "San Marino",
0 
],
[
 "Sao Tome & Principe",
56 
],
[
 "Saudi Arabia",
0 
],
[
 "Senegal",
9 
],
[
 "Serbia",
283 
],
[
 "Seychelles",
157 
],
[
 "Sierra Leone",
25 
],
[
 "Singapore",
60 
],
[
 "Slovakia",
196 
],
[
 "Slovenia",
270 
],
[
 "Solomon Islands",
56 
],
[
 "Somalia",
0 
],
[
 "South Africa",
225 
],
[
 "Spain",
284 
],
[
 "Sri Lanka",
16 
],
[
 "Sudan",
8 
],
[
 "Suriname",
128 
],
[
 "Swaziland",
90 
],
[
 "Sweden",
152 
],
[
 "Switzerland",
185 
],
[
 "Syria",
5 
],
[
 "Tajikistan",
2 
],
[
 "Thailand",
99 
],
[
 "Macedonia",
106 
],
[
 "Timor-Leste",
1 
],
[
 "Togo",
36 
],
[
 "Tonga",
36 
],
[
 "Trinidad & Tobago",
197 
],
[
 "Tunisia",
51 
],
[
 "Turkey",
51 
],
[
 "Turkmenistan",
19 
],
[
 "Tuvalu",
6 
],
[
 "Uganda",
45 
],
[
 "Ukraine",
206 
],
[
 "United Arab Emirates",
16 
],
[
 "United Kingdom",
219 
],
[
 "Tanzania",
36 
],
[
 "USA",
249 
],
[
 "Uruguay",
115 
],
[
 "Uzbekistan",
25 
],
[
 "Vanuatu",
21 
],
[
 "Venezuela",
333 
],
[
 "Vietnam",
111 
],
[
 "Yemen",
6 
],
[
 "Zambia",
32 
],
[
 "Zimbabwe",
64 
] 
];
data.addColumn('string','Country');
data.addColumn('number','Beer');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartGeoChartID25786021e5() {
var data = gvisDataGeoChartID25786021e5();
var options = {};
options["width"] =    556;
options["height"] =    347;

    var chart = new google.visualization.GeoChart(
    document.getElementById('GeoChartID25786021e5')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "geochart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartGeoChartID25786021e5);
})();
function displayChartGeoChartID25786021e5() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartGeoChartID25786021e5"></script>
 
<!-- divChart -->
  
<div id="GeoChartID25786021e5" 
  style="width: 556; height: 347;">
</div>

---

## So why don't you try it right now?
 
- You can access it [right there](https://laurentkal.shinyapps.io/DDP_Project/).
- All the data are from the World Health Organization.
- The alcohol dataset was downloaded at the [fivethirtyeight github repo](https://github.com/fivethirtyeight/data) (and by the way, if you're looking for cool datasets, just head there!). 
- A more complete [article](http://fivethirtyeight.com/datalab/dear-mona-followup-where-do-people-drink-the-most-beer-wine-and-spirits/) based on this dataset was published by the fivethirtyeight team.

