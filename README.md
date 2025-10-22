# 🎓 Udemy Courses Data Analysis Project

## 🧭 Objective
The goal of this project is to analyze Udemy course data to uncover patterns in **subscribers, revenue, pricing, and content duration**.  
The analysis aims to support **marketing strategies, pricing decisions**, and **content development** on online learning platforms.

---

## 📊 Dataset Description
**Source:** Kaggle — Udemy Courses Dataset  
**Rows:** ~3,683  
**Columns:** 14  

### Main Columns:
- `course_id`: Unique identifier for each course  
- `course_title`: Course name  
- `is_paid`: Whether the course is paid or free  
- `price`: Course price  
- `num_subscribers`: Number of enrolled students  
- `num_reviews`: Number of reviews  
- `num_lectures`: Total number of lectures  
- `level`: Course level (Beginner, Intermediate, etc.)  
- `content_duration`: Total hours of content  
- `subject`: Course category  
- `published_timestamp`: Date of publication  

### Data Cleaning Steps in PYTHON : 
- Removed duplicates
- Change columns type / replace ` "free"&"True" with 0 ` to be able to make agg process (price column) 
- Replaced nulls with suitable values
- Handling timestamp column    
- Created new calculated columns:
  - Extracted date parts (`year`, `month`, `day`)  
  - `revenue` = `price * num_subscribers`  
  - `Engagement Ratio` = `num_reviews / num_subscribers`   

---

## 🧰 Tools and Technologies
- **Python** → Data cleaning and EDA  
  - Libraries: `Pandas`, `Matplotlib`, `Seaborn`  , ` numpy `
- **Power BI** → Interactive dashboard creation  
- **Excel** → Used for metric testing and exporting cleaned data  
- **Python Script** →used to link the data between jupyter and power pi to maintain the flow 
---

## 🔍 Exploratory Data Analysis (Python)
Performed EDA to understand the data distribution and relationships:

- Checked missing values and outliers  
- Analyzed correlations between `price`, `subscribers`, and `duration`  
- Generated visuals such as:
  - how many courses paid and free pie chart)
  - Top 10 Courses by Subscribers (Bar Chart)  
  - the distribution of subject column per num_courses (column chart)  
  - distribution of courses per levels (column chart)   

### Example Insights from Python:
- Most Udemy courses are paid coursess with 91.6% to 8.4%
- **IT and Business** subjects attract the highest number of subscribers.  
- No strong correlation between `duration` and `number of subscribers`.  
- 2015 was the heighest year with subscribers
---

## 📈 Power BI Dashboard Overview

### Pages Created:
1. **Overview Page**
   - Subscribers & revenue trend over years  
   - Revenue distrebution per subject
   - Paid vs free percentage

2. **Subscribers Analysis**
   - subscribers per subject
   - Engagement Ratio by Subject
   - Top 5 courses py subscribers
   - subscribers per level 
   - Subscribers Trend by Year and Month

4. **Revenue Analysis**
   - subscribers per subject
   - Top 5 Courses by Subscribers
   - revenue by subject
   - Revenue Trend by Year  

5. **Content Analysis**
   -Subscribers Trend by Year  
   - Top 5 Courses by duration 
   - content duration vs subscribers   

---

## 💡 Key Insights
- **IT and Business** courses dominate both in subscriptions and revenue.  
- **Short-duration** courses attract more learners.  
- A small percentage of courses generate the majority of total revenue.  
- Higher-priced courses tend to have **fewer subscribers**.  
- Engagement (reviews/subscribers) is stronger for **affordable, practical courses**.  

---

## 🧠 Recommendations
1. **Focus on high-demand subjects** like IT and Business.  
2. **Offer discounts or bundles** for expensive courses to increase sales.  
3. **Create more short, practical courses** — they perform best.  
4. **Promote courses during peak publishing months** for maximum visibility.  
5. **Encourage feedback and reviews** to boost engagement ratio and course visibility.  

---

## 🏁 Conclusion
The analysis reveals that Udemy’s growth is driven by **affordable, short, and skill-focused** courses.  
By optimizing pricing and focusing on top-performing categories, the platform can increase both **revenue** and **learner engagement**.

---

## 📂 Project Structure

[Uploading udemy_courses_clean.csv…]()

<img width="1207" height="742" alt="Screenshot 2025-10-22 200458" src="https://github.com/user-attachments/assets/eb1e430f-352f-48c3-949a-23e0bccda11c" />
<img width="1214" height="734" alt="Screenshot 2025-10-22 200440" src="https://github.com/user-attachments/assets/67e76338-f785-428e-b959-fbc0df07e46d" />

<img width="1202" height="705" alt="Screenshot 2025-10-22 200517" src="https://github.com/user-attachments/assets/5348a36b-3f38-4970-b53e-fdf2f3556faf" />
<img width="1207" height="739" alt="Screenshot 2025-10-22 200833" src="https://github.com/user-attachments/assets/ac4a3ea3-6dfb-42af-9633-66691ddd8065" />

---

## 🧑‍💻 Author
**Islam Mohamed**  
Data Analyst | Python | Power BI | Excel | SQL
📧 *[islam.rm178@gmail.com]*  
🌐 [GitHub Profile]([https://github.com/yourusername](https://github.com/islammohamedrm))

