# Factors that are considered for prediction of Unemployment Rates for each country:-
For the prediction of unemployment rates for the G7 countries several factors have been taken into consideration for all these countries that can affect the overall unemployment. The data on all these factors are extracted at the monthly level from the official websites or the given third-party websites and other reliable sources. These factors are summarized below:

### Population figures: 
Working-age population, Labour force, Unemployment level of males, females & overall, Part-time & full-time employment numbers.

### Rates & proportions: 
Employment rates, Inactivity rates/Labour Force Participation rates.

### Economic factors: 
Consumer Price Index (CPI)/ Producer Price Index (PPI)/ Gross Domestic Product (GDP)/ Monthly Inflation rates of any of these factors etc.

### Other factors: 
Average working hours, Wages of labourers, Total new job vacancies, Monthly labour costs, energy costs, other derived variables etc.


# Methodologies & Workflow:-

Importing dataset - Preparing the dataset (Feature Scaling - Eliminating the variables for which there is high multicollinearity in the data, creating new derived variable) - Train-Test split - EDA (Time series plot, ACF, PACF plot) - Fitting suitable ARIMAX model on the train dataset - Choosing final model based on significance of regressors & coeffcients - Validating it on Test dataset - Using this model to forecast Unemployment Rates of future months.
