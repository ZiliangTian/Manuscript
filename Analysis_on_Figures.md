# Figure 1

![Figure 1](https://github.com/ZiliangTian/Manuscript/blob/master/Figure1.png)
Figure 1: The left is differences in the spatial coverage between CCAM-ensemble and BARRA-TA. 
Blue is the 10 km-resolution CCAM-ensemble grid and in red indicates the area where the 1.5km
resolution BARRA-TA grid downscaled to 10 km-resolution extends beyond the CCAM-ensemble 
coverage. The right top one is one of the soil parameters (Volume fraction of condensed water 
in soil at critical point) in BARRA-TA. The right bottom one is two soil types in CCAM

## Comments
* It is inaccuracy to compare soil typw with soil parameters;
* CCAM's soil parameters are more than 3 (From Marcus's Comment).

# Figure 2 and Figure 3

![Figure 2](https://github.com/ZiliangTian/Manuscript/blob/master/Figure2.png)
Figure 2 An example monthly time-series for west Tasmania representing the percentage if change
in the monthly mean of soil moisture compared to temperature, precipitation and evaporation for
both ACCESS1-0 and BARRA-TA. (Values have been rescaled to a common scale for comparison).

![Figure 3](https://github.com/ZiliangTian/Manuscript/blob/master/Figure3.png)
Figure 3 An example monthly time-series for east Tasmania representing the percentage of change
in the monthly mean of soil moisture compared to temperature, precipitation and evaporation for
both ACCESS1-0 and BARRA-TA. (Values have been rescaled to a common scale for comparison).

## Methods

Considering the different topography and precipitation in west and east Tasmania, we took one 
point in each of these regions and compared the monthly time-series over 8 years (2007-2014) 
between ACCESS-G - one of the CCAM RCMs as an example - and BARRA-TA over soil moisture and 
related variables. The reason for ACCESS-G is that we found one model’s extreme values were 
averaged out by the other five models in the ensemble mean. Because of the different unit and 
magnitude between the variables we considered, for visualizing the change we had to rescale the 
variation.

## Outcome

We first investigated the monthly variation of soil moisture with its monthly mean value at two 
grid cells, one in west Tasmania (Figure 2) and one in east Tasmania (Figure 3) over the common 
period (2007-2014). The high correlation area in the west means that the west grid cell can be 
representative for the cells around it and it can be used to explore the relationship between 
soil moisture and a range of variables. The east grid cell is in a low correlation area and it 
could show a time-series different from the western area. 

In the west grid cell, the time-series of monthly soil moisture is very similar in all four 
layers of ACCESS1-0, all showing a strong correlation (or anticorrelation) with precipitation, 
temperature and evaporation (Figure 2). In BARRA-TA however, there is an obvious lag between 
the different soil layers, which increases with depth. This lag of more than one month, lead to
low correlation of the soil moisture in the bottom layers with surface conditions. Comparing 
ACCESS1-0 with BARRA-TA, we find that the annual cycle is more obvious in ACCESS1-0 and more 
intra-annual change is represented in the later. The lag in ACCESS1-0 is small, and is more 
variable with the lower values of soil moisture. The fluctuation in temperature had less 
amplitude than other values, which could translate into higher correlation values by least 
square regression. 

With low evaporation in the east grid cell, the time-series of soil moisture in the top layer 1 
fluctuated more than in the other three soil layers (Figure 3). Layers 2 to 4 showed lower 
values and less correlation in the soil moisture and the three related variables compared to 
layer 1. Analyzing the precipitation and soil moisture in the four layers, there were more 
random changes with lower precipitation values than in west region, and the change was dominated 
by extreme precipitation values each time. In the analysis of each CCAM ensemble member and the 
CCAM-ensemble mean, we found that one model’s extreme values were averaged out by the other five 
models.

## Discussion

In the spatial correlation of soil moisture between CCAM-ensemble and BARRA-TA, we found the 
correlation values of soil moisture are higher in the west and north of Tasmania. The topography 
of south-east Tasmania is mostly lowland, resulting in mostly dry area with lower annual 
precipitation than the north and west mountainous region (Grose et al. 2010; White et al. 2013). 
In dry areas, the change of soil moisture is more closely related to episodic precipitation. But 
in wet areas, soil moisture will dry out or filtrate slowly over time, which can be easier to 
simulate in both models. Hence in dry areas, the timing of simulated precipitation is crucial for
an accurate modelled output of soil moisture.

## Comment

Explain why choose these two grid cells within all grid cells.

I think these two figures could make reader confused and should be deleted. (or is there better 
way to present it?)

Detail: Why confused? 
Because it needs to explain how we ensure the location of the two grid cells, and why just take 
one grid cells at each west and east region, as well as how we judge the boundary between west 
region and east region.

Also, we only consider ACCESS1-0 model in CCAM. Should it be explained why we take the ACCESS1-0 
as example?

# Figure 4 and Figure 5

![Figure 4](https://github.com/ZiliangTian/Manuscript/blob/master/Figure4.png)
Figure 4 The correlation between soil moisture and a range of variables in CCAM-ensemble from 
the multi-year monthly mean value over all grid cells in Tasmania, in comparison with BARRA-TA. 
Here, the resolution of CCAM-ensemble and BARRA-TA is 10km and 1.5km respectively.

![Figure 5](https://github.com/ZiliangTian/Manuscript/blob/master/Figure5.png)
Figure 5 The percentage of grid cells (on y-axis) greater than each correlation value. 
CCAM-ensemble members are coloured lines, with the CCAM-ensemble mean in black. BARRA-TA is 
represented as the dark-blue line. The red vertical line marks the 75% of all grid-cells 
threshold. A-C) shows the correlation between soil moisture and A) precipitation; B) 
temperature; C) evaporation.

