Explain the purpose of the analysis:
	Underline the potential impact of this analysis, which aims to create a model that can accurately distinguish between healthy and high-risk loan applicants based on the creditworthiness of potential borrowers from peer-to-peer lending services. This could significantly influence the peer-to-peer lending industry.

Explain what financial information the data was on and what you needed to predict:
	The financial information was on a dataset of historical lending activity from a peer-to-peer lending services company.  I needed the testing feature data and fitted model to make the predictions.

Describe the stages of the machine learning process you went through as part of this analysis:
	The processes I used included but were not limited to, collecting the data, analyzing it by cleaning it, selecting a model, and evaluating it.

Briefly touch on any methods you used (e.g., `Logistic Regression`, or any other algorithms):
	I used logistic regression, so I imported the logistic regression model from SkLearn using the training data X_train and y_train.

In summary, both machine learning models perform equally depending on the specific problem you’re trying to solve. Machine learning models present better techniques for predicting bank creditworthiness than the traditional static modeling approach. Using original data, the first Logistic Regression model does very well at predicting 'healthy loans' with accuracy, precision, and recall close to 100%. It still does well but performs noticeably worse at identifying high-risk loans, where it has a precision of 85% and a recall of 91%.
I think it's more important to predict ‘0’s, which are low-risk clients. As a bank, you want low-risk clients when distributing loans to avoid default.
