# Fill levels of Swiss reservoir lakes

Reservoir lakes are basically giant batteries that are able to store and deliver electric energy. The **Swiss Federal Office of Energy** (SFOE) regularly [publishes](https://www.bfe.admin.ch/bfe/en/home/supply/statistics-and-geodata/energy-statistics/electricity-statistics.html) weekly data concerning the current fill level of Swiss reservoir lakes in GWh and the current fraction of the maximum possible fill level. Unfortunately, the data from the SFOE is only available as PDF. This repository provides the data in csv format which was obtained through a PDF scraping of the yearly files from the SFOE. The data ranges from 2003-01-06 until 2020-06-22.

## Description of data

|Value|Description|
|:---|:---|
|Date|observation at 00:00 of the corresponding date|
|VS|current fill level in GWh of reservoirs in the canton Valais|
|VSp|fraction of the max possible fill level in the canton Valais|
|GR|current fill level in GWh of reservoirs in the canton Grisons|
|GRp|fraction of the max possible fill level in the canton Grisons|
|TI|current fill level in GWh of reservoirs in the canton Ticino|
|TIp|fraction of the max possible fill level in the canton Ticino|
|rCH|current fill level in GWh of reservoirs in the rest of Switzerland|
|rCHp|fraction of the max possible fill level in the rest of Switzerland|
|CH|current fill level in GWh of reservoirs in whole Switzerland|
|CHp|fraction of the max possible fill level in whole Switzerland|
|Rhm|longtime mean of the daily mean flow of the river Rhine in Basel in m^3/s|
|Rh|actual flow at 12:00|
|Rhp|fraction of the longtime mean|
