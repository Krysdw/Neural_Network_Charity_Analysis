# Neural_Network_Charity_Analysis

Overview
This purpose of this analysis is to predict whether applicants will be successful if backed by the Alphabet Soup Co. Thus, proving to be a good investment for the Alphabet Soup Company. 
To conduct the following analysis, data manipulation; the creation of training and testing sets will be instituted to better analyze the models for prediction. 
Results
•	Data Processing
o	To clean the data, I removed the EIN and NAME columns since they have no value to the model.
o	The variables considered for the following model are: 
-	'STATUS', 
-	'ASK_AMT
-	'IS_SUCCESSFUL', 
-	'APPLICATION_TYPE', 
-	'CLASSIFICATION', 
-	'USE_CASE', 
-	'ORGANIZATION', 
-	'INCOME_AMT'. 
-	"USE_CASE_Other" & "AFFILIATION_Other" columns were dropped
•	Compiling, Training, and Evaluating the Model Attempt #1
o	2 Hidden Layers
-	8 neurons (Layer1), 
-	5 neurons (Layer2)
o	Used Relu and Sigmoid Activations Functions since sigmoid is best for binary classification problems as this and Relu is for nonlinear datasets.
Testing Attempts
Attempt: 2
•	3 Hidden Layers
-	80 neurons
-	30 neurons
-	15 neurons
Relu/Sigmoid Functions used: Best for binary classification and non linear datasets
804/804 [==============================] - 3s 4ms/step - loss: 0.5513 - accuracy: 0.7315

Attempt: 3
•	3 Hidden Layers
-	80 neurons – Layer 1
-	35 neurons – Layer 2
-	10 neurons – Layer 3
•	Used Relu and Sigmoid Activations Functions: best for binary classification and Relu is for nonlinear datasets.
268/268 - 1s - loss: 0.5918 - accuracy: 0.7355 - 1s/epoch - 4ms/step
Loss:0.5917807221412659, Accuracy: 0.7355102300643921

Attempt: 4
•	3 Hidden Layers
-	80 neurons – Layer 1
-	30 neurons – Layer 2
-	15 neurons – Layer 3
•	Reordered Relu and Sigmoid Activations
215/215 - 1s - loss: 0.5530 - accuracy: 0.7276 - 696ms/epoch - 3ms/step
Loss:0.5529584884643555, Accuracy: 0.7275510430335999

The best accuracy rate for all tested models is noted at .73, but with small improvements in each test. 
Summary
The average accuracy rate for all models was 73%, with notable improvements for each test.  Perhaps an improvement of features would create a better testing environment. For instance: what is the measurement of success and what leads to success? How many of these features tend to be present for those that are successful. A more in-depth study, based on the accuracy rate that was drawn from the current study is recommended.

