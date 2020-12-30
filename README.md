Given the definition of Financial Distress, while is certainly a well known parameter for companies, the challenge for you is to propose how you would go about building and model for Prediction of Financial Distress for Individuals, giving them a score and productising it via an API.
You don’t have to implement anything but requirements are as follows:

- Assuming you have access to banking data (transactions) and also from any other source: telco, personal data, etc. (including other digital platforms), identify features/parameters (not extensively but most important ones to consider) to be part of your proposed solution.
1. Financial Statement Data(Cash Flow Statement, balance sheet)
2. Credit Blacklist Data

- Which algorithm(s) would you propose.
Logistic regression and SVM, because it is classification problems
 
- How would you build and train your model.
1. Problem Definition
2. Prepare the data
3. Algorithm Evaluation
4. Divide Dataset (2/3 for Training and 1/3 for Testing)
4. Train Model using Dataset Training
5. Check the performance and find out for model improvement (tuning)
6. Test Model using Dataset Testing 
7. Finalize Model
8. Test Finalize Model using new data(Financially distress 1/0)

- How would you productise the predictive financial distress model in order to consume it and update it (real time) with more data.
Expose the API with input parameter their Financial Statement Data (We'll keep the data and can be used as train data in the future) and keep update the Credit Blacklist Data

- Which part is the most challenging? 
Understanding the domain knowledge in limited time and Data Preparation (Data Exploration, Cleaning and Selection)

- How do you think this is gonna impact people's lives? 
1. We can give insight to the people by providing models to be used widely and remind them about their financial status or give a warning for their expense once they input the data in application for example. 
2. We can give insight for any companies that would like to check their financial status
3. We can give insight for government when they would like to have sampling about citizens financial status 