## Method

We extracted the monthly time-series for soil moisture, precipitation, surface temperature and 
evaporation for each grid cell from each of RCMs and from BARRA-TA, and we explored the 
correlation between the range of variables using least squares regression provided by Schulzweida 
et al. (2006). The correlation values are the mean from individual correlation from each member 
of the ensemble. We selected the periods 1990-2019 and 2007-2014 in CCAM and in BARRA-TA, 
respectively.

To compare the soil moisture in CCAM and BARRA-TA, we took the mean of CCAM ensemble. Each grid 
cell from BARRA-TA and CCAM-ensemble had an eight-year monthly dataset from 2007 to 2014, and a 
multi-year monthly mean. We used the correlation equation least squares regression provided in 
Climate Data Operators (Schulzweida et al. 2006) to calculate the mean value between BARRA-TA and 
CCAM-ensemble. Then we did the statistics of spatial correlation and split the correlation into 
higher correlation area and low correlation area based on a critical point, which is described in 
detail below.

In order to calculate the statistics of the spatial correlation, we checked the distribution of 
correlation values over all grid cells. For this, we chose 21 correlation values between soil 
moisture and precipitation from 0 to 1 with a 0.05 interval (from -1 to 0 for the negative 
relationship between soil moisture and other two related variables: temperature and evaporation). 
We calculated the percentage of grid cells above each correlation value, as well as the average 
percentage of CCAM-ensemble. Last, we mark the 75% percentage line to better explain the change of 
curve between models.

## Outcome

We investigated the spatial correlation between soil moisture and three related variables: 
precipitation, surface temperature and potential evaporation in CCAM-ensemble and compare them with
similar metrics from BARRA-TA.

Similar to the correlation of soil moisture between CCAM-ensemble and BARRA-TA, higher correlation
values were observed mainly in west Tasmania (Figure 4). Due to the negative relationship between
soil moisture and two related variables: surface temperature and potential evaporation – the soil
loses moisture with increasing surface temperature and hence increasing potential evaporation – a
strong correlation between these variables is indicated by the most negative correlation values (-1)
. In the spatial distribution, grid cells with high correlations (above 0.5 or below -0.5) were 
located mostly in western Tasmania, while grid cells with low correlation values (below 0.5 or 
above -0.5) were located mostly in eastern Tasmania (Figure 4).

In the CCAM-ensemble, the first three layers showed similar pattern of correlation, but lower 
correlations in bottom layer 4 in all related variables. In BARRA-TA, the lower-correlation grid 
cells were located predominantly in the eastern Tasmania in the top three layers, and in particular
in layer 3. In the fourth layer however, negative-correlation grid cells were distributed all over 
the study region, with the lowest values predominantly in the east part of Tasmania.

