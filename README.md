Given the definition of Financial Distress, while is certainly a well known parameter for companies, the challenge for you is to propose how you would go about building and model for Prediction of Financial Distress for Individuals, giving them a score and productising it via an API.
You don’t have to implement anything but requirements are as follows:

1. Assuming you have access to banking data (transactions) and also from any other source: telco, personal data, etc. (including other digital platforms), identify features/parameters (not extensively but most important ones to consider) to be part of your proposed solution.
- Financial Statement Data(Cash Flow Statement, balance sheet)
- Credit Blacklist Data

2. Which algorithm(s) would you propose.
- Logistic regression 
- SVM
 
3. How would you build and train your model.
- Problem Definition
- Prepare the data
- Algorithm Evaluation
- Divide Dataset (2/3 for Training and 1/3 for Testing)
- Train Model using Dataset Training
- Check the performance and find out for model improvement (tuning)
- Test Model using Dataset Testing 
- Finalize Model
- Test Finalize Model using new data(Financially distress 1/0)

4. How would you productise the predictive financial distress model in order to consume it and update it (real time) with more data.
- Expose the API with input parameter their Financial Statement Data (We'll keep the data and can be used as train data in the future) 
- Update the Credit Blacklist Data

5. Which part is the most challenging? 
- Understanding the domain knowledge in limited time 
- Data Preparation (Data Exploration, Cleaning and Selection)

6. How do you think this is gonna impact people's lives? 
- We can give insight to the people by providing models to be used widely and remind them about their financial status or give a warning for their expense once they input the data in application for example. 
- We can give insight for any companies that would like to check their financial status
- We can give insight for government when they would like to have sampling about citizens financial status 


Proposed Stack for this assignment : 
- Python : Have many libraries and open source sample 
- Jupyter Notebook or PyCharm (IDE for Python Script/Apps/Model Development)
- MySQL/PostgreSQL/MongoDB : Saving Data for Archive and Future Needed (Training, Test and New Data)
