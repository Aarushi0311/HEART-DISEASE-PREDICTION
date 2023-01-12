# HEART-DISEASE-PREDICTION
# Abstract
    Day by day the cases of heart disease are increasing at a rapid rate and it's very important and concerning 
    to predict any such diseases beforehand. This diagnosis is a difficult task i.e. it should be performed 
    precisely and efficiently. The project mainly focuses on which patient is more likely to have a heart disease 
    based on various medical attributes. We prepared a heart disease prediction system to predict whether the 
    patient is likely to be diagnosed with heart disease or not using the medical history of the patient. I have used 
    algorithms of machine learning such as logistic regression to predict and classify the patient with heart 
    disease. 
    
 # Requirement Analysis
    1) Language: Python 3.7
    2) Data Set: Kaggle(https://www.kaggle.com/)
    3) Code Editor: Jupyter Notebook
    4) Image processing libraries
        • Numpy
        • Pandas
        • Scikit-learn
        • Matplotlib
        • Seabor
 # Implementation
1) DATA ACQUISITION:
    The cardiac disease dataset was obtained from the Kaggle website. It contains 14 features and 294 
    records.
    Attribute Information:-
    SNO.        ATTRIBUTE NAME                  INFORMATION
    1.              Age                   Age of the person in years
    2.              Sex                   Gender of the Person(1 = Male; 0 = Female)
    3.              cp                    Chest Pain Type
    4.            trestbps                Resting blood pressure
    5.             chol                   Serum cholesterol
    6.              fbs                   Fasting blood sugar > 120 mg/dl(1 = True; 0 = False)
    7.            restecg                 Resting electrocardiographic results
    8.            thalach                 Maximum heart rate achieved
    9.             exang                  Exercise induced angina
    10.           oldpeak                 ST depression induced by exercise relative to rest
    11.            slope                  The slope of the peak exercise ST segment
    12.             ca                    Number of major vessels (0-3) colored by fluoroscopy
    13.           thal                    0 = normal; 1 = fixed defect; 2 = reversible defect
    14.          target                   1 = Heart Disease 0 = Healthy Heart 
  2) DATA PRE-PROCESSING
      Data preprocessing can refer to the manipulation or dropping of data before it is used in order to ensure 
      or enhance performance, and is an important step in the data mining process.
  3) FEATURE SELECTION
      It includes splitting of data into two parts: Training data and Test data. The accuracy of 82% obtained by 
      logistical regression for a split ratio of training and testing is 90:10.
  4) LOGISTIC REGRESSION
      In logistic regression, the goal is to calculate the values of the coefficients within every input variable.
  5) RESULT
      If our prediction is equal to 0, then the person does not have any heart disease and is healthy,
      Whereas if the prediction is not equal to 0, the person has heart disease.
