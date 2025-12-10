# Smart_Burn
🏃‍♂️ SmartBurn: AI-Based Calorie Burn Prediction 🔥
💡 Introduction

In today’s world, where health and fitness awareness continues to grow, tracking the number of calories burned during physical exercise has become essential.
Many individuals rely on wearable devices such as FitBit or smartwatches to estimate calories burned; however, these devices are often expensive or not easily accessible.

SmartBurn aims to provide an intelligent and accessible alternative by utilizing Machine Learning (ML) algorithms to predict calories burned based on exercise data such as duration, heart rate, weight, and gender. This approach offers a more accurate and convenient method for monitoring physical activity without the need for costly hardware or specialized fitness devices.

❗ Problem Statement

Most existing calorie tracking systems rely on wearable smart devices or advanced gym equipment, which are often expensive.

Even when devices are available, they may not provide personalized or accurate results due to differences in body composition, fitness level, and exercise intensity.

Manual estimation methods depend on general formulas that overlook individual variations and specific workout types.

There is a growing need for an intelligent, data-driven system that can accurately predict calorie burn based on workout data, providing gym users, trainers, and fitness enthusiasts with reliable feedback without costly equipment or manual input.

🎯 Objectives

Develop a Machine Learning model capable of accurately predicting calories burned based on user-specific physiological data (duration, heart rate, body temperature, weight, gender, age).

Collect, preprocess, and analyze fitness data to identify the most influential features affecting calorie expenditure and improve model precision.

Compare the performance of multiple regression algorithms (Linear Regression, Random Forest, KNN, SVM, Decision Tree, Extra Tree, Stacking, Voting) to select the most accurate and efficient model.

Design a prototype system that can later be integrated into a smart fitness application or used by gyms and trainers to provide real-time calorie predictions and insights.

Enhance user awareness and motivation by offering data-driven feedback to monitor calorie burn and achieve fitness goals effectively.

🧠 Models and Performance

The project explores multiple regression algorithms, including:

Linear Regression 📈

K-Nearest Neighbors (KNN) 🤝

Support Vector Machine (SVM) ⚡

Decision Tree 🌳

Extra Trees 🌲

Random Forest 🌳🌳

Stacking and Voting Ensemble Models 🏅

Best Model Performance:

Random Forest 🌟

Test R²: 0.99795 ✅

Train R²: 0.99971 ✅

🖥️ API Integration

The project includes a RESTful API that allows external applications to input user exercise data and receive predicted calorie burn in real-time.

<img width="1919" height="1002" alt="deploy" src="https://github.com/user-attachments/assets/8e534a8d-2816-4c08-a681-c6c8f2bce2b3" />
📝 Data Input Guide

To get the most accurate calorie prediction, please fill in the following fields:

✨ Select Gender

Purpose: Identifies the user's gender

Note: Choose Male or Female from the dropdown list

✨ Age (years)

Purpose: Current age in years

Note: Enter a whole number (e.g., 21, 30, 45)

✨ Height (cm)

Purpose: User height in centimeters

Note: Required for body metrics calculations

✨ Weight (kg)

Purpose: Current weight in kilograms

Note: Use your current accurate weight for higher prediction accuracy

✨ Duration (minutes)

Purpose: How long the exercise was performed

Note: Enter the exact number of minutes you were active

✨ Heart Rate (bpm)

Purpose: Heart rate during or right after the activity

Note: Enter BPM (beats per minute) measurement

✨ Body Temperature (°C)

Purpose: Body temperature after the activity

Note: Measure and enter your temperature post-workout

⭐ Reminder:
After completing all fields, click “Predict Calories” for the model to process your inputs and generate your estimated calorie burn result. 🔥


📊 Power BI Visualization

SmartBurn also provides interactive Power BI dashboards for visualizing workout data and calorie predictions, helping users and trainers monitor trends and performance.
![visualization](https://github.com/user-attachments/assets/2ada3cbb-9d03-491f-ae46-f7c8a167d87d)

✨ Features

🏋️ Personalized Calorie Prediction: Predicts calories burned based on user-specific data such as weight, gender, age, heart rate, and exercise duration.

📊 Data-Driven Insights: Analyzes workout data to identify the most influential factors affecting calorie expenditure.

🤖 Multiple ML Models: Compares various machine learning algorithms (Linear Regression, Random Forest, KNN, SVM, Decision Tree, Extra Trees, Stacking, Voting) to select the best model.

🌟 High Accuracy: Best model (Random Forest) achieves very high R² scores on both Train and Test datasets.

🖥️ API Integration: RESTful API to receive user data and provide real-time calorie predictions.

📊 Power BI Dashboards: Interactive dashboards for visualizing workout data and predictions, helping users and trainers monitor performance.

💸 Cost-Effective: No need for expensive wearable devices or advanced gym equipment.

📈 Motivation & Awareness: Helps users track progress and achieve fitness goals with accurate and easy-to-understand reports.

🛠️ Technologies Used

Python 🐍

scikit-learn 🤖

Flask/FastAPI 🌐

Pandas, NumPy 📊

Power BI 📈
