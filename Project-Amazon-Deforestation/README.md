What is the scale of Amazon deforestation?
An exploratory data analysis.

Introduction

The dataset consists of 3 tables:

1)  deforested area in square km each year [2004-2019] in each of 9 states 
2)  nr of firespots each month each year [1999-2019] in each state
3)  information on appearance of El Ninio or La nina and its severity
4)  additional table with area of each state (km 2) and forested area in 2001 and 2020

Through the analysis of this dataset we want to shed light on the following issues:

1. Deforestation
        - is intensity of deforestation growing or decreasing between 2004 and 2019?
        - what is the scale and intensity of deforestation in different states?
        - is there a spatial pattern of deforestation?
2. Fires:
        - what is the behavior of fires: where and when do they occur?
        - is there a correlation between number of fires and deforestation?
3. El Nino/La Nina
        - is there an effect of climate phenomenas El Niño and La Niña on deforestation?
        - is there a correlation between climate phenomenas El Niño and La Niña and nr of fires?
        
        
After cleaning and transforming data, the exploratory data analysis begun

Map Charts made in Tableau showing:

   primary forest coverage in each state in 2001
   percent of deforested area till 2020
   deforested area till 2020

        
![obraz.png](attachment:54973c2a-a42b-4c59-bd31-95e7077a64f1.png)

Insights:

 - loss of 240 000 km 2 of primary forest during 20 years
 - most intense deforestation in Para, Mato Grosso, Rondonia, Amazonas
 - deforestation creeping from the south

Map Charts made in Tableau showing:

   intensity of total deforestation each year between 2004-2019 and cumulative total deforestation
   intensity of deforestation in each region each year between 2004-2019

![obraz.png](attachment:6acc9f21-5867-4ca7-b231-e890658610b1.png)

Insights:

- most intense deforestation in 2004 and than steadily decreasing
- more or less stable between 2009-2018
- increase in deforestation since 2018 in Amazonas, Para, Acre, Roraima

Charts made in Tableau showing:

   intensity of total deforestation each year between 2004-2019 and number of fires
   intensity of deforestation in each region each year between 2004-2019 and number of fires

![obraz.png](attachment:64aa382a-e961-4765-910f-9197454a5000.png)

Insights:

- most intense deforestation in 2004 and than steadily decreasing
- more or less stable between 2009-2018
- increase in deforestation since 2018 in Amazonas, Para, Acre, Roraima

Map Chart made in Tableau showing intensity and localization of firespots between 1999 and 2019

![obraz.png](attachment:5fee5e71-232b-4f67-a4d1-60e254edf5d5.png)

Insights:

 - most intense fires aggregated aroun agglomertions
 - states with most intense fires Para, Mato Grosso, Rondonia, so the same states with intense deforestation

Map Charts made in Tableau showing:

   intensity of total deforestation each year between 2004-2019 and number of fires
   intensity of deforestation in each region each year between 2004-2019 and number of fires

![obraz.png](attachment:64aa382a-e961-4765-910f-9197454a5000.png)

Insights:

- strong correlation between number of fires and deforestation at 0.906
- states with strongest correlation coefficients between deforestation and number of fires are notorious:
        Rondonia (0.907), Mato Grosso (0,838) and Para(0,767)


El Nino and La Nina seem to be very weakly correlated with intensity of deforestation and number of fires suggesting, 
that the fires appearing are not natural fires resulting from dryness brought by El nino, but man-made fires aiming at deforestation.