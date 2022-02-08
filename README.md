# Project Name
> The project problem statement is to understand the factors affecting the demand for the rental bikes and gauge by how much are these factors describe the demand


## Table of Contents
* [General Info]
* [Technologies Used]
* [Conclusions]
* [Acknowledgements]
* [Subjective Questions on Linear Regression]

## General Information
- BoomBikes is a US Based bike sharing company that wants to identify and determine the factors that affect demand for their bikes based on several independent variables they have collected.They could salvage this to manipulate their business strategy to meet the demand levels. The data set contains 2 years information on the number of bikes rented on a day along with additional parameters that the business have identified as potential drivers for the demand.

## Conclusions
- <b> Conclusions from EDA </b>
    - The average demand for BoomBikes have increased from 2018 to 2019.
    - There is a clear influence of weather, season, and days of week on the demand of bikes.
- <b> Conclusions from Linear Regression Model </b>
    - There is a significant influence of parameters temperature, weather condition, seasonality, windspeed on the demand for bike.
    - Additionaly there is also some slight influence of the months of the year, whether the day is holiday or not on the demand
- <b> Evaluation Metrics </b>
    - R2 Score on Test Data Set :0.7792
    - Adjusted R2 Score on Train Data Set : 0.809

## Technologies Used
- pandas - version 1.2.4
- seaborn - version 0.11.1
- statsmodels - version 0.12.2
- scikit learn - version 0.24.1

## Acknowledgements
- Dataset Acknowledgement
- [1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

- @article{
	year={2013},
	issn={2192-6352},
	journal={Progress in Artificial Intelligence},
	doi={10.1007/s13748-013-0040-3},
	title={Event labeling combining ensemble detectors and background knowledge},
	url={http://dx.doi.org/10.1007/s13748-013-0040-3},
	publisher={Springer Berlin Heidelberg},
	keywords={Event labeling; Event detection; Ensemble learning; Background knowledge},
	author={Fanaee-T, Hadi and Gama, Joao},
	pages={1-15}

- This project was based on the linear regression assignment from Upgrad ML/AI Course

## Subjective Questions
- Contains a PDF Solution to some subjective questions on the case study and in general about linear regression.

## Contact
Created by [@Bala129] - feel free to contact me!
