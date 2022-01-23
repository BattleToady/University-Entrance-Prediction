# University-Entrance-Prediction
My first pet- and diploma-project.

Idea: create model to predict entrant will can enter to university or not.
What I did: created parsing program in Python with using regular expressions and request library from open-data site abit-poisk(unfortunately I lost it)
than I looked a little on data and made more columns(like mean mark for every specialty and university, mark for free places etc.)
Tried a lot of models(from sklearn)
Made pipeline and widgets for prediction(how it can be implemented into product), calibrated model.

Files:
Preprocess_YYYY_year.ipynb - preprocess for each year dataset, I had 2017-2021 including.
Preprocess_for_first.ipynb - union of previous datasets and making a little preprocessing more
StatisticalHypoteses.ipynb - I check 2017-2021 data I checked they had a same distibution or different ones, and some other looking and stat testing data.
CheckModels.ipynb - I tried a lot of models, RFE, GridSearchCV and other ways to improve them.
Prototype.ipynb - I made dataset with data about each specilty in each university, what I needed for prediction. Also I added widgets, pipeline and tried calibrate model.
