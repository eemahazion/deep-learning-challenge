# Analysis for Deep Learning
Alphabet Soup Neural Network Model

•	Overview: The purpose of this analysis is to help the nonprofit foundation, Alphabet Soup, build a Neural Network model to seek out applicants that will most likely succeed with funding.

•	Results:
o	Data Preprocessing
	The target variable for our model as seen in the dataframe is “IS_SUCCESFUL”, a field indicating whether the applicant that was funded was successful or not.
 ![image](https://github.com/eemahazion/deep-learning-challenge/assets/124013416/bf2c3100-da2d-45de-8ade-85e5e0c97ebf)

	The feature variables includes a long list, but to name a few as seen above: “USE_CASE”, “INCOME_AMT”, “ASK_AMT” etc.
	2 variables that were removed while processing were useless for the model. They included “EIN” and “NAME” as these were just unique identifiers essentially, and were not attributes.

o	Compiling, Training and Evaluation the Model
	The neural network model had 3 dense layers, with 2 activation functions (relu and sigmoid). This was a good amount for the amount of data and accuracy optimizing.
	I was not able to achieve the 75% accuracy target score for the machine learning model.
 ![image](https://github.com/eemahazion/deep-learning-challenge/assets/124013416/bc93bc27-02c0-4189-b59a-8eb0a9aed2b1)

	Ways to increase model performance could be getting rid of more irrelevant data, changing the number of epochs or hidden layers as well. Possibly even changing the activation functions.


•	Summary: 
o	This model is not the most accurate at 73%. This would not be a good enough tool to turn down potential applicants. There could be other models I haven’t explored yet, that could better tune out categorical data. 

o	Another way to fix the root problem is to get better data. Possibly source better, more relevant information from the applicants. Some metric data would be much better, similar to what they already have in “INCOME_AMT” and “ASK_AMT”.

o	 Another way to get better data is to deconstruct the bins for “INCOME_AMT”, as the more granular we get with this data, it would be invaluable. Binning the profit/income of organizations, gives you less insightful data, as you can see in picture below we have only 9 bins for income. Profit is a huge factor of success and is better served granular.
 ![image](https://github.com/eemahazion/deep-learning-challenge/assets/124013416/c6ae3ce5-f72e-445c-bd89-d800a803886f)


