# Introduction and first results

From July 08th 2022 to September 25th 2022, 7 sensors were placed in urban and rual locations around Biel/Bienne to capture air temperature measurements and plan for a larger surveillance network for summer 2023.

*The first data collection occured from 11.08.2022 - 14.08.2022. The raw data set is available through the sister github repository upon request.*

The below plots are of uncorrected data fresh from the first readings and demonstrate three initial points:
1) All locations track reasonbly well by eye, no clear interruptions in any measurements.
2) All data captured and transmitted correctly
3) Rural minimum temperatures are consistently below urban ones, converge with urban temps on maximum values
4) The rural references correspond well
5) The Park Muncipal / Stadtpark sensor (Log_4) registered the highest temperatures -> likely due to lack of ventilation.

```{figure} figures/results/summary.png
---
height: 450px
name: summary
---
Summary statistics of all data points from July 08th - July 11th 2022
```
```{figure} figures/results/summary_grouped.png
---
height: 450px
name: summary_grouped
---
Line plot of sensors grouped by rural, urban, park, and overall mean.
```
