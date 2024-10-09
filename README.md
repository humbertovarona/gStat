# gStat

Geostatistical analysis of oceanographic and meteorological datasets

# Version

1.7

# Release date

2024-04-09

# DOI

[https://doi.org/10.5281/zenodo.13243330](https://doi.org/10.5281/zenodo.13243330)

# License

MIT

# Description

Geostatistics is a branch of applied statistics that focuses on the analysis and modeling of spatial and geographic phenomena. It uses mathematical and statistical methods to study and predict the distribution of variables that vary in space, such as the concentration of minerals in the soil, air quality in a region, or the distribution of species in an ecosystem. Through techniques like kriging, geostatistics allows for the interpolation and estimation of values in unsampled areas, providing precise maps and models that are essential for decision-making in fields like geology, hydrology, agronomy, and urban planning. This discipline integrates spatial data with contextual information to offer a more comprehensive and detailed view of the studied environment, thus contributing to better management and utilization of natural resources.

A software that performs geostatistical analysis is essential because it allows users to process and analyze spatial data efficiently and accurately. Its importance lies in several key aspects:

1. ***Precision in Decision Making:*** By providing accurate maps and models of the distribution of spatial variables, it helps make informed decisions in fields like geology, hydrology, agronomy, and urban planning.
2. ***Interpolation and Estimation:*** It uses advanced techniques like kriging to estimate values in unsampled areas, allowing for a more comprehensive understanding of the studied phenomenon without the need for exhaustive sampling.
3. ***Handling Large Volumes of Data:*** It can process large sets of spatial data, facilitating the analysis of trends and patterns in environmental and natural resource studies.
4. ***Resource Optimization:*** It helps identify areas of interest or concern, enabling better management and utilization of natural resources, as well as the implementation of mitigation measures in problematic areas.
5. ***Data Integration:*** It allows for the integration of spatial data with contextual information, offering a holistic view of the environment and improving the understanding of interactions between different variables.

___

The following software creates maps, 2D Longitude x Time, Latitude x Time figures and distribution histograms for the following statistical tests:

***Mean:*** In geostatistics, the mean is used to determine the average value of a spatial variable, such as the concentration of a mineral in a region. This helps provide an overall view of the average level of the variable under study across the area.

***Standard Deviation:*** The standard deviation in geostatistics measures the variability of spatial data around the mean. For example, in a soil contamination study, a low standard deviation would indicate that contaminant concentrations are uniformly distributed near the mean, while a high standard deviation would show a more dispersed distribution.

***Variance:*** Variance is used to quantify the dispersion of spatial data. In geostatistics, it helps assess the extent of variability in the spatial distribution of a variable, such as soil moisture in an agricultural region.

***Coefficient of Variation (CV):*** The coefficient of variation is used in geostatistics to compare the variability of different spatial data sets with different units or means. For example, it can be used to compare the variability of the concentration of two different minerals in a mine.

***Mean Absolute Deviation:*** In geostatistics, the mean absolute deviation is useful for understanding the variability of spatial data in a way that is less sensitive to extreme values. It can be applied to evaluate the consistency of water quality at different points in a river.

***Median Absolute Deviation (MAD):*** The median absolute deviation is used in geostatistics as a robust measure of dispersion, especially useful in the presence of outliers. It can be applied to assess variability in temperature measurements at different weather stations within a region.

***Mean Standard Error (MSE):*** The mean standard error in geostatistics is used to estimate the precision of the mean of a set of spatial data. For example, when sampling the concentration of a pollutant in the air, the MSE helps determine the precision of the estimate of the mean concentration across the city.

# How to install

Matlab 2023b compatible software

- Open Matlab
- Go to APP tab
- Click on the "Install App" button
- Select the gStat.mlappinstall file
- In the Install dialog click on the "Install" button

Create a directory and copy into it the following databases: etopo_2.mat, gshhs_f_coast.mat, gshhs_f_rivers.mat, and wdb_f_borders.mat.

# How to run

Type in the Matlab command window:

```sh
>> gStat <Enter>
```
or Find gStat in the APP tab of Matlab.

# Cite as

Humberto L. Varona, Silena Herold-Garcia, Carlos Noriega, Moacyr Araujo, & Fabrice Hernandez. (2024). Geostatistical analysis of oceanographic and meteorological datasets (gStat). (1.7). Zenodo. https://doi.org/10.5281/zenodo.13243330
