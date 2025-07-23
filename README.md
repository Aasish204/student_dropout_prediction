# Student_Dropout_Prediction
This project analyzes the school dropout situation in Bagmati Province, Nepal, using data analytics and machine learning. It helps identify the key reasons why students drop out before completing school and suggests how to support them better.

⚠️ Note:

    •The dataset is focused only on Bagmati Province, not the whole of Nepal.
    •It is partially synthetic — some data points were generated or estimated using AI tools to fill gaps from visual sources. 
        This means the dataset may not exactly match real-world figures and is used for educational purposes only.

________________________________________
🔍 Project Goals
1.	Understand the major reasons behind school dropout in Bagmati Province.
2.	Use data to identify students at risk of dropping out.
3.	Build models to predict dropout likelihood.
4.	Segment students into risk groups to plan targeted interventions.
________________________________________
📊 Dataset

•	Based on charts and data from the UNICEF Nepal Education Fact Sheet 2022.

•	Focused only on students from Bagmati Province.

•	Some values were synthetically generated to complete or simulate the dataset.

•	Includes:

    o	Demographics: gender, age, marriage status, disability
    o	School details: school type, district, area type, distance to school, library/internet access
    o	Performance: attendance rate, academic score, class repetition, education level
    o	Socio-economic: wealth level
    o	Target: dropout (0 = no, 1 = yes)

________________________________________
🛠️ Models Used
1.	Logistic Regression – Predicts dropout based on input features with ~98% accuracy.
2.	Decision Tree – Visual model for identifying dropout causes (~96% accuracy).
3.	K-Means Clustering – Groups students (Weak, Average, Strong) based on performance.
________________________________________
📈 Key Findings
1.	Low attendance and poor academic scores are strong predictors of dropout.
2.	Rural students, girls, and those from low-income families face more challenges.
3.	Students who live far from school or lack access to internet/libraries are at higher risk.
4.	Some districts in Bagmati show higher dropout patterns than others.
