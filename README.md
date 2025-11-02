# **Project Title: Hotstar Data Analysis Using Python**

---

##  **1.Introduction / Overview**

jiohotstar is one of India’s leading OTT streaming platforms offering a wide range of movies, TV shows, and sports content.  
This project focuses on analyzing the Hotstar dataset to uncover insights about the types of content available, popular genres, and trends over time.

By performing data cleaning, analysis, and visualization, we aim to understand:
- Which genres and types (Movies/TV Shows) dominate the platform  
- How content is distributed across age ratings  
- How content production has evolved over the years  

---

##  **2. Objectives**

- To explore and clean the Hotstar dataset  
- To perform exploratory data analysis (EDA) for better understanding  
- To visualize different patterns and distributions using charts  
- To identify trends in genres, release years, and content types  
- To derive meaningful business insights from the data  

---

##  **3. Tools & Libraries Used**

**Language:** Python  
**Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly  
**Environment:** Google Colab  

---

##  **4. Dataset Information**

The dataset provides detailed information about **Movies** and **TV Shows** available on **Disney+ Hotstar**.  
It contains 10 columns and 6874 rows, covering details like titles, genres, release years, ratings, and content type.

### **Columns Included:**
- **hotstar_id:** Unique identifier for each title  
- **title:** Name of the movie or TV show  
- **description:** Short summary or storyline of the content  
- **genre:** Category or type of content (e.g., Drama, Comedy, Action, etc.)  
- **year:** Year of release  
- **age_rating:** Audience suitability (U, U/A, A, etc.)  
- **running_time:** Duration in minutes (for Movies)  
- **seasons:** Number of seasons (for TV Shows)  
- **episodes:** Number of episodes (for TV Shows)  
- **type:** Specifies whether it is a Movie or a TV Show  

**Source:** Kaggle / Public Dataset  
**Shape:** 6874 rows × 10 columns  

This dataset is suitable for **Exploratory Data Analysis (EDA)** and **Visualization**, helping us uncover insights about content trends, audience targeting, and platform strategy.


---

## **5. Expected Outcomes**

- Visualizations showing trends in genres, release years, and ratings  
- Insights about which type of content (Movies or TV Shows) dominates Hotstar  
- Understanding the age-rating distribution and popular genres  
- Summary of business insights to help platform content strategy  

---

##  **Business Problems and Questions Solved:**

### 1️⃣ Business Problem:
The content strategy team wants to know whether to focus more on Movies or TV Shows on the platform.  

**Business Question:**  
What is the count of Movies and TV Shows available on Hotstar?

---

### 2️⃣ Business Problem:
The marketing team wants to promote the most popular genres to attract new subscribers.  

**Business Question:**  
Which genre has the highest number of titles on the platform?

---

### 3️⃣ Business Problem:
The compliance and content curation team wants to ensure there is enough content for all age groups.  

**Business Question:**  
How is the content distributed across different age ratings (U, UA, A)?

---

### 4️⃣ Business Problem:
The management team wants to understand how content production or acquisition has changed over time.  

**Business Question:**  
How many Movies and TV Shows were released each year on Hotstar, and what is the trend over the years?

---

### 5️⃣ Business Problem:
The content strategy team wants to identify which genres are dominated by Movies and which by TV Shows, to plan future content production and licensing decisions.  

**Business Question:**  
For each genre, how many Movies and TV Shows are available on the platform?

---

### 6️⃣ Business Problem:
The content and compliance teams want to analyze how content is distributed across different age ratings and genres, to ensure that there is a good balance of content for all audience segments — from kids to adults.  

**Business Question:**  
Which genres are popular among different age groups on Hotstar?
