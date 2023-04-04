# LiverDisease

This project is about liver disease was created in cooperation with [Urszula Jarocka](https://github.com/UrszulaJa)

Patients with Liver disease have been continuously increasing because of excessive consumption of alcohol, inhale of harmful gases, intake of contaminated food, pickles and drugs, so it is valid to inspect existing medical test results and find some patterns which may improve disease prediction.

This project is based on the dataset is provided from [here](https://www.kaggle.com/datasets/uciml/indian-liver-patient-records). This dataset contains 416 liver patient records and 167 non liver patient records collected from North East of Andhra Pradesh, India.

**Attribute Information:**
1) Age of the patient
2) Gender of the patient
3) Total Bilirubin
4) Direct Bilirubin
5) Alkaline Phosphotase
6) Alamine Aminotransferase
7) Aspartate Aminotransferase
8) Total Protiens
9) Albumin
10) Albumin and Globulin Ratio
11) Dataset: field used to split the data into two sets (patient with liver disease, or no disease)

**In order to precisely analyze how each medical test result affect whether a patient is sick or not, the following tests were performed:**
- The influence of the patient's age on the risk of the disease.
- The influence of the patient's gender on the risk of the disease.
- The influence of the patient's age and gender on the risk of the disease.
- The influence of the patient's blood albumin concentration on the risk of the disease.
- The influence of the patient's age, gender and blood albumin concentration on the risk of the disease.
- The influence of the patient's ratio of albumin to globulins in the blood on the risk of the disease.
- The influence of the patient's age, gender, blood albumin concentration and ratio of albumin to globulins on the risk of the disease.
- The influence of the patient's total blood protein concentration on the risk of the disease.
- The relationship between total protein, albumin and albumin-to-globulin ratio variables to each other.
- The influence of the patient's blood total bilirubin concentration on the risk of the disease.
- The influence of the patient's blood direct bilirubin concentration on the risk of the disease.
- The relationship between total bilirubin and direct bilirubin.
- The influence of the patient's alkaline phosphotase level on the risk of the disease.
- The influence of the patient's alamine aminotransferase level on the risk of the disease.
- The influence of the patient's aspartate aminotransferase level on the risk of the disease.
- The influence of individual factors on the risk of the disease depending on the patient's gender.
- The influence of the number of morphotic elements exceeding the specified norm on the risk of disease.
- The relationship between total bilirubin, alkaline phosphotase, alamine aminotransferase and total protiens variables to each other.
- The influence of explanatory variables on the total protein variable.

**Conclusions based on the performed tests:**
1) None of the examined variables showed the characteristics of a normal distribution, therefore non-parametric tests were used to find statistical relationships between the selected factors.
2) According to some individual tests, there might be no relationship between variables. However, it should be noted that all morphotic elements are components of the same patient's blood, so individual factors can influence each other - directly or indirectly. Based on the performed tests, it can be concluded that all explanatory variables have some impact on the risk of the disease. For example, there is no statistically significant difference between the mean value of total proteins of sick people and healthy people. Thus, there is no relation between total proteins and the presence or absence of the disease. On the other hand, there is strong relation between the risk of the disease and the value of albumin, which is a component of protein. To sum up, the results suggest no influence of protein on the risk of the disease with simultaneous significant dependence of albumins and globulins. Therefore, it can be concluded that all explanatory variables are significant.
3) Significant factors that increase the risk of the disease are gender and age. Men, especially adults and the elderly, are mostly at risk. Among the group of examined patients, men accounted for as much as 78% of all patients. In addition, depending on the patient's gender, it is important to analyze different features. If the patient is a male, tests can include examining total bilirubin, direct bilirubin, alkaline phosphotase, alamine aminotransferase, aspartate aminotransferase and albumin. On the other hand, for females, only the results of alkaline phosphotase tests can provide significant information about the risk of the disease.
4) Moreover, all morphotic elements (total bilirubin, direct bilirubin, alkaline phosphatase, alamine aminotransferase, aspartate aminotransferase, total protein, albumin, albumin-to-globulin ratio) significantly affects the risk of the disease. The more elements out of the norm, the greater chance that the patient is sick. In particular, when 3 morphotic elements are outside the norm, the patient should be diagnosed.
