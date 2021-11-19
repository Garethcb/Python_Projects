# Python_Projects
The principal driver behind our analysis is to answer the question, “can we predict car sales prices by training a model to determine the dominant features driving sales prices.” This task required the use, selection, and evaluation of four separate prediction models with the best performer, in terms of achieving the lowest RMSE, acting as our final model.
___
This analysis required the use, selection, and evaluation of four separate prediction models trained on web-scraped car sales data that required numerous data preparation steps. The transformation of our data set into a state, structure, and format that our machine learning algorithms could parse entailed both data pre-processing (removing outliers, missing values, etc.) and feature selection through statistical testing. Finally, machine learning pipelines allowed us to fit the data to our models. Despite evidence of slight overfitting on the training sets, all models outperformed our mean baseline benchmark. Notably, XGBoost is the best performer in terms of achieving the lowest RMSE on our testing data. Importantly, age, unleaded fuel, and hatchback body type are our three most important features in deriving price predictions.
___
**Techniques Included:**

-	Web scraping (BeautifulSoup)

-	Modelling (sklearn)

-	Train-Test splits and Cross validation

-	Hyper-parameter Tunning

-	Model performance evaluation

