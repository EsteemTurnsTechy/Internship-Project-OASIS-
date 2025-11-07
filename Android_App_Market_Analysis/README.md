
 Android App Market Analysis

 Project Overview
This project explores the Android App Market on Google Play to uncover insights about app ratings, pricing, popularity, and installation trends.  
It demonstrates core data analyst skills in data cleaning, exploratory data analysis (EDA), and visualization using Python and Jupyter Notebook.

---

 Dataset
The dataset used was downloaded from Kaggle:  
 [Android App Market on Google Play](https://www.kaggle.com/datasets/utshabkumarghosh/android-app-market-on-google-play)

It contains details of apps such as:
- App name, category, and type (free or paid)
- Ratings and number of reviews
- Size, installs, and price
- Content rating and genres
- User reviews (for sentiment analysis)

---

 Tools and Libraries
- Python: Pandas, NumPy  
- Visualization: Matplotlib, Seaborn  
- Text Analysis: WordCloud, NLTK (for review sentiments)  
- Notebook: Jupyter Lab / Jupyter Notebook  
- Version Control: Git & GitHub  

---

  Data Preparation
- Imported and merged the `apps.csv` and `user_reviews.csv` datasets.  
- Cleaned data by handling missing values and converting incorrect data types.  
- Stripped symbols (like `$` and `+`) and standardized numerical columns such as `Installs`, `Size`, and `Price`.  
- Converted categorical columns to lowercase for consistency.  

---

 Exploratory Data Analysis (EDA)

 Category Exploration
- Most apps fall under the Family, Game, and Tools categories.  
- Entertainment-related apps dominate in total volume and popularity.  
- Visualization: Bar chart showing number of apps per category.

 App Ratings and Popularity
- Average rating across the Play Store is around 4.2 stars.  
- Apps with more installs generally have higher ratings and users tend to trust popular apps more.  
- Paid apps have slightly higher average ratings than free apps, suggesting estimated worth.  
- Visualization: Scatterplots showing Ratings vs Installs, and Ratings by Category.

 Install Trends
- Free apps accounts for over 90% of total installs.  
- Games, Communication, and Social   categories dominate the install counts.  
- Visualization: Bar plots and heatmaps displaying install trends by category and app type.

 Pricing Trends
- The majority of apps are free, while paid apps cluster below \$10.  
- Pricing has little correlation with app rating but can influence installs.  
- Visualization: Histogram of app prices and boxplots comparing paid vs free ratings.

  Sentiment Analysis (User Reviews)
- Text analysis of reviews showed:
- Majority of user sentiments are positive (words like love, great, useful).  
- Negative sentiments often relate to ads, bugs, or performance.  
- Visualization: WordCloud of positive and negative reviews.

---

 Key Insights
| Insight | Description |
|----------|--------------|
High Ratings| Most apps maintain a rating above 4.0. |
Popular Categories| Games, Family, and Tools are dominated in both count and installs. |
Free vs Paid| Free apps attract more users but paid apps slightly have better ratings. |
Install Correlation| High installs strongly correlate with user trust and app quality. |
Sentiment| User feedback is mostly positive, highlighting satisfaction with design and performance. |

---

 Conclusions
- The Android app ecosystem is dominated by free apps, which rely on popularity and usability to gain traction.  
- User ratings indicates key success, closely tied to installs and visibility.  
- Data-driven decisions can help developers focus on popular categories and optimize pricing strategies.  

---

 Future Analysis
- Build an interactive **dashboard** (using Power BI, Streamlit, or Tableau).  
- Perform **time-series analysis** on app updates and installs.  
- Integrate **Play Store API** for live data monitoring.

---

  Author
Oluwatimilehin Amusan 
Email: timilehin.amusan1@gmail.com  
LinkedIn: [[linkedin.com/in/yourprofile](https://www.linkedin.com/in/oluwatimilehin-amusan))  
GitHub Portfolio: [https://github.com/EsteemTurnsTechy](https://github.com/EsteemTurnsTechy)

---




### 📁 Repository Structure
