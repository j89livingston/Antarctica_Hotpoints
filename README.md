# Antarctica Hotpoints 2000-2021

## 3 SEPARATE SATELLITE DATA:


GENERAL ATTRIBUTES
Latitude
Center of nominal 375 m fire pixel

Longitude
Center of nominal 375 m fire pixel

Bright_ti4
(Brightness temperature I-4)
VIIRS I-4: channel brightness temperature of the fire pixel measured in Kelvin.

Scan
(Along Scan pixel size)
The algorithm produces approximately 375 m pixels at nadir. Scan and track reflect actual pixel size.

Track
(Along Track pixel size)
The algorithm produces approximately 375 m pixels at nadir. Scan and track reflect actual pixel size.

Acq_Date
(Acquisition Date)
Date of VIIRS acquisition.

Acq_Time
(Acquisition Time)
Time of acquisition/overpass of the satellite (in UTC).

Satellite
N Suomi National Polar-orbiting Partnership (Suomi NPP)

Confidence
This value is based on a collection of intermediate algorithm quantities used in the detection process. It is intended to help users gauge the quality of individual hotspot/fire pixels. Confidence values are set to low, nominal and high. Low confidence daytime fire pixels are typically associated with areas of sun glint and lower relative temperature anomaly (15K) temperature anomaly in either day or nighttime data. High confidence fire pixels are associated with day or nighttime saturated pixels.

* Please note:
Low confidence nighttime pixels occur only over the geographic area extending from 11° E to 110° W and 7° N to 55° S. This area describes the region of influence   of the South Atlantic Magnetic Anomaly which can cause spurious brightness temperatures in the mid-infrared channel I4 leading to potential false positive alarms. These have been removed from the NRT data distributed by FIRMS.

Version
Version identifies the collection (e.g. VIIRS Collection 1) and source of data processing: Near Real-Time (NRT suffix added to collection) or Standard Processing (collection only).
"1.0NRT" - Collection 1 NRT processing.
"1.0" - Collection 1 Standard processing.

Bright_ti5
(Brightness temperature I-5)
I-5 Channel brightness temperature of the fire pixel measured in Kelvin.

FRP
(Fire Radiative Power)
FRP depicts the pixel-integrated fire radiative power in MW (megawatts). Given the unique spatial and spectral resolution of the data, the VIIRS 375 m fire detection algorithm was customized and tuned in order to optimize its response over small fires while balancing the occurrence of false alarms. Frequent saturation of the mid-infrared I4 channel (3.55-3.93 µm) driving the detection of active fires requires additional tests and procedures to avoid pixel classification errors. As a result, sub-pixel fire characterization (e.g., fire radiative power [FRP] retrieval) is only viable across small and/or low-intensity fires. Systematic FRP retrievals are based on a hybrid approach combining 375 and 750 m data. In fact, starting in 2015 the algorithm incorporated additional VIIRS channel M13 (3.973-4.128 µm) 750 m data in both aggregated and unaggregated format.

Satellite measurements of fire radiative power (FRP) are increasingly used to estimate the contribution of biomass burning to local and global carbon budgets. Without an associated uncertainty, however, FRP-based biomass burning estimates cannot be confidently compared across space and time, or against estimates derived from alternative methodologies. Differences in the per-pixel FRP measured near-simultaneously in consecutive MODIS scans are approximately normally distributed with a standard deviation (ση) of 26.6%. Simulations demonstrate that this uncertainty decreases to less than ~5% (at ±1 ση) for aggregations larger than ~50 MODIS active fire pixels. Although FRP uncertainties limit the confidence in flux estimates on a per-pixel basis, the sensitivity of biomass burning estimates to FRP uncertainties can be mitigated by conducting inventories at coarser spatiotemporal resolutions.

Type
(Inferred hot spot type)
0 = presumed vegetation fire

1 = active volcano

2 = other static land source

3 = offshore detection (includes all detections over water)

DayNight
(Day or Night)
D= Daytime fire

N= Nighttime fire
