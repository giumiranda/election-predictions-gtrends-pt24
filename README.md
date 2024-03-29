# Predicting Election Outcome Using Google Trends Data

This project aims to explore whether Google Trends data can be used to forecast the outcomes of elections in Portugal. We analyze the search interest trends for various political parties leading up to the elections and build predictive models using ARIMA (AutoRegressive Integrated Moving Average) to forecast the electoral performance of each party.

## Data Collection and Preprocessing

We collect Google Trends data for major political parties in Portugal, including PS (Partido Socialista), AD (Aliança Democrática), Chega, Iniciativa Liberal, and Bloco de Esquerda. The data is processed to calculate the relative search interest for each party over a period of 30 days preceding the election date.

## Exploratory Data Analysis

We visualize the seasonal trends of each party using seasonal decomposition analysis to identify any underlying patterns or trends in the search interest data.


## ARIMA Modeling

We employ the AutoARIMA algorithm to automatically select the best parameters for the ARIMA models for each political party. These models are trained on the historical search interest data to predict the electoral outcome for each party.

## Model Evaluation

We evaluate the performance of the ARIMA models by comparing the predicted election results with the actual election outcomes. 

The discrepancies between the predicted and actual results are analyzed to identify potential factors influencing the search trends and model predictions.

## Conclusion

The ARIMA models provide insights into the relationship between Google search interest and election outcomes. However, our analysis reveals that the models tend to overestimate the votes for certain parties, such as Chega and Iniciativa Liberal. Possible explanations for these discrepancies include demographic factors, party characteristics, and external factors affecting search trends.

Further research is needed to refine the models and explore additional variables that may influence search interest and electoral outcomes. Despite the limitations, this study highlights the potential of using Google Trends data as a supplementary tool for election prediction and political analysis in Portugal.
