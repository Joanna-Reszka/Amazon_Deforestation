# Amazon Deforestation
## What is the scale of Amazon deforestation?
#### An exploratory data analysis of dataset from Kaggle:

https://www.kaggle.com/datasets/mbogernetto/brazilian-amazon-rainforest-degradation
<br />
### Introduction

The Amazon rainforest is a moist broadleaf tropical rainforest in the Amazon biome that covers territory belonging to nine nations. The majority of the forest is contained within Brazil, with 60% of the rainforest, followed by Peru with 13%, Colombia with 10%, and with minor amounts in Venezuela, Ecuador, Bolivia, Guyana, Suriname and French Guiana.

The region provides important benefits to communities living near and far. Nearly 500 indigenous communities call the Amazon rainforest home. It’s a highly biodiverse ecosystem, home to untold species of plants and animals. The rainforest can create its own weather and influence climates around the world. Unfortunately, the fragile ecosystem faces the constant threat of deforestation and fires (for natural or anthropogenic causes).

Deforestation happens for many reasons, such as illegal agriculture, natural disasters, urbanization and mining. There are several ways to remove forests - burning and logging are two methods. Although deforestation is happening all over the world today, it is an especially critical issue in the Amazon rainforests, as the only large forest still standing in the world. There, the species of plants and animals they harbor have been disappearing at an alarming rate.

### Dataset

#### The dataset consists of 3 tables:

1)  deforested area in square km each year [2004-2019] in each of 9 states 
2)  nr of firespots each month each year [1999-2019] in each state
3)  information on appearance of El Ninio or La nina and its severity
4)  additional table with area of each state (km 2) and forested area in 2001 and 2020

### Questions

#### Through the analysis of this dataset we want to shed light on the following issues:

#### 1. Deforestation:
##### - is intensity of deforestation growing or decreasing between 2004 and 2019?
##### - what is the scale and intensity of deforestation in different states?
##### - is there a spatial pattern of deforestation?
#### 2. Fires:
##### - what is the behavior of fires: where and when do they occur?
##### - is there a correlation between number of fires and deforestation?
#### 3. El Nino/La Nina:
##### - is there an effect of climate phenomenas El Niño and La Niña on deforestation?
##### - is there a correlation between climate phenomenas El Niño and La Niña and nr of fires?
<br />  

### Insights from the analysys 

#### Map Charts made in Tableau showing:
1) primary forest coverage in each state in 2001
2) percent of deforested area till 2020
3) deforested area till 2020

![obraz](https://github.com/Joanna-Reszka/Amazon_Deforestation/assets/97312220/d0841d65-2132-48d0-b4f4-12c4c856bfd6)

    
#### Insights:

##### - loss of 240 000 km 2 of primary forest during 20 years
##### - most intense deforestation in Para, Mato Grosso, Rondonia, Amazonas
##### - deforestation creeping from the south

![obraz.png](attachment:6acc9f21-5867-4ca7-b231-e890658610b1.png)

##### Map Charts made in Tableau showing:
###### intensity of total deforestation each year between 2004-2019 and cumulative total deforestation
###### intensity of deforestation in each region each year between 2004-2019

#### Insights:

##### - most intense deforestation in 2004 and than steadily decreasing
##### - more or less stable between 2009-2018
##### - increase in deforestation since 2018 in Amazonas, Para, Acre, Roraima

![obraz.png](attachment:64aa382a-e961-4765-910f-9197454a5000.png)

##### Charts made in Tableau showing:
###### intensity of total deforestation each year between 2004-2019 and number of fires
###### intensity of deforestation in each region each year between 2004-2019 and number of fires

#### Insights:

##### - most intense deforestation in 2004 and than steadily decreasing
##### - more or less stable between 2009-2018
##### - increase in deforestation since 2018 in Amazonas, Para, Acre, Roraima

![obraz.png](attachment:5fee5e71-232b-4f67-a4d1-60e254edf5d5.png)

##### Map Chart made in Tableau showing intensity and localization of firespots between 1999 and 2019

#### Insights:
##### - most intense fires aggregated aroun agglomertions
##### - states with most intense fires Para, Mato Grosso, Rondonia, so the same states with intense deforestation

![obraz.png](attachment:64aa382a-e961-4765-910f-9197454a5000.png)

##### Map Charts made in Tableau showing:
##### intensity of total deforestation each year between 2004-2019 and number of fires
##### intensity of deforestation in each region each year between 2004-2019 and number of fires

#### Insights:
##### - strong correlation between number of fires and deforestation at 0.906
##### - states with strongest correlation coefficients between deforestation and number of fires are notorious:
#####    Rondonia (0.907), Mato Grosso (0,838) and Para(0,767)


##### l Nino and La Nina seem to be very weakly correlated with intensity of deforestation and number of fires suggesting, 
##### that the fires appearing are not natural fires resulting from dryness brought by El nino, but man-made fires aiming at deforestation.
<br />

### Conclusions
