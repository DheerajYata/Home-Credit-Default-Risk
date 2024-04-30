# Home-Credit-Default-Risk

## Business Problem and Project Objective
Home Credit is a global non-banking financial institution committed to facilitating the financial inclusion of individuals with little to no credit history. The core challenge is predicting the loan repayment abilities of these individuals accurately. Our project leveraged historical loan application data to predict default risks, aiming to empower Home Credit with data-driven insights for making safer lending decisions.

## Solution Implemented
Our project employed several advanced machine learning models to predict loan repayment difficulties, enhancing decision-making for loan approvals:

**Logistic Regression**: Established a baseline for comparison, with an AUC of 0.737. 

**Random Forest**: Improved accuracy over the baseline with an AUC of 0.738 and a Kaggle score of 0.63, highlighting its efficiency in capturing complex patterns in data.

**Tuned Random Forest**: Further refinement of the Random Forest model for optimal performance.

**Light GBM (LGBM)**: Delivered the best performance with a Kaggle score of 0.63 and an AUC of 0.76, leveraging its capability of handling large volumes of data with speed and accuracy.
These models were crucial in developing a robust framework for assessing credit risk more accurately.

## Personal Contributions
My specific contributions to the project included a wide range of tasks that covered both the development and the refinement stages of our predictive models:

**Data Preparation**: Managed the initial stages of data cleaning, normalization, and transformation to ensure high-quality inputs for modeling.

**Feature Engineering**: Developed key features that significantly enhanced model accuracy, including but not limited to AGE_YEARS, CREDIT_TERM, INCOME_CREDIT_RATIO, and ANNUITY_INCOME_PERCENT.

**Model Development**: Built and refined multiple predictive models:

**Logistic Regression Model**: Implemented the baseline model and conducted initial evaluations.

**Random Forest and Tuned Random Forest Models**is : Developed and optimized these models to improve predictive performance.

**Test Set Preparation and Model Predictions**: Carefully prepared the test datasets to accurately simulate real-world application during the prediction phase.

**Final Predictions**: Generated the final model outputs, ensuring they were ready for evaluation and deployment.

**ROC-AUC Curves**: Created visualizations to illustrate model performance and facilitate easier interpretation of results.

**Notebook Editing**: Ensured that all notebooks were well-documented, clear, and reproducible, making the project accessible for review and future use.

## Business Value Delivered

The predictive modeling framework provides substantial value to Home Credit by:

**Improving Loan Approval Decisions**: By utilizing predictive analytics, Home Credit can make informed decisions, reducing financial risks associated with bad loans.

**Enhancing Operational Efficiency**: Automation of loan approvals expedites the processing time, enhancing customer experience.

**Developing Tailored Financial Products**: Using insights from our models, Home Credit can offer customized loan products to different segments, improving service and competitiveness.

## Challenges Encountered

Key challenges included managing large datasets with missing values and high dimensionality, requiring sophisticated imputation strategies and robust computational resources. Additionally, feature selection and ensuring model generalization across different data scenarios added layers of complexity to our project.

## Learning Outcomes
This project deepened my expertise in several areas:

**Machine Learning Proficiency**: Advanced my understanding of ensemble methods and gradient boosting techniques.

**Data Handling Skills**: Enhanced my ability to preprocess and engineer features from complex datasets effectively.

**Strategic Business Thinking**: Improved my skills in translating technical findings into actionable business strategies.


## Presentation Link 
[Presentation Link](https://github.com/DheerajYata/Home-Credit-Default-Risk/blob/1ce05bdddae2e87daf86ec579916764dcde2df86/Capstone%20Presentation%20Group%206%20(1).pptx)

## Project File 
[Project File]()
