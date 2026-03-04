# ⚽ FIFA 2019 Data Exploration (EDA) Project

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the FIFA 2019 Complete Player Dataset.

The objective of this project is to analyze player data and discover meaningful insights about:

- Player ratings and potential
- Age distribution
- Club and nationality analysis
- Preferred foot comparison
- Performance category analysis
- Top players based on different attributes

---

## 📂 Dataset Information

- **Dataset:** data.csv
- **Format:** CSV  
- **Total Players:** ~18,000  
- **Total Features:** 80+ columns  

### Important Columns Used:

- Name  
- Age  
- Nationality  
- Club  
- Position  
- Overall  
- Potential  
- Preferred Foot  
- Work Rate  
- Dribbling  
- BallControl  
- Finishing  
- Passing attributes  
- Physical attributes  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- WordCloud  
- Missingno  

---

## 📊 EDA Steps Performed

1. Imported necessary libraries  
2. Set seaborn color palette  
3. Loaded dataset  
4. Checked head, columns, shape, and info  
5. Handled missing values  
6. Visualized missing data using heatmap  
7. Created multiple subplots  
8. Generated WordCloud for nationality  
9. Filled missing values using mean, median, and mode  
10. Created performance categories:
    - General
    - Shooting
    - Passing
    - Mobility
    - Power
    - Mental
    - Defending
    - Rating  
11. Compared players by position  
12. Compared players by height  
13. Analyzed work rate distribution  
14. Compared nationality and overall score  
15. Compared popular clubs by overall rating  
16. Found top 10 left-footed players  
17. Found top 10 right-footed players  
18. Compared ball control & dribbling  
19. Identified player with highest overall & potential  
20. Found best player in each performance category  
21. Generated WordCloud for most frequent names and clubs  

---

## 📈 Key Insights

- Majority of players are right-footed.
- Some clubs have significantly higher average overall ratings.
- Younger players tend to have higher potential ratings.
- Shooting and Passing ratings vary by position.
- Certain nations dominate the top overall rankings.

---

## ▶️ How to Run This Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/harithaharikumar100-gif/fifa-data-exploration.git
