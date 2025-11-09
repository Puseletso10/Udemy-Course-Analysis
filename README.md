
# 📊 Udemy Course Performance Analysis

## 📁 Overview
This Power BI dashboard presents an analytical summary of **Udemy course performance**, focusing on key metrics such as **revenue, subscribers, reviews, and course engagement**. The goal is to understand which subjects and course types generate the most value and how learner levels, ratings, and pricing impact overall outcomes.

---

## 🧹 Data Preparation & Cleaning
The dataset underwent **comprehensive data cleaning and preprocessing** to ensure accuracy and reliability of insights.

### Steps performed:
- **Removed duplicates** based on `course_id` to maintain unique course entries.
- **Checked for missing values** in key fields such as `price`, `num_subscribers`, and `rating`.
- **Standardized data types** (numeric, date, and text fields).
- **Validated published timestamps** to ensure chronological accuracy.
- Ensured **consistency** in categorical values (e.g., “Beginner,” “Intermediate,” “Expert”).
- Verified **accuracy** by cross-referencing totals and averages during import.

---

## 🧾 Dataset Information

### Columns:
| Column Name | Description |
|--------------|-------------|
| **course_id** | Unique identifier for each course |
| **course_title** | Name of the course |
| **url** | Direct course link |
| **price** | Course price (in USD) |
| **num_subscribers** | Total number of enrolled learners |
| **num_reviews** | Number of reviews given by users |
| **num_lectures** | Total number of video lectures in the course |
| **level** | Course difficulty level (Beginner, Intermediate, Expert, All Levels) |
| **rating** | Average user rating (0–5 scale) |
| **content_duration** | Total video duration of the course (in hours) |
| **published_timestamp** | Date and time when the course was published |
| **subject** | Main topic category (e.g., Web Development, Business Finance, etc.) |

---

## Dashboard Highlights

### Key Metrics:
- **Revenue:** 881.7M
- **Total Subscribers:** 12M
- **Total Courses:** 3,672K
- **Average Rating:** 0.61
- **Reviews:** 574K
- **Subjects:** 4

## 📈 Analysis Breakdown:
**1. Subscribers by Subject:** Web Development dominates with 7.9M subscribers, followed by Business Finance (1.9M).
- Indicates strong demand for tech-related learning content.
  
**2. Revenue by Courses:** Top-performing courses include The Web Developer Bootcamp (24M) and The Complete Web Developer Course (23M).
- Suggests strong alignment between web development content and profitability.

**3. Subscribers by Level:** Majority of learners are Beginner Level (4.1M), highlighting Udemy’s role as an entry point for new learners.

**4. Paid vs Free Subscribers:** Free: 30.52%, Paid: 69.48%
- Most users access paid content which contribute heavily to total revenue.

**5. Revenue by Year:** Rapid growth observed between 2014–2016, peaking at 315M in 2015.
- Indicates a potential saturation or market shift after the peak period.

**6. Subscribers by Course:** The “Learn HTML5 Programming” course leads with 269K subscribers, followed by “Coding for Entrepreneurs” and “The Web Developer Bootcamp.”

---

## ⚙️ Tools & Techniques
- **Tool:** Power BI Desktop
- **Data Transformation:** Power Query Editor
- **Modeling:** DAX (Data Analysis Expressions)
- **Source File:** Udemy course dataset (CSV format)

---

## 🎯 Objective
To evaluate **Udemy’s content performance trends** by analyzing course-level data and identifying:
- High-performing subjects and courses.
- Patterns between pricing, ratings, and subscriber growth.
- Insights to guide content development and marketing focus.

---

## 🧩 Recommendations
- Continue investing in **Web Development** and **Business Finance** courses.
- Develop **Intermediate** and **Expert-level** programs to retain learners.
- Introduce strategies to **convert free users to paid subscribers**.
- Focus on **course quality improvements** to increase ratings and reviews.

---

## 👩‍💻 Author
**Puseletso Motsoari**  
*Data Analyst*  
📧 [motsoaripuseletso8@gmail.com]  
📅 *Created: [November, 2025]*

