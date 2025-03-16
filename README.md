## Techlabs Düsseldorf Data Science Track - Team 2 

### Project: Predicting Sleep Disorder 
This project seeks to predict sleep disorders by leveraging machine learning based on a comprehensive dataset containing 374 in raw data & 100,000 records in synthetic data.The dataset comprises 13 key variables, categorized as follows:

1. Demographics: 👤
Person ID: Unique identifier for each individual.
Gender: 🚻 (Male/Female)
Age: 📅 (Years)
Occupation: 💼 (e.g., Software Engineer, Doctor, Teacher)
BMI Category: 📏 (Underweight, Normal, Overweight, Obese)

3. Cardiovascular Health: ❤️
Blood Pressure: 🌡️ (Systolic/Diastolic)
Heart Rate: 💓 (Beats per minute)

4. Lifestyle: 🏃‍♀️
Physical Activity Level: ⏱️ (Minutes per day)
Stress Level: 😟 (Scale of 1 to 10)
Daily Steps: 🚶 (Number of steps)

5. Sleep-Related Factors: 💤
Sleep Duration: ⏰ (Hours per day)
Quality of Sleep: ⭐ (Scale of 1 to 10)

6. Sleep Disorder: 🤕 (None, Insomnia, Sleep Apnea) - Target Variable

   
Data Preprocessing:
Categorical variables, such as gender and BMI category, were encoded using binary and ordinal encoding methods to make them suitable for machine learning algorithms. The data was then split into training (80%) and testing (20%) subsets to evaluate model performance effectively.
Exploratory Data Analysis:
Next, we delved into exploratory data analysis to uncover trends and relationships within the dataset. Histograms and boxplots were used to visualize the distribution of key variables. For instance, higher stress levels were observed to correlate with poorer sleep quality, while increased physical activity appeared to have a positive impact on sleep duration. These insights guided the modeling process.
Model Development:
With the preprocessed data in hand, we implemented two classification models, including Logistic Regression and Random Forest. Each model was trained and evaluated. The Random Forest model stood out for its ability to handle complex relationships between features and deliver high accuracy.

Among the models tested, the Random Forest classifier emerged as the most effective, achieving an accuracy of 93%. Key findings include:

Feature Importance: Blood pressure, BMI category, and age were identified as the most influential predictors of sleep disorders.

