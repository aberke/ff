# Food Futures

This repository contains the data and analysis code used in our project published via Appetite: 
"The negative impact of vegetarian and vegan labels: Results from randomized controlled experiments with US consumers".

All are free to reuse the methodology and data. Please cite appropriately.

> Berke, A., & Larson, K. (2023). The negative impact of vegetarian and vegan labels: Results from randomized controlled experiments with US consumers. Appetite. https://doi.org/10.1016/j.appet.2023.106767

### Abstract

Reducing consumption of animal products is a critically important challenge in efforts to mitigate the climate crisis. Despite this, meals containing animal products are often presented as the default versus more environmentally sustainable vegetarian or vegan options. We tested whether vegetarian and vegan labels on menu items negatively impact the likelihood of US consumers choosing these items by using a between-subjects experimental design, where participants chose a preference between two items. Menu items were presented with titles and descriptions typical at restaurants, and a random group saw "vegan" or "vegetarian" labels in the titles of one of the two items. Two field studies were conducted at a US academic institution, where people selected what to eat via event registration forms. The methodology was extended to an online study, where US consumers selected what to hypothetically eat in a series of choice questions. Overall, results showed the menu items were significantly less likely to be chosen when they were labeled, with much larger effects in the field studies, where choice was not hypothetical. In addition, the online study showed male participants had a significantly higher preference for options containing meat versus other participants. Results did not indicate the impact of labels differed by gender. Furthermore, this study did not find that vegetarians and vegans were more likely to choose items with meat when the labels were removed, indicating that removing labels did not negatively impact them. The results suggest removing vegetarian and vegan labels from menus could help guide US consumers towards reduced consumption of animal products.

Keywords: Diet; Behavior change; Choice architecture; Environment; Field experiment


## Data 

See `data/`

Data were collected from 2 main sources:
1. Field studies conducted through RSVP forms. See `ml-surveys/`.
The field studies were conducted through Google Forms and the data went to spreadsheets. The aggregated and deidentified dataset is provided and used in the analysis notebooks.

2. An online survey conducted through Qualtrics where participants were recruited via the Prolific platform.
Online survey data is preprocessed to remove identifying information (participant Prolific IDs). The resulting dataset is made openly accessible.

All data collection was approved via the MIT IRB.

The primary use of the data is to study the impact of vegetarian/vegan labels on food selection.

A secondary use of the data is to analyze the dietary habits and preferences of the surveyed population and estimate the average days/week the population eats vegetarian/vegan. This secondary analysis also makes use of census data from the ACS 5-year survey. This dataset is also provided in `data/`



## Data Analysis

For the main study analyses see

data-analysis/online-survey-v1-analysis.ipynb

and 

data-analysis/field-studies-analysis.ipynb

## Surveys

### Field studies

These were designed so that participants would be unaware that they were participating in the experiments. Event organizers sent out Google forms aas RSVP forms for their events. We conducted the experiment by creating the Google forms for the event organizers. We had to use Google forms to avoid suspicion, but Google forms do not support randomized controlled experiments like the ones we conducted. So we created our own mini infrastructure for randomized controlled experiments using Google forms.

See `ml-surveys/`

### Online study

A preview of the Qualtrics survey can be viewed via the following link: 
https://mit.co1.qualtrics.com/jfe/preview/previewId/6d475378-103a-4bc5-9c74-4827001c382a/SV_3agplznyD9Ga7BA?Q_CHL=preview 

A full copy of the survey questions is provided as supplementary material published via [Appetite](https://ars.els-cdn.com/content/image/1-s2.0-S0195666323017476-mmc2.pdf) or [here](https://drive.google.com/drive/folders/1ckIUdrPeypiFp3XG2tzdwDORWMhD9tpn).

