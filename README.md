# Hackathon_Projects
Check my Hackathon projects here..


# TVS Hiring Hackathon
My Solution to Hackathon

A Financial institution in India wants to leverage Machine Learning techniques to determine the client’s loan repayment abilities and take proactive steps to reduce the magnitude of exposure to default.
Goal: The goal of the problem is to predict whether a client will default on the vehicle loan payment or not, given the recent data of all the loan transactions. This can help the institution to distinguish the future applicants who might default. For each ID in the Test Dataset, you must predict the “Default” level
Note: Please answer the below descriptive question in the Jupyter Notebook Itself. This is going to carry more weightage in the final evaluation. This is an open-ended question and you are free to come up with a detailed explanation basis the analysis, model building exercise you have carried out.

## Data Description:

Features              Description
ID                    Id of the Applicant
Compensation          Income of the Applicant
Vehicle_Status        Whether the Applicant owns vehicle currently
Loan_amt              Loan Amount
Annuity_amt           Loan Annuity
density_Ind           Population density of the Applicant's residence
Job_Type              Sector of Job the Applicant belongs to
Default_hist          Whether any default history
Prop_List             No of Properties listed on Applicants Name
Home_Appliances       No of Home Appliances that Applicant owns
Region_Type           Category of the Region that Applicant belongs
Credit_Inq            History of credit enquiries happened on this particular Applicant
Education_det         Educational Qualification details of the Applicant
Marital_Stat          Marital Status of the Applicant
Gen                   Gender of the Applicant
Credit_Lnks           no.of credit links the Applicant possess
Experience            Experience of the Applicant
Income_Alt            Any Alternate income source for the Applicant
Day_Process           Application process day
Ph.No                 Has Applicant tagged his/her contact number
Type_Loan             Loan Category
Dependents            No .of Dependents of the client
Company_Rating        Rating of the Company in which the Applicant works
Region                Region to which the Applicant Belongs to
Age                   Age of the Applicant
hour_Process          Application Process hour
Addr_permanent        Whether the address has been verified
Permanent_Addr_tag    Whether the permanent address has been tagged in the application
c1_rated              Credit Score Normalized from Source 1
c2_rated              Credit Score Normalized from Source 2
Contact_age           Days prior the contact number has been changed from the date of Application
Product_bought        No.of Products purchased using Credit links
Default               Defaulted or Not Defaulted - 0-Not Defaulted, 1- Defaulted

## Evaluation Metric:
Submissions are evaluated on F1-Score between the predicted class and the observed target.

## Approach
I first cleaned the data set and made it ready for visualization. Further, I plotted various columns to check the behaviour of the dataset. After plotting the graphs, I used LabelEncoder to encode the categorical variables.Then I used Feature Scaling to rescale the dataset. Then I used Decision Tree Classifier to train the dataset. I also used Random Search CV to select best paramters of the model.

## F1 Score= 0.2698
