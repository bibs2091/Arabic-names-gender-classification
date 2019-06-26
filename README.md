# Arabic-names-gender-classification
Arabic names gender classification with Maching learning using python.

I used in this project a dataset contain +6000 name labled with gender (either male or female) you can check it [here](https://github.com/Eslam2014/arabic_names_with_gender)

I used Random Forest Classifier, the model treats only names longer than or equal to 2 characters 


the features I used are:
* the last letter of the name
* the second last letter of the name
* the third last letter of the name (in case of len(name)==2 the third last character will be "-")
* boolean indicator of whether the name contains ابو
* boolean indicator of whether the name contains عبد 
