---
title: NPP Soil Water Content
created: '2020-11-10T16:26:56.355540'
modified: '2020-11-10T16:26:56.355549'
state: active
type: dataset
tags:
  - Biota
  - Climatologymeteorologyatmosphere
  - Environment
  - Farming
  - Geoscientificinformation
  - Iso Metadata
  - Np216
groups: []
csv_url: >-
  https://jornada.nmsu.edu/sites/jornada.nmsu.edu/files/data_files/JornadaStudy_013_npp_soil_water_content_data.csv
json_url: ''
layout: post

---
<p>Once a month soil water content measurements are made at 10 depths (where possible) at each of 10 access tubes at each of the 15 LTER-II sites using a neutron probe (Campbell Model 503DR Hydroprobe). Measurements are taken at 30cm, 60cm, 90cm, 120cm, 150cm, 180cm, 210cm, 240cm, 270cm, and 300cm when possible or to the greatest depth it was possible to install the access tubing before hitting impenetrable caliche. If fewer depths were measured, the missing depths have a zero in the raw data set of count values. These are changed to "." in converted water content data set. Calculated water content values equal to less than zero are changed to zero in converted water content data set. Converted water content values are a volume/volume relationship and represent cm3 water/cm3 soil. Data from neutron probe data logger is dumped to disk. Raw count data is then converted to water content using a Fortran program called WC2.FOR (water content for LTER-II). Water content data is then sorted by i.d. number using a LOTUS 123 macro found in WC2_SORT.WQ1 which creates final version of water content data set for the month in a separate file. Two files per month are saved: raw count data (mmddyy-2.RAW; ex. 121189-2.RAW where -2 indicates LTER-II NPP site neutron probe readings) and calculated/ sorted soil water content data appended to data file containing that year's data (NPPSWCyy.DAT; example NPPSWC89.DAT contains NPP soil water content data for 1989). Regression equation was derived by Mahlia Nash, and after datalogger upgrade was added to hydroprobe, by David Hudson, both working for Dr. Peter Wierenga (as of 1994 at university at Tucson (Hudson's phone # is 602-621-3236). See PROBE.HIS file for probe history and regressions used for different data periods when different probes were used. The hydroprobe used whenever possible is Hydroprobe Model CPN503DR (Campbell Pacific Nuclear, Pacheco, CA) with data logger. This probe has a 50mCi241 Am-Be source and a hydrogen detector. Neutrons encountering hydrogen become thermalized. The detector totals returning thermalized neutrons over a 16 second sample time which is the raw count value displayed. The raw count value is then substituted into the proper regression equation for cm3 of water per cm3 of soil.</p>