Here is the statistics of the spatial pattern of these correlations. 

For the correlation with precipitation and temperature, CCAM-ensemble had better result of spatial
distribution, where the correlation value is higher with 75% percentage than BARRA-TA (Figure 5-A 
and 5-B). In contrast, BARRA-TA had more grid cells with higher correlation with evaporation of 
around 75 % than CCAM-ensemble in the first two layers (Figure 5-C).

For the soil layers from surface to bottom, the high correlation (or anticorrelation) area 
decreased with depth in both CCAM-ensemble and BARRA-TA. There is difference between top layers 
and bottom layers and also between CCAM-ensemble and BARRA-TA.

## Discussion

Our results indicate that CCAM-ensemble has higher correlations of soil moisture with precipitation
and temperature than BARRA-TA, and higher correlation of soil moisture and evaporation in the first
two layers. Best et al. (2011) points to multiple factors influencing surface evaporation, like 
evapotranspiration and bare soil evaporation. Plant root extraction for evapotranspiration can be 
another way to transport soil moisture into the atmosphere (Kowalczyk et al. 2006). Similarly, 
precipitation and surface temperature have a more complicated relationship with soil moisture than 
linear correlation. Our results could suggest that precipitation and surface temperature have a 
higher weight in adjusting the soil moisture in CCAM-ensemble than in BARRA-TA, and evaporation has
a higher weight to this purpose in BARRA-TA than the CCAM-ensemble. 

Our results showed that the top two layers in both CCAM-ensemble and BARRA-TA have a better 
representation of the relationship between soil moisture and the variables we investigated than the
bottom layers. As shown in Figure 2 and 3, a larger time lag exists in BARRA-TA but only slightly 
larger in CCAM-ensemble, which could cause lower correlation values in the bottom layers between 
CCAM-ensemble and BARRA-TA. The correlation values of soil moisture between CCAM-ensemble and 
BARRA-TA are higher in the west and north Tasmania. In our study we found that the area of high 
correlation decreases with depth in CCAM-ensemble and BARRA-TA, and much faster in the latter. The
different performance through layers, region and between two models could be caused by the 
different performance of layer, region within soil between CCAM and BARRA-TA, discussed in the 
following section. 

## Comment

Based on soil moisture, these two figures said there are different correlation between soil 
moisture and related variable over different region. But it just a beginning to show the different 
distribution of correlation over all domain.

Also, it shows that soil moisture has different weight with three related variables. Maybe this is 
the key point here.

# Figure 6

![Figure 6](https://github.com/ZiliangTian/Manuscript/blob/master/Figure6.png)
Figure 6 Soil profiles of CCAM-ensemble and BARRA-TA in different time periods: a) the six-layers 
soil profile of CCAM-ensemble from 1990 to 2019; b-d) four-layer soil profile of CCAM-ensemble and 
BARRA-TA from: b) 1990 to 2019; c) 2007 to 2016; and d) 2007 to 2014. The soil profiles are derived
from six (a) or four (in b, c, d) data points at the middle of each soil layer. Soil layer 
boundaries are represented by the brown long dash line. The data points for each layer is the mean 
value calculated from models throughout the corrected map range and the whole periodnnnn.

## Method

To allow comparison between BARRA and CCAM, we converted the six soil layers in CCAM into four soil
layers matching the soil layers in BARRA (Table 3). Soil moisture is measured in cubic meter per 
cubic meter (m3/m3), and is considered homogeneous vertically within the same soil layer (Best et 
al. 2011; Kowalczyk et al. 2006), which can be presented in both CCAM and BARRA-TA. In order to 
define the new four soil layers in CCAM, we calculated the weighted sum of soil moisture from CCAM’s
original six layers relative into the four new layers (Table 3). 

The soil profiles are derived from six (a) or four (in b, c, d) data points at the middle of each 
soil layer. Soil layer boundaries are represented by the brown long dash line. The data points for 
each layer is the mean value calculated from models throughout the corrected map range and the 
whole period.

## Outcome

The data points for each layer represent the spatial mean value of BARRA-TA and CCAM-ensemble 
throughout the standardized map range and the whole period. The profile of the six soil layers in 
CCAM-ensemble show that the soil moisture increased with depth (Figure 6a). In BARRA-TA, the first 
three layers were consistent throughout the two time periods (2007-2016 and 2007-2014), with the 
fourth layer being slightly different between the two periods.

