# Cardiovascular Risk Prediction 

### <b>Description:</b>
This is a supervised (classification) machine learning capstone project on Cardiovascular risk prediction, given by [Alma Better](https://www.almabetter.com/). 

![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)

### <b>Problem statement:</b>
Cardiovascular diseases (CVDs) are the leading cause of death globally, taking an estimated 18.6 million lives each year, which accounts for 33% of all the global deaths. CVDs are a group of disorders of the heart and blood vessels and include coronary heart disease, cerebrovascular disease, rheumatic heart disease and other conditions. More than four out of five CVD deaths are due to heart attacks and strokes, and one third of these deaths occur prematurely in people under 70 years of age.

It is important to detect cardiovascular disease as early as possible so that management with counselling and medicines can begin.

Our main aim here is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD).

![pic2](https://user-images.githubusercontent.com/85065799/202833341-89899418-1a91-4113-93f2-f4658ab4be6e.jpg)

![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)

#### <b>Note:</b> Dataset is provided by the company, Alma Better.

### <b>Dataset description:</b> 
The problem and aim stated above can be solved with the help of machine learning models and the data that we have. The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes.

#### <b>Variables:</b>
Each attribute is a potential risk factor. These attributes include demographic, behavioral, and medical risk factors.

#### <b>Defining the columns:</b>
<b>Demographic:</b>

  • Sex: male or female("M" or "F")

  • Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)
  
<b>Behavioral:</b>

  • is_smoking: whether or not the patient is a current smoker ("YES" or "NO")

  • Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.)
  
<b>Medical( history):</b>

  • BP Meds: whether or not the patient was on blood pressure medication (Nominal)

  • Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)

  • Prevalent Hyp: whether or not the patient was hypertensive (Nominal)

  • Diabetes: whether or not the patient had diabetes (Nominal)
  
<b>Medical(current):</b>

  • Tot Chol: total cholesterol level (Continuous)

  • Sys BP: systolic blood pressure (Continuous)

  • Dia BP: diastolic blood pressure (Continuous)

  • BMI: Body Mass Index (Continuous)

  • Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)

  • Glucose: glucose level (Continuous)
  
<b>Predict variable (desired target):</b>

  • 10-year risk of coronary heart disease CHD(binary: “1”, means “Yes”, “0” means “No”) - DV
  
![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)

### <b>Project Flowchart:</b>
1. Initial preparations(Loading the dependencies and the data)

2. EDA 

3. Clean-Up
     * Handling null values.
     * Handling duplicate values.
     * Removing Outliers.

4. Feature engineering
     * Feature encoding
     * Grouping columns for better understanding.
     * Checking correlation for feature removal.
     * Checking the distribution of the data.
     
5. Pre processing of the data
     * Dealing with class imbalance.
     * Splitting and scaling the data.
    
6. Model implementation 
     * Logistic Regression
     * Decision tree classifier
     * Random Forest Classifier
     * Gradient Boosting Classifier

7. Model explainability

![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)

### <b>Conclusion:</b>

<b>1. EDA insights:</b>
  * The age group that is most likely to have a positive CHD risk factor is 47-65.
  * Education level is not a great factor to determine the CHD risk factor.
  * Males have a 7% greater chance of having a positive CHD risk factor.
  * Smoking increases the chances of a positive CHD risk factor by around 3%.  
  * Having BP medications increases the chances of a positive CHD risk factor by around 19%.
  * Having a prevalent stroke increases the chances of a positive CHD risk factor by around 31%.
  * Prevalent Hypertension increases the chances of a positive CHD risk factor by around 13%.
  * Diabetes increases the chances of a positive CHD risk factor by around 24%.
   
<b>2. Results from ML models:</b>
  * Logistic regression gives a ROCAUC score of 0.6365 on the testing set. This is worst performing model.
  * Decision tree model gives a ROCAUC score of 0.6617 on the testing set.
  * Random Forest Classifier model gives a ROCAUC score of 0.7584 on the testing set. This is the best performing model.
  * Gradient Boosting Classifier model gives a ROCAUC score of 0.7416 on the testing set.
  * Classification report and confusion matrix has been plotted for all the models.
  * Model explainability has been achieved by SHAP library's summary plot and an attribute called feature_importances_ of the tree based algorithms.
  * Total cholestrol and age are the two most important factors to predict the CHD risk factor.

<b>3. Challenges faced:</b>
  * Feature engineering.
  * Handling class imbalance.
  * Choosing model explainability techniques.
  * Running the slow Gradient Boosting Classifier.

![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)

<b> For further information you can check the google colab file added in the repository. 

If you find any mistakes or have any suggestions for me, please reach out to me, all the criticism is heartly welcomed.

You can also reach out to me for project collaborations.

My Email Id - <u>syedshabbir107@gmail.com</u>

My LinkedIn profile - [Profile](https://www.linkedin.com/in/syed-adnan-s-2b899b228/)</b>

### Thankyou for tagging along to the end.
