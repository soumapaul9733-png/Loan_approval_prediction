📊 Dataset Features

The dataset contains information about loan applicants and whether their loan was approved.

Loan_ID: A unique ID assigned to each loan application.

Gender: Applicant's gender (Male/Female, encoded as 1/0).

Married: Marital status of the applicant (Yes/No, encoded as 1/0).

Dependents: Number of dependents, converted into numerical values.

Education: Education level (Graduate/Not Graduate, encoded as 1/0).

Self_Employed: Whether the applicant is self-employed (Yes/No, encoded as 1/0).

ApplicantIncome: Income of the primary applicant.

CoapplicantIncome: Income of the co-applicant.

LoanAmount: Requested loan amount, represented in thousands.

Loan_Amount_Term: Loan repayment period in months.

Credit_History: Indicates whether the applicant meets the required credit-history guidelines.

Property_Area: Location of the property (Urban/Semiurban/Rural, encoded as 2/1/0).

Loan_Status: Indicates whether the loan was approved (Y/N, encoded as 1/0). This is the target variable.

🔄 Project Workflow

The project follows a simple machine-learning pipeline:

Data Preprocessing
Load the dataset, handle missing values, convert categorical features into numerical values, and prepare the data for model training.

Exploratory Data Analysis (EDA)
Explore the dataset through visualizations to understand how different features, such as education and marital status, relate to loan approval.

Model Development
Split the dataset into training and testing sets and train a Support Vector Machine (SVM) Classifier to predict loan approval.

Model Evaluation
Evaluate the trained model using accuracy. The model achieved approximately 79.8% training accuracy and 83.3% test accuracy.

Prediction
Test the trained model with new, unseen applicant information and generate loan approval predictions.

🛠️ Requirements & Usage

The project uses the following Python libraries:

numpy

pandas

seaborn

scikit-learn

To run the project, open the notebook in Google Colab or a local Jupyter environment and execute the cells sequentially. The notebook will handle preprocessing, visualization, model training, evaluation, and predictions.
