# SC1015 Mini Project

## Group Members
#### Group 10: Sum Yuan Sen, Dominic Tay, Dhairya

## About

The *English Premier League* is the most-watched sports league in the world and is contested by 20 clubs which operates on a system of promotion and relegations. 
As football evolves in the modern era where teams spent huge amount of money on player transfers, sponsorships etc. , it is clear that the stakes are high and teams are desperate to win.

Thus, this project aims to make use of the abundance of data that is ever present to us in today’s technology-driven world to generate meaningful insights for teams to adopt. 


## Objective

To investigate factors that will maximise goals scored for a football team in the *English Premier League*, using data from past 5 seasons of the *EPL (17/18 to 21/22)*

## Models Used

 * Decision Tree Classifier (Baseline)
 * K-Nearest Neighbors Classifier
 * Random Forest Classifier

## Conclusions


* The variables "HS" - Home Shots and "HST" - Home Shots on Target have a high correlation to "FTHG" - Full-Time Home Goals.
* Hyperparameter tuning of random forest takes a long time due to the high number parameters in random forest and the different range of values for each parameter.
* Tuning the parameter of the model does not improve the model by a big amount, however it is still a small step towards a higher accuracy.
* Though "HS" and "HST" might be useful in getting more goals, other outside factors still needs to be considered such as player abilities and performance. 

## Lessons learnt

* Hands-on approach on working with new datasets
* How to use different models for better trainings and predictions



## Files and folder descriptions
* **Codes**: A Jupyter Notebook **(.ipynb file)** containing the main source code for the project.
* **Datasets**: The English Premier League yearly datasets **(.csv files)** that is used in the project.
* **Presentation Slides**: Our group's powerpoint slides **(.pdf file)** for the project. *If it shows "Unable to render rich display", refresh the webpage a few times.*

## Contributions

* **Dhairya** : Introduction, Data Preparation & Cleaning, Slides, Presentation Video
* **Dominic** : Data Preprocessing and Visualization, Slides, Presentation Video
* **Yuan Sen** : Model Training and Hyperparameter Tuning, Slides, Presentation Video

## References
* 1.6. nearest neighbors. scikit. (n.d.). Retrieved April 22, 2023, from https://scikit-learn.org/stable/modules/neighbors.html#classification
* Sklearn.ensemble.randomforestclassifier. scikit. (n.d.). Retrieved April 22, 2023, from https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html
* English Premier League Dataset. Saif. (2022) Retrieved March 2, 2023, from  https://www.kaggle.com/datasets/saife245/english-premier-league
* Create a Python Heatmap with Seaborn. Holland. (2018). Retrieved March 2, 2023, from https://absentdata.com/python-graphs/create-a-heat-map-with-seaborn/
* Python BoxPlot Jupyter Notebook. Lowther. (2019). Retrieved March 19, 2023, from https://www.wafermovement.com/2019/08/pythonboxplotnotebook/
* Making Plots in Jupyter Notebook Beautiful & More. Bipin. (2020). Retrieved March 19, 2023, from https://towardsdatascience.com/making-plots-in-jupyter-notebook-beautiful-more-meaningful-23c8a35c0d5d
* scikit learn. scikit-learn-developers. (2007). Retrieved March 2, 2023 from https://scikit-learn.org/stable/about.html#citing-scikit-learn

