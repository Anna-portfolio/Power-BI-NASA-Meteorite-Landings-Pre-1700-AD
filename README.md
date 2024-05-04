# Power BI: NASA Meteorite Landings Before 1700 AD

![Meteorite Landings_logo](https://github.com/Anna-portfolio/Power_BI_NASA_Meteorite_Landings_Pre-1700_AD/assets/75646880/5e74d592-bf27-4018-a02a-124a238d636c)

![Meteorite_Landings_image01](https://github.com/Anna-portfolio/Power_BI_NASA_Meteorite_Landings_Pre-1700_AD/assets/75646880/c15933e0-a80e-4fa3-88dd-81f4b06142a3)

![Meteorite_Landings_image02](https://github.com/Anna-portfolio/Power_BI_NASA_Meteorite_Landings_Pre-1700_AD/assets/75646880/522aa8ef-be69-4144-b42c-e0a4a086a059)



<h4>Power BI project, presenting meteorite landings observed and documented before 1700 AD (based on linked dataset by NASA)</h4>
<br>

<h3>Overview:</h3>
This report, based on NASA's dataset linked below, presents meteorite landings observed and documented before 1700 AD. 

<h3>Main Features:</h3>
<ul>
  <li>Page #1 Map: interactive map with landings locations and legend</li>
  <li>Page #2 Details: provides detailed description of chosen item (name, location, dynamic text box, and data table)</li>
</ul>
<h3>Main adjustments and modifications in Power BI:</h3>
<ul>
  <li>includes two datasets: 'Meteorite_Landings' (dataset downloaded from NASA's website) and 'Metorites_Country' (created by myself, specifies the present-day country of landings locations)</li>
  <li>'Meteorite_Landings', column 'year': add filter is less than or equal to 1699</li>
  <li>'Meteorite_Landings', columns 'name' and 'year': merge into 'year_name_merged' and used as legend items in Page #1</li>
 <li>add relationship by Id 'Meteorite_Landings' and 'Meteorite_Country' (used for details in Page #2)
 <li>'Meteorite_Landings', column 'mass (g)': replace null to string "unknown" (to be correctly displayed into the Page#2 dynamic text box)</li>
 <li>Page #1: add zoom buttons to map</li>
 <li>Page #1 and Page #2: add drillthrough buttons allowing for navigating between the two pages</li>
 <li>Page #1 and Page #2: add background image (link below)</li>
</ul>


![Meteorite_Landings_image03](https://github.com/Anna-portfolio/Power_BI_NASA_Meteorite_Landings_Pre-1700_AD/assets/75646880/d615ecd1-8423-47a2-974b-05853d490bf2)



<h3>Sources:</h3>
<a href="https://data.nasa.gov/Space-Science/Meteorite-Landings/gh4g-9sfh/about_data">NASA dataset source</a><br>
<a href="https://pixabay.com/illustrations/ai-generated-earth-asteroid-8656816/">Background image source</a>

