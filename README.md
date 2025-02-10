# Gen-Z Dating App Behavior Analysis

## 1. Project Overview
In this project, we analyze the behavior and preferences of Gen-Z users on dating apps. Key areas of focus include:
- **Gender-Based Preferences**
- **Age-Related Usage Trends**
- **Regional and Temporal Behavior**
- **Feature Engineering for Predictive Modeling**

## 2. Key Insights and Observations

We derived the following insights from the dataset:

- **Age Group with Highest Activity**: The most active users fall within the *0.0 to 1.0 years* age range, revealing higher engagement than expected from the youngest users.
  
- **Daily Usage**: On average, Gen-Z users spend only *0.18 minutes per day* on dating apps, suggesting that their usage is brief but frequent.
  
- **Regional Insights**: Users in **metro areas** tend to engage with dating apps more actively than **rural users**.
  
- **Multiple App Usage**: A significant number of users engage with *multiple dating apps* simultaneously, indicating a preference for exploring multiple options.
  
- **Gender Differences**: Preliminary data suggests varying usage patterns based on gender, with some features being more engaging for one gender over the other.


## 3. Data Files and Documents
The following files are included for further review and analysis:

- **`feature_engineered_data.csv`**: The final dataset with all features processed for analysis.
- **`final_summary.csv`**: A summary of key metrics derived from the dataset.
- **`final_summary.ipynb`**: A Jupyter notebook with the detailed analysis and visualizations.


## 4. Methodology

### 4.1 Data Collection
The data was gathered through a combination of user surveys and in-app tracking of Gen-Z users' behavior. Data points collected include:
- User **age**, **gender**, and **location**
- Frequency of **app usage**
- **Time spent** on the app daily
- Features interacted with, and the **number of apps** used simultaneously

### 4.2 Data Analysis
Exploratory Data Analysis (EDA) was carried out to uncover trends and patterns in the dataset. Here’s an example of how we explored the data.


```python
import pandas as pd

# Load data
data = pd.read_csv('final_summary.csv')

# Display a summary of the data
data.describe()



When displayed on GitHub, it will format the code properly. Make sure you use the triple backticks at the beginning and end of the code block.

---

### **Visualizations**
For visualizations, you can either:
- **Embed images**: If you saved any plots from Jupyter, upload them to your GitHub repository and reference the image in the README.
  Example:
  ```markdown
  ![Age vs Daily Usage](images/age_vs_daily_usage.png)