For the CCAM-ensemble, soil moisture increased with depth showing the steepest change between the 
first and the second layer. In BARRA-TA, soil moisture reached its maximum in the second layer, 
and then decreased with depth. This suggests that the top two layers of BARRA-TA and CCAM-ensemble 
have a higher similarity, while the bottom two layers is relatively very different.

## Discussion

The mean value in the first two top layers increased with depth for both CCAM-ensemble and BARRA-TA.
For the bottom two layers, the soil profile decreased in BARRA-TA but continued to increase in 
CCAM-ensemble (Figure 6).

## Comment

Why take soil profile? 
Is there has strong evidence to present the difference of soil layers by soil profile?

# Figure 7

![Figure 7](https://github.com/ZiliangTian/Manuscript/blob/master/Figure7.png)
Figure 7 Monthly time-series of soil moisture in BARRA-TA (in black) and CCAM-ensemble (in colour) 
between 2007-2016. The data is derived from the monthly mean across the entire region of Tasmania.

## Method

## Outcome

Figure 7 shows ten years (2007-2016) of monthly time-series of soil moisture in BARRA-TA and 
CCAM-ensemble. The value is calculated from the mean monthly value across the entire region of 
Tasmania. In the top two layers, the time-series values were higher in BARRA-TA than in 
CCAM-ensemble and showed a similar interannual cycle between the two models. In the bottom two 
layers, the ten-year time-series differed between the two periods (2007-2014 and 2015-2016) of 
BARRA-TA, with soil moisture values in the first period consistently higher than in CCAM-ensemble. 
The third soil layer showed a similar interannual cycle in its moisture content, while the fourth 
layer had a more varied value, with little evidence of an interannual cycle. In the second period 
of BARRA-TA, the third- and fourth-layer soil moisture values were mostly lower than in 
CCAM-ensemble. This suggests that these steep changes occur at the transition from JULES to 
ACCESS-G in BARRA-TA, which are related to the different methods of simulating the land-surface 
environment between the two time periods. In our evaluation of CCAM-ensemble, we used only the 
JULES model offline simulation data from 2007 to 2014, with focus on the top two soil layers.

## Discussion

In 2015/2016, , the base model for regional reanalysis in BARRA was changed from UM to ACCESS-G 
and the land surface model was changed from JULES to MOSES 2 (Best et al. 2011; Su 2018). The 
latter model takes different methods to handle the land surface environment (Best et al. 2011; BoM 
2010), with more focus on the atmospheric study and increased impact on the absorption of soil 
moisture around the plant root zone. For the study of soil moisture, we chose to use the JULES 
operation period in order to provide consistent assessment of CCAM-ensemble, that is, the period 
2007-2014.

We found soil moisture in BARRA-TA was typically higher than in the CCAM-ensemble. Previous studies
showed that this could arise from the method used to model the hydrological processes. For example,
in JULES, there are two pathways for the water once it reaches the soil surface: infiltration into
the soil and surface runoff (Best et al. 2011). In BARRA, JULES has runoff switched off, as the 
river routing is not included for the limit-area model (Su 2018). In CCAM, CABLE takes surface 
runoff as one of the dominant factors for the flux of infiltration (Kowalczyk et al. 2006). The 
large source of water into the soil in BARRA-TA may cause these higher values than CCAM. This study
focused on the general trends, rather than the absolute soil moisture values.

## Comment

In the result, there should point out the difference between two period.

# Figure 8, Figure 9 and Figure 10

![Figure 8](https://github.com/ZiliangTian/Manuscript/blob/master/Figure8.png)
Figure 8 The correlation of monthly annual cycle between soil moisture in CCAM-ensemble and 
BARRA-TA calculated from the multi-year monthly mean values over all grid cells in Tasmania. Here, 
the resolution of CCAM-ensemble and BARRA-TA is 10km.

![Figure 9](https://github.com/ZiliangTian/Manuscript/blob/master/Figure9.png)
Figure 9 the percentage of grid cells (y-axis) with correlation values higher than the critical 
point (x-axis) over all model grid cells for CCAM-ensemble (in colour). The CCAM-ensemble mean 
value is shown in black for reference.

![Figure 10](https://github.com/ZiliangTian/Manuscript/blob/master/Figure10.png)
Figure 10 Partition of the correlation map by the correlation critical point 0.90. The top (bottom)
row shows grid cells with higher (lower) correlation values than the critical correlation point 
(0.90) from layer 1 to layer 4.

## Methods

For visualizing the spatial distribution within soil moisture between CCAM-ensemble and BARRA-TA, 
we split each correlation map into two parts: high-confidence areas and low-confidence area based 
on the critical point.

In choosing the critical point, we decided to:
*	Take the CCAM-ensemble mean. 
*	Consider the first surface soil layer as the standard, because the distribution of the 
correlation values among the four layers was not consistent. This was justified because the first 
surface soil layer provides the platform for direct interaction between precipitation, surface 
temperature, evaporation and soil moisture and it can avoid the contribution of differing 
hydrological models;
*	Choose the critical correlation point which was the closest to 75% percentage in the first layer 
in the CCAM-ensemble.

## Outcome
There is the correlation of soil moisture between CCAM-ensemble and BARRA-TA over the entire region
of Tasmania. The multi-year monthly mean values showed higher correlation in most grid cells in the
first three layers (Figure 8), which could reflect a strong interannual cycle in the CCAM-ensemble. 
The first two soil layers showed a similar pattern where the correlation values are higher than 0.9 
over more than 71% grid cells (Figure 10). The third soil layer was less well correlated, with the 
lowest correlation in the fourth soil layer, particularly in the southeast corner (where the 
correlation was also negative) (Figure 10). This correlation decreased towards the east, the lowest
value being observed on the east coast of Tasmania. In the fourth layer however, there was a high 
correlation from inland western Tasmania towards central Tasmania. Very high correlation values 
were observed in the first three soil layers (Figure 9), with the percentage of grid cells with 
high correlation rapidly decreasing once below 0.85. In the fourth layer the situation is different.
The percentage of grid cells with high correlation decreased consistently.  

## Discussion

In the spatial correlation of soil moisture between CCAM-ensemble and BARRA-TA, we found the 
correlation values of soil moisture are higher in the west and north of Tasmania. The topography 
of south-east Tasmania is mostly lowland, resulting in mostly dry area with lower annual 
precipitation than the north and west mountainous region (Grose et al. 2010; White et al. 2013). In
dry areas, the change of soil moisture is more closely related to episodic precipitation. But in 
wet areas, soil moisture will dry out or filtrate slowly over time, which can be easier to simulate
in both models. Hence in dry areas, the timing of simulated precipitation is crucial for an 
accurate modelled output of soil moisture.

Technically, the characteristics of soil could be represented by the soil type (Koster et al. 2009
). Soil type in BARRA-TA has various change spatially, but is more consistent in the east region 
than soil type in CCAM (Figure 1). CCAM has only two separate soil types, and has uneven 
distribution in the east region. Therefore, soil type in BARRA-TA could be more realistic to 
represent the characteristics of soil. The soil types in BARRA-TA and CCAM are composed of multiple
parameters (Table 2), they are constant in time and do not change with precipitation, which can be
a limitation, especially for applications on a small spatial scale over a long period of time 
(Corney et al. 2010).

## Comment 

Need more evidence.

# Figure 11

![Figure 11](https://github.com/ZiliangTian/Manuscript/blob/master/Figure11.png)
Figure 11 The correlation of daily seasonal and annual time-series between soil moisture in 
CCAM-ensemble and BARRA-TA calculated from the multi-year daily mean values over all grid cells in 
Tasmania. Here, the resolution of CCAM-ensemble and BARRA-TA is 10km.

## Method

For calculating the seasonal variation, we used the daily soil moisture in layer 1 and 2 for four 
calendar seasons in 1990-2019 for CCAM-ensemble and 2007-2014 for BARRA-TA. We calculated the 
seasonal mean at each grid cell for the CCAM-ensemble members.

For the same range of years, we explored the correlation of season variation in layer 1 and layer 2, 
by calculating the multi-year daily mean values for each season and each grid cell. We calculated 
correlation values from BARRA-TA and each CCAM-ensemble member by least squares regression, and then 
calculated the CCAM-ensemble mean. 

## Outcome

For the seasonal variation, different seasons has different distribution of spatial correlation. In 
summer, there are more low correlation grid cells in the east region. In Winter, there are more low 
correlation grid cells in the west and south region, and also the east coastline. The grid cells with
high correlation in winter are mostly distributed in the middle and north Tasmania. In autumn and 
spring, the grid cells with high correlation takes most region but not the east coastline. Overall, 
the eastern region had a higher number of grid cells with low correlation of seasonal variation in 
layer 1 and 2 between CCAM-ensemble and BARRA-TA (Figure 11). More extensive areas of low correlation
were observed in summer and winter, with the winter low correlation area extending over almost the 
entire region. 

## Discussion

This study shows a lower correlation between CCAM-ensemble and BARRA-TA over most grid cells in 
winter compared to the other three seasons. Also, low correlation was observed in the east region in 
summer, and to a smaller degree in autumn and spring. The grid cells with lower correlation are 
mostly dry in summer. The difference in seasonal maximums across the four seasons in the 
CCAM-ensemble and BARRA-TA could cause the lower values observed in the winter.

## Comment

Not enough to explain the seasonal change of soil moisture

What we got now is only the correlation between BARRA and CCAM for the seasonal dataset

How about the seasonal time series? The seasonal value of soil moisture shown in the map?

# Figure 12

![Figure 12](https://github.com/ZiliangTian/Manuscript/blob/master/Figure12.png)
Figure 12 Percentage of change in soil moisture in CCAM-ensemble between three periods: historical 
(1960-1989), current (1990-2019) and future (2070-2099) and for each season. Columns from one to 
five correspond to the change in annual, autumn, spring, summer and winter.

## Method

We explored the projected values of soil moisture for three time periods: historical (1960-1989), 
current (1990-2019) and future (2070-2099). We calculated the mean value for each grid cell. We 
found that RCMs were very similar, therefore we considered the mean of the CCAM-ensemble. We 
compared the variation of soil moisture in the top two soil layers across 30 years, between historic
and current period and between historic and future period. To analyse the seasonal change in soil 
moisture, we considered four calendar seasons (MAM, SON, DJF, JJA) and compared its variation in the 
future from historical and current period.

## Outcome

There has been minimal change between the historical and current periods, where the change is within 
5%. In exploration of future projections from the CCAM-ensemble, the general trend indicates that 
the soil moisture will decrease in the region of Tasmania in the future, with the driest area being 
projected to be around the central plateau. The east region will get wetter in summer and autumn in 
the future (Figure 12-B). This wetter area had low correlation of soil moisture between BARRA-TA and 
CCAM-ensemble (Figure 11). Soil moisture will be lower in all the study region in winter and spring 
and with less change in the west Tasmania in winter. In regards with the current change (Figure 
12-A), the wetter region in the east region is expected to decrease in the future, while the drier 
region is expected to increase.

## Discussion

Model predictions show that wetter area could decrease in the future in the east region of Tasmania,
while the drier area could increase. This could be caused by the rise of temperature in Tasmania, 
while the drier area could increase. 

Focusing on the surface layers, which we have more confidence in than the lower layers for the 
reasons discussed above, shows that the future changes between layer 1 and layer 2 have the same 
pattern in CCAM-ensemble. Soil moisture in layer 1 has larger change than in layer 2, which could be 
caused by direct effect with related variables in surface layer 1.

Spatially, the drier area with large magnitude (more than 10% approximately) has higher correlation 
compared with BARRA-TA than the wetter or slight-changed area in the future. In summer, the 
correlation between CCAM-ensemble and BARRA-TA shows there are high correlation in the west region 
in the future change. The west region will become drier than the east region, where the soil moisture
will increase or change slightly in the future. In winter, the correlation between CCAM-ensemble and 
BARRA-TA shows there are lower correlation in the southwest region. In future change, this region is 
no obvious change or change slightly. 

Supported by BARRA-TA, CCAM can be confident to project the future change in the region, where the 
soil moisture will decrease rapidly (approximately more than 10 %)

## Comment

The future change is based on the seasonal change. As the seasonal change has not been explained 
enough, the future change is suspicious.
