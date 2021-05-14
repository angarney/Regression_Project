# Regression_project

Alexandra Garney

### Abstract
---
Home ownership can be a way to build wealth through real estate and increase generational wealth. Property taxes are not always fairly levied within communities. In 2013, Philadelphia, PA created the [Actual Value Initiaitive](https://www.pewtrusts.org/~/media/assets/2015/09/philadelphia-avi-update-brief.pdf) to overhaul property taxes and create assessed property values that more closely align with sales prices. Fair housing advocates have been skeptical of the plan's success. The goal of this project was to create a regression model to better understand/interpret any potential differences in residents of Philadelphia's assessed property values compared with the sales prices of their properties. 

### Data
---
* [Philadelphia Office of Property Assessment](https://www.opendataphilly.org/dataset/opa-property-assessments/resource/ca89fcd7-9fa4-4b9b-983d-e48e56eca17f?inner_span=True) - sales price, tax assessed value, home features
* [Walkscore.com](https://www.walkscore.com/) - zip code walkscores
* [Ziprealty.com](https://www.ziprealty.com/) - zip code highest grade school score
* [City-data.com](https://www.city-data.com/zipmaps/Philadelphia-Pennsylvania.html) - demographics, unemployment rates, land usage by zip code
* [Wikipedia](https://en.wikipedia.org/wiki/Wiki) - Philadelphia neighborhoods and correspond zip codes

### Algorithms
---
* _Linear Regression with feature engineering including a polynomial feature_
* _K-folds Cross Validation_

### Results
---
50% of the variance in property tax value to sales price % was explained by the model within an Absolute Mean Error of 69.7%.
Features included in the final model with high impact were house sales price ranges and neighborhoods. 

### Tools
---
* Pandas
* Numpy
* Scikit-learn
* Matplotlib
* Seaborn
* BeautifulSoup
* Linear Regression
* K-fold Cross Valiation

### Communication
---
A [slide presentation](https://github.com/angarney/Regression_project/blob/main/philly_property_taxes_051421.pdf) was created.