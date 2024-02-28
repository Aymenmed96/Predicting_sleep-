#Totalsleep-Dreaming-Prediction-for-Mammals

This project aims to use machine learning techniques to predict two aspects of mammalian sleep: the total amount of sleep and the amount of dreaming (or REM) sleep. We use a dataset that contains 16 features for 83 mammal species, grouped into four categories: general, biological, ecological, and sleep features. The dataset is relatively small, which is a common challenge in biological data analysis.

Installation

To run this project locally, you need to install the following dependencies:

To predict dreaming time, run: pip install -r requirements-dreaming_prediction.txt
To predict total sleep time, run: pip install -r requirements-totalsleep-prediction.txt
To see the correlation between biological and ecological features, run: pip install -r requirements-correlation-biological-ecological-attributes.txt

Data Sources
The data used in this project comes from two sources:

Famille_Taxonomie.xlsx: This file contains the taxonomic classification of the mammal species.
sleep_merged.tsv: This file contains the sleep features and other biological and ecological features of the mammal species. It is a merge of two studies on sleep duration in mammals:
Allison T, Cicchetti DV. Sleep in mammals: ecological and constitutional correlates. Science. 1976 Nov 12;194(4266):732-4. doi: 10.1126/science.982039. PMID: 982039.
Savage VM, West GB. A quantitative, theoretical framework for understanding mammalian sleep. Proc Natl Acad Sci U S A. 2007 Jan 16;104(3):1051-6. doi: 10.1073/pnas.0610080104. Epub 2007 Jan 10. PMID: 17215372; PMCID: PMC1783362.

Project Structure
The project consists of three parts:

Part 1: Predicting total sleep time. In this part, we perform exploratory data analysis, select and compare different machine learning models, and interpret the results.
Part 2: Predicting dreaming time. In this part, we follow the same steps as in part 1, but for a different target variable.
Part 3: Exploring the relationship between biological and ecological features. In this part, we use correlation analysis and visualization to examine how different features are related to each other.
