# <b>Project Three: Poverty in the Midwest </b><br />

<ins><b>Description</ins></b><br />
This project aimed to identify the predictor variables that most significantly impact the rate of homelessness. We employed methods such as exploratory data analysis and factor analysis to develop a structural equation model, uncovering the relationships between our predictors and response variables. Some of our variables are total Population, Bachelor's Degree or Higher, Veterans, Owner/Renter Occupied, In labor/Not in labor force, etc. 

<ins><b>Background</ins></b><br />
Our study focuses on 12 Midwest states: North Dakota, South Dakota, Nebraska, Kansas, Minnesota, Iowa, Missouri, Wisconsin, Illinois, Michigan, Indiana, and Ohio. Within these states, we included every county, totaling 1,056 counties. This comprehensive sample size provides a robust representation of the broader U.S. population.

<ins><b>Objectives</ins></b><br />
- To identify key predictor variables affecting the rate of homelessness.
- To understand the relationships between these predictors and homelessness rates.
- To analyze the statistical relationships between various demographic, economic, and social variables and the rate of homelessness.

<ins><b>Exploratory Data Analysis</ins></b><br />
Our exploratory data analysis observed that the covariability varied across different dimensions. Given our large sample size, we identified numerous outliers. However, after removing these outliers, we found that their absence did not significantly impact our correlation plot.

![pic1](EDApic1)
![pic2](EDApic2)

<ins><b>Exploratory Factor Analysis</ins></b><br />
In our analysis, we initially observed no complex dimensions in the data. Using orthogonal rotation, we identified that the relationship between home ownership and homelessness rates differed significantly. Specifically, owner-occupied housing showed a strong negative relationship with homelessness, while renter-occupied housing exhibited a strong positive relationship. However, when we applied oblique rotation, the relationships reversed: owner-occupied housing displayed a strong positive relationship with homelessness, and renter-occupied housing showed a strong negative relationship. For our study, we ultimately decided to use orthogonal rotation to maintain the clarity and interpretability of these relationships.

![pic3](EFApic1)
![pic4](EFApic2)

<ins><b>Path Diagram</ins></b><br />
Our path diagram revealed key relationships between housing occupants and socioeconomic factors. Specifically, renter-occupied housing was linked to the broader category of housing occupants, while the percentage of residents with a bachelor's degree was associated with occupation status. Among these factors, owner-occupied housing had the most significant effect on poverty rates, underscoring the critical role of home ownership in mitigating poverty.

![pic5](SEMpic1)

<ins><b>Structural Equation Model</ins></b><br />
- NFI & CFI: 0.509 < 0.95
- IFI: 0.510 < 0.95
- RMSEA: 0.567 > 0.08
- MFI: 0.001 < 0.95
- GFI: 1.000

Although it seems that our predictor variables would be able to successfully predict poverty, our structural equations model summarized that using our variables and data, we were not able to predict homelessness. Our measures of statistical data did not satisfy critical thresholds within various indices of our structural equations model such as the NFI, IFI, CFI, etc. which resulted in an unsuccessful study. Surprisingly enough, our Goodness-of-Fit Index is 1.00, indicating a successful capture of the covariance of our structure, but found no correlation within our predictors themselves.

![pic6](SEMpic2)

<ins><b>Conclusion</ins></b><br />
In conclusion, we found that our model is unable to predict poverty using the variables we selected. Because of this, further research can be conducted by adding more predictors to the dataset or using twelve different predictors that may be able to predict poverty.

<ins><b>Features</ins></b>
- Exploratory Data
- Factor Analysis 
- Structural Equation Modeling

<ins><b>Technologies Used</ins></b>

- Microsoft Excel
- R & RStudio

[Click here](https://github.com/Geremyycx/Signature-Work-Portfolio.git) to return to the main portfolio page.
