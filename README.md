# Student_Dropout_Prediction

This project analyzes the school dropout situation in Bagmati Province, Nepal, using data analytics and machine learning. It helps identify the key reasons why students drop out before completing school and suggests how to support them better.

⚠️ Note:

     The dataset is focused only on Bagmati Province, not the whole of Nepal.

     It is partially synthetic — some data points were generated or estimated using AI tools to fill gaps from visual sources. This means the dataset may not     exactly match real-world figures and is used for educational purposes only.

<img width="625" height="9" alt="image" src="https://github.com/user-attachments/assets/627c6bfc-486f-42af-9e15-d4a526f1b17a" />


🔍 Project Goals
Understand the major reasons behind school dropout in Bagmati Province.

Use data to identify students at risk of dropping out.

Build models to predict dropout likelihood.

Segment students into risk groups to plan targeted interventions.

📊 Dataset
Based on charts and data from the UNICEF Nepal Education Fact Sheet 2022.

Focused only on students from Bagmati Province.

Some values were synthetically generated to complete or simulate the dataset.

Includes:

Demographics: gender, age, marriage status, disability

School details: school type, district, area type, distance to school, library/internet access

Performance: attendance rate, academic score, class repetition, education level

Socio-economic: wealth level

Target: dropout (0 = no, 1 = yes)

🛠️ Models Used
Logistic Regression – Predicts dropout based on input features with ~98% accuracy.

Decision Tree – Visual model for identifying dropout causes (~96% accuracy).

K-Means Clustering – Groups students (Weak, Average, Strong) based on performance.

📈 Key Findings
Low attendance and poor academic scores are strong predictors of dropout.

Rural students, girls, and those from low-income families face more challenges.

Students who live far from school or lack access to internet/libraries are at higher risk.

Some districts in Bagmati show higher dropout patterns than others.
