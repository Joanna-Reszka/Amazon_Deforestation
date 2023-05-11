# Amazon Deforestation
## What is the scale of Amazon deforestation?
#### An exploratory data analysis of dataset from Kaggle:

https://www.kaggle.com/datasets/mbogernetto/brazilian-amazon-rainforest-degradation
<br />
### Introduction

The Amazon rainforest is a moist broadleaf tropical rainforest in the Amazon biome that covers territory belonging to nine nations. The majority of the forest is contained within Brazil, with 60% of the rainforest, followed by Peru with 13%, Colombia with 10%, and with minor amounts in Venezuela, Ecuador, Bolivia, Guyana, Suriname and French Guiana.

The region provides important benefits to communities living near and far. Nearly 500 indigenous communities call the Amazon rainforest home. It’s a highly biodiverse ecosystem, home to untold species of plants and animals. The rainforest can create its own weather and influence climates around the world. Unfortunately, the fragile ecosystem faces the constant threat of deforestation and fires (for natural or anthropogenic causes).

Deforestation happens for many reasons, such as illegal agriculture, natural disasters, urbanization and mining. There are several ways to remove forests - burning and logging are two methods. Although deforestation is happening all over the world today, it is an especially critical issue in the Amazon rainforests, as the only large forest still standing in the world. There, the species of plants and animals they harbor have been disappearing at an alarming rate.

Below image showing the pattern of deforestation comes NASA Earth Observatory website:
##### https://earthobservatory.nasa.gov/images/145649/mapping-the-amazon

![obraz](https://github.com/Joanna-Reszka/Amazon_Deforestation/assets/97312220/ca556cda-7d84-4dfd-bd4f-da5769e1ce94)


### Dataset

#### The dataset consists of 3 tables:

1)  deforested area in square km each year [2004-2019] in each of 9 states 
2)  nr of firespots each month each year [1999-2019] in each state
3)  information on appearance of El Ninio or La nina and its severity
4)  additional table with area of each state (km 2) and forested area in 2001 and 2020 (https://rainforests.mongabay.com/brazil/)
5)  additional data with GDP for Brazilian regions in 1999-2019 (https://www.statista.com/)

### Questions

#### Through the analysis of this dataset we want to shed light on the following issues:

#### 1. Deforestation
##### - is intensity of deforestation growing or decreasing between 2004 and 2019?
##### - what is the scale and intensity of deforestation in different states?
##### - is there a spatial pattern of deforestation?
#### 2. Fires:
##### - what is the behavior of fires: where and when do they occur?
##### - is there a correlation between number of fires and deforestation?
#### 3. El Nino/La Nina:
##### - is there an effect of climate phenomenas El Niño and La Niña on deforestation?
##### - is there a correlation between climate phenomenas El Niño and La Niña and nr of fires?
#### 4. GDP:
##### - is there an association of GDP with intensity of deforestation?
<br />  

### Insights from the analysys 
###
#### 1. Deforestation:
#### Map Charts made in Tableau showing:
1) primary forest coverage in each state in 2001
2) percent of deforested area till 2020
3) deforested area till 2020

![obraz](https://github.com/Joanna-Reszka/Amazon_Deforestation/assets/97312220/d0841d65-2132-48d0-b4f4-12c4c856bfd6)

    
#### Insights:

##### - loss of 240 000 km 2 of primary forest during 20 years
##### - most intense deforestation in Para, Mato Grosso, Rondonia, Amazonas
##### - deforestation creeping from the south

####
##### Charts made in Tableau showing:
1) intensity of total deforestation each year between 2004-2019 and cumulative total deforestation
2) intensity of deforestation in each region each year between 2004-2019

![obraz](https://github.com/Joanna-Reszka/Amazon_Deforestation/assets/97312220/cde2c11a-12b0-4b18-ae5d-21be975c48c6)


#### Insights:

##### - most intense deforestation in 2004 and than steadily decreasing
##### - more or less stable between 2009-2018
##### - increase in deforestation since 2018 in Amazonas, Para, Acre, Roraima
####
##### Map Chart made in Tableau showing intensity and localization of firespots between 1999 and 2019

![obraz](https://github.com/Joanna-Reszka/Amazon_Deforestation/assets/97312220/77f6a84f-6646-4432-a022-5ec675c3635c)

#### 2. Fires
#### Insights:
##### - most intense fires aggregated around agglomertions
##### - states with most intense fires Para, Mato Grosso, Rondonia, so the same states with intense deforestation

####
##### Charts made in Tableau showing:
1) intensity of total deforestation each year between 2004-2019 and number of fires
2) intensity of deforestation in each region each year between 2004-2019 and number of fires

![obraz](https://github.com/Joanna-Reszka/Amazon_Deforestation/assets/97312220/3a2e1425-d554-4ccd-b4d9-3f267940e38c)


#### Insights:
##### - strong correlation between number of fires and deforestation at 0.906
##### - states with strongest correlation coefficients between deforestation and number of fires are notorious:
#####    Rondonia (0.907), Mato Grosso (0,838) and Para(0,767)

#### 3. El Nino/La Nina
##### El Ninio is regular climatic phenomenon bringing heavy droughts and increasing fire risk.
La Nina has the opposite effect of bringing cooling and moist and decreasing fire risk.
##### Charts made in Tableau showing:
1) intensity fires each year between 2004-2019 and severity of El Nino with correlation coefficient
2) intensity of deforestation  between 2004-2019 and severity of El Nino with correlation coefficient
3) the correlation of El Nino and fires per region
![obraz](https://github.com/Joanna-Reszka/Amazon_Deforestation/assets/97312220/855f221b-5039-438d-9392-6f4447a7ca22)

#### Insights:
##### - lack of general correlation (at 0.15) between number of fires and El Nino 
##### - lack of general correlation (at 0.09 ) between deforestation and El Nino
##### - regions with moderate correlation of El Ninio with fires are Amazonas, Roraima and Amapa - where most of the area is not heavilly deforested, so in other words we can see the expected correlation of increased fire risk with severe El Nino in regions tahat mostly respond to natural factors without human induced deforestation.

##### Charts made in Tableau showing:
1) intensity fires each year between 2004-2019 and severity of La Nina with correlation coefficient
2) intensity of deforestation  between 2004-2019 and severity of La Nina with correlation coefficient
3) the correlation of La Nina and fires per region
![obraz](https://github.com/Joanna-Reszka/Amazon_Deforestation/assets/97312220/e1515270-c4a5-46fb-b594-8c492ed3fd59)

#### Insights:
##### - lack of general correlation (at -0.15) between number of fires and La Nina
##### - lack of general correlation (at -0.19 ) between deforestation and number and La Nina
##### - region with moderate correlation of La Nina with (lack of) fires is costal Amapa probably, while other two costal states like Para and Maranhao    still have fires even in La Nina periods due to human induced fires and deforestation.

#### 3. GDP
##### Charts made in Tableau showing:
1) GDP perBprazilian state
2) intensity of deforestation between 2004-2019 and total GDP for Brazil 
![obraz](https://github.com/Joanna-Reszka/Amazon_Deforestation/assets/97312220/33ca41ae-1923-4354-b3cd-2c274e5e7d96)

#### Insights:
##### - regions with Highest deforestation are among those with lowest GDP
##### - there seem to be an association between growing GDP between 2004-2010 and decreasing deforestation, and when GDP starts dropping again from 2015, deforestation intensifies again

### Conclusions and reccomendations

#### Amazon as very precious biom should be protected by global community
