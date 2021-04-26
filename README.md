# CoronaLens
Coronavirus dataset exploration;


The target of this project is to analyse the evolution of the coronavirus pandemic in Romania; 
We have made use of dataset provided by Ministry of Health in Romania. 
The dataset contains information cummulated in the month of March regarding the rate of infection in romania per counties, the number of PCR / Quick Tests , the number of hospitalised people per each hospital in romania, hospitalised people in ICU, the number of deceased per each day.
We decided to select the month of March as the start of our project as it marks the start of the third outburst of Covid-19 in Romania; 


The dataset contains time series and geographical data so the difficulty of representing it was increased. We have drawn important conclusions from the dataset such as: the most effective hospitals, the most affected areas, the counties which would need more support in their fight against the pandemic. We have added interactive plots which help our reasoning;

Seeing the data, we decided that one of the most helpful things which will actually have an impact on the evolution of the virus would be the creation of a machine learning model which could predict the spread of the virus allowing us to supplement the ICU units total available places for a certain hospital; In this way we could save lives by sparing the time needed to transfer infected people to other ICU units;

We have made use of SHAP and LIME model interpreters to be able to anaylse the reasoning of our machine learning algorithms;

Link to the dataset : 
(https://data.gov.ro/dataset/transparenta-covid)
Credits to data.gov.ro for developing their data sharing platform;
