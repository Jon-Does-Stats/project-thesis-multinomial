Each csv represents the reflectance at each given point. Well, it's technically irradiance (the variable directly measured by the RS instrument; but a proxy here for reflectance). The output table is ~ 60 x 146 for a calendar year. Each row is a point (see ID attribute for xwalk) and the 146 columns represent the value at each time step. 

NA fill values due to cloud, shadow, snow, etc. = -9999. A scaling factor of 0.0001 is applied to the data to reduce the bit size of rasters. You can multiply the data by 0.0001 to achieve the actual percent reflectance - but this is not necessary for any statistical work. 

Filename includes the band name at the end (eg. NM_Sentinel2_2020_B8.csv = B8 reflectance for calendar year 2020).

The spatial resolution of bands 2,4 and 8 are 10 m. Bands 5-7, 8A, 11 and 12 are 20 m. no bands were resampled.


