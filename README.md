# Data Analysis for the Decathlon Sissy Mua Marketing Campaign

## Introduction

The notebook has mainly utilised the Pandas library for the data analysis. Running the code below with a conda environment set-up should allow one to run the notebook smoothly.

```bash
conda create -n decathlon
conda activate decathlon
conda install pandas
conda install jupyter
```

The steps proceeding to the result of the analysis are in the analysis.ipynb. This [README.md](http://README.md) file  provides a brief verbal description and explanation for the analysis. 

The code has to be properly run with the 5 CSVs. They should be put in the folder called /dataset. 

## Objectives of the Study

1. The team in charge of this influence campaign wants to know if the objective of rejuvenating its target population has been achieved.
2. In addition, Fitness Cardio wonders if this campaign was profitable for Decathlon. To answer this last question, you can apply an average margin rate of 20%*.

The main objective of this influencer campaign was to recruit new Generation Z customers from social networks.

## Results

1. The objective of rejuvenating the target population (Generation Z Women) is successful. The analysis is done by analysing the traffic and transactions amount of the Female Fitness Cardio products before and after the campaign, specifically of the population born after 1995. The average traffic of members born after 1995 browsing the Female Fitness Cardio products website has increased 42% after the campaign. The average transactions per day of members born after 1995 buying the Female Fitness Cardio products website has increased 41% after the campaign as well. The reason for choosing this data to analyse this objective is that it is assumed that rejuvenation of the target population's interest towards the brand should take a more broad perspective into consideration. Therefore, not only the four items promoted in the campaign are included in the analysis, but also the the related products for the brand. 1995 was chosen as a line to divide the generation-Z population. The traffic and purchase from both male and female members are also considered, but not the male-only products. It is because the purchase of female products may not be only conducted by female but also their friends of other gender.
2. For the profitability question, a more strict approach was adopted. Only the 4 products directly promoted on Instagram were selected in the analysis. The objective here is to see if the transactions amount of the 4 products after the campaign are able to compensate the 30k euro of the marketing campaign cost. Assuming that there are no other costs other than 20% mark-up, there is around 7974 euro of profit. Therefore, the campaign is profitable. 

## Limitations

1. The rejuvenation effect can be more throughout if the data from digital marketing tools are provided. The flow audience CSV now only provides if the traffic is from mobile or desktop. However, the data from tracking links and affiliation links are not provided. If they are provided, a more direct relationship can be looked into and relevant metrics specific to digital marketing can be calculated, such as conversion rate. Other relationship like if new customer joining as new members from such links or from specific product pages can also be formed.
2. The period of the campaign effect is now limited to the data we have, which is only around 10 days. If data of longer period is provided, the delayed effect can be investigated. The effect period is also arbitrarily set the data available. Further literature may be looked into for the effect period of a Instagram marketing campaign. Perhaps more domain knowledge, such as from the experience of marketing expert in Decathlon can be consulted. 
3. Products from the similar category are not investigated. The campaign may have some sort of effect on those products as well. 
4. Other factors such as social factors, or other events that may have correlatively affected the sales/traffic figure are not considered, as I have little knowledge in the French sports celebrities/influencers circle.