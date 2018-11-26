# Task
You assume the role of a data analyst at MedBank. A cooperative bank specializing in the healthcare market.

You have just received your new project and the associated dataset unknown to you.

Their task is to create the best possible forecasting model for a marketing campaign for a new product "MedTrust" and to predict the completion probabilities.

Analyze the training data set for this purpose.

First carry out an exploratory analysis : For which of the explanatory variables are correlations to the target variable observed? Which ones are technically meaningful?

Make a selection of explanatory variables and then create various predictive models (logistic regression, decision trees, and random forests).

Create different models with different parameters for each procedure . Proceed as systematically as possible so that you can later describe the performance of the model (= AUC) as a function of the parameters.

Apply this model to forecast the test data.

#Evaluation and further process
You can ignore the generated leaderboard in kaggle. It is not the pure result (AUC) that counts, but especially the steps and decisions until then.

We will discuss the results together in a one-hour video / phone call . For this reason, please send me your preferred periods and your preferred medium by submitting the results.

In this appointment, we then discuss the further joint application process. The next step after the video / telephone would be a personal get-together in the apoBank.

Submission format
Please use the default solution template file to upload your results.

The first column contains the sequence numbers from the test data record with the variable name "ID".

The second column contains the corresponding completion probabilities in the format [0, 1] with the variable name "Expected".

Example of the second line: 432176974, 0.098767853.

# Data Source
The dataset is the result of a MedBank call center marketing campaign for the MedTrust product.

The data is purely fictitious "dummy data set" , which has nothing to do with apoBank's real customers.

The data are largely cleansed.

You can use all the variables for your modeling, but you do not have to. It is up to you to change or combine variables.

Please document all decisions and changes.

# files
The file TrainData receives the training data set for the challenge.

The file TestData receives the test data for the challenge. In this file, the Variable target variable is not filled.

The solution template file is the default pattern for submitting the solution (see Submission Format)

# variables
Master number: Internal customer identification number in the bank system

Target Variable: Customer completed the product in the campaign

Day: Call day of the call center agent

Month: month of call of the call center agent

Duration: duration of the call

Call ID: Internal call identification number

Age: age of the customer

Gender: Customer's gender

Type of employment: type of employment of the customer

Marital status: Marital status of the customer

Credit Failure: Customer has a defaulted loan in the bank

Account balance: Current account balance of the customer in his checking account

House: Customer has property

Credit: Customer has a loan in the bank

Contact type: In this way the customer was contacted

Number of speeches: The number of times the customer was addressed has already been addressed in this campaign

Days since last campaign: so many days ago, the customer was addressed in the campaign

Number of contacts last campaign: The number of times the customer was approached during the last campaign

Result last campaign: result of last campaign
