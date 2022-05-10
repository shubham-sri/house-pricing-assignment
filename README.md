# House Selling Price
> Here buisness requrement to get model which explain which variable is important for calulating selling price of any property so that bussines person can make some conclusions


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- Project have dataset consist of numeical and categorical data, where we need to build a model which is less complex and also not overfitted on data
- Outcome of this project is to comeup with a model which have best fitting over on training and testing data. Model is able to predict  price of house based on diffent params like area, type, etc... 
- Build two model Ridge and Lasso with Grid CV Seraching for getting optimal hyperpamamters

## Conclusions
- For ridge model found 80 as optimal params which provide solution with 89% R2 score on train and 87% on test data.
- For lasso model found 0.0001 as optimal params which provide solution with 89% R2 score on train data and 88% on test data.



## Technologies Used
- matplotlib - 3.3.1
- seaborn - 0.11.0
- sklearn -  0.23.1
- numpy - 1.22.2
- pandas - 1.1.4

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@shubham-sri](https://github.com/shubham-sri) - feel free to contact me!


## License
This project is open source and available under the [... License](./LICENSE).