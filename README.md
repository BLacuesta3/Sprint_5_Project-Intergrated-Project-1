# 🎮 Video Game Exploratory Data Analysis & Hypothesis Testing Project
**Video Game Sales Analysis (EDA & Statistical Testing)**

## 📌 Project Overview  
In this project, I performed **Exploratory Data Analysis (EDA)** to help the online gaming store *Ice* identify patterns that influence whether a video game is likely to succeed.  

The analysis is based on historical data (up to 2016), including:  
- ⭐ User and critic reviews  
- 🎯 Game genres  
- 🎮 Platforms (PlayStation, Xbox, PC)  
- 🌍 Regional and global sales  

The objective is to uncover **trends and key factors that impact sales performance** to support data-driven decisions for future releases.

## 📂 Dataset  
- 📄 File Name: `games (8).csv`  
- Contains data on video game sales, reviews, platforms, genres, and ESRB ratings  

## 🛠️ Tools and Libraries Used  
- 🐼 pandas  
- 🔢 numpy  
- 📊 matplotlib  
- 📈 seaborn  
- 📉 scipy.stats  

## 🔍 Methodology  

### 1️⃣ Data Preparation  
- Loaded and inspected the dataset  
- Handled missing values  
- Corrected data types and standardized columns  

### 2️⃣ Exploratory Data Analysis  

#### 📊 Game Release Trends  
- Analyzed number of games released per year  
- Identified reliable time periods  

#### 🎮 Platform Analysis  
- Compared total sales across platforms  
- Identified top-performing platforms  
- Built yearly sales distributions  

#### 📉 Platform Lifecycle  
- Analyzed how platforms rise and decline over time  
- Estimated platform lifespan trends  

#### 📅 Relevant Time Period Selection  
- Selected appropriate data window for forecasting (2017)  

#### 📦 Sales Distribution by Platform  
- Used boxplots to compare global sales  
- Evaluated differences in averages and spread  

#### ⭐ Reviews vs Sales (PS4 Case Study)  
- Built scatterplots for reviews vs sales  
- Calculated Pearson correlation  

#### 🔄 Cross-Platform Comparison  
- Compared sales of the same games across platforms  

#### 🎯 Genre Analysis  
- Identified most profitable genres  
- Compared sales distributions  

#### 🌍 Regional Analysis (NA, EU, JP)  
- Top 5 platforms per region  
- Market share differences  
- Top 5 genres per region  
- Impact of ESRB ratings  

## 📈 Hypothesis Testing  

### 🧪 Hypothesis 1  
- **H₀:** Average user ratings of Xbox One and PC are equal  
- **H₁:** Average user ratings are different  
- 📊 Test Used: `scipy.stats.ttest_ind`  
- 📉 Result: Failed to reject the null hypothesis  

### 🧪 Hypothesis 2  
- **H₀:** Average user ratings for Action and Sports genres are equal  
- **H₁:** Average user ratings are different  
- 📊 Test Used: `scipy.stats.ttest_ind`  
- 📉 Result: Failed to reject the null hypothesis  

### ⚙️ Significance Level  
- Alpha = **0.05**  

## 📊 Key Insights  
- Platform popularity follows a lifecycle pattern with clear rise and decline phases  
- Sales distributions vary across platforms and genres  
- Reviews show some correlation with sales but are not always strong predictors  
- Regional preferences differ across platforms and genres  
- No statistically significant difference found in tested rating groups  

## 🚀 Conclusion  
This analysis highlights key drivers of video game success, including platform trends, genre performance, and regional differences. These insights can support better decisions around platform targeting, genre focus, and regional strategy.
