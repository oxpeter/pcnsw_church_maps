# pcnsw_church_maps
Code to extract details of all NSW Presbyterian Churches from the PCNSW church database,
 and convert it into a Folium map for easier viewing.

To view the output, visit [this page](https://oxpeter.github.io/pcnsw_church_maps/)

There are now two separate maps being created, for two different purposes. The first map 
shows the locations of all the churches and their basic details:
* minister
* meeting times
* address
* website

[church address map](img/pressy_churches_by_address_map.png)

The second map is more for strategic planning purposes, and is more complex. It contains
a set of different overlays and colour schemes that can be selected. Churches can be 
coloured according to the following:
* Presbytery
* Status of Charge
* Basic position

ABS Census overlays can also be activated, showing data at the SA4 level. Currently
this includes:
* population
* number of people self-identifying as Presbyterian
* number of Presbyterians per 1,000 persons 

[census data map](img/church_plus_abs.png)