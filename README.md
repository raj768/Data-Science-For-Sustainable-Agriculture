# Data-Science-For-Sustainable-Agriculture

## Final Year Project

### Project Description:

The environment and global food security depend on sustainable agriculture, which involves using farming techniques that are environmentally friendly to produce crops while preserving the fertility and health of the soil. To accomplish this, farmers need accurate information on soil parameters such as nutrients, soil moisture, and pH levels. Important decisions, such as maintaining soil health, minerals, and nutrients, preventing erosion, deciding which crops to grow, determining care needs like the necessary amount of water and fertilizer for plants, and identifying the best planting and growing conditions, all depend on this information.
In addition, the United States Department of Agriculture (USDA) must comprehend various field aspects to provide sound advice to the government on managing the land, utilizing ecological water, and combating rising CO2 levels. Eddy covariance (EC) or an infrared gas analyzer is used for measurements (Wagle, 2019), and these systems have remote monitoring capabilities. They must also be scalable for improved monitoring, which might incur significant expenses when established in the field. The USDA is primarily interested in values such as the Enhanced Vegetation Index (EVI) and Land Surface Water Index (LSWI). Net Ecosystem Exchange (NEE), Gross Primary Product (GPP), and environmental respiration (ER) are all critical factors in managing CO2 levels. The USDA has been exploring ways to use weather data, including average temperature (TAVG), average relative humidity (HAVG), average daily vapor deficit (VDEF), heating degree days (Hdeg), cooling degree-days (65 standards) (CDEG), average wind speed (Wspd), solar radiation, and rainfall, to predict field variables, rather than solely relying on sensor data. The USDA measures the Enhanced Vegetation Index (EVI) and Land Surface Water Index (LSWI) using moderate-resolution spectroradiometer (MODIS) satellite images.
Earlier research has demonstrated that weather and Enhanced Vegetation Index (EVI) data can predict several field and soil characteristics effectively. The data also indicates variations in the values of field parameters across different pastures. In this context, our approach involves predicting the field characteristics of multiple pastures using information from a single pasture instead of relying on sensor data. This methodology is expected to assist the USDA in optimizing resource allocation and avoiding unnecessary expenditures.





### Objectives:

From a technical perspective, the project's main objective is to provide the USDA with a better awareness of the conditions in all fields so that decisions can be made without installing expensive monitors.

•	Predictive Modeling of EVI and LSWI: The first objective of our project is to use one pasture data (Weather and soil variables of P13) to predict satellite readings such as Enhanced Vegetation Index (EVI) as well as Land Surface Water Index (LSWI) and then validate the same for two different pastures. The data provided here is a daily value, so we must interpolate the 8-day satellite readings to create daily estimates using linear interpolation.

•	Predictive Modeling of ER: The project's second objective is to use weather, and soil variables, and combine them with one of the 3-sensors measurements of Gross Primary Production (GPP), Net Ecosystem Exchange (NEE), Evapotranspiration (ET) at a time to model for environmental respiration (ER).


