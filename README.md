# ACCENTURE
# [Task 4 - Model Presentation (with talk track) (1).pdf](https://github.com/user-attachments/files/17613009/Task.4.-.Model.Presentation.with.talk.track.1.pdf)
BUSINESS ANALYTICS PORTFOLIO
# **Accenture Data Analytics Internship - Social Buzz Project**

## **Table of Contents**
- [Overview](#overview)
- [Project Understanding](#project-understanding)
- [Data Cleaning & Modeling](#data-cleaning--modeling)
- [Data Visualization & Storytelling](#data-visualization--storytelling)
- [Client Presentation](#client-presentation)
- [Key Learnings and Reflections](#key-learnings-and-reflections)
- [Repository Structure](#repository-structure)

---

## **Overview**
This repository documents my work as a Data Analytics Intern with Accenture North America, focused on a client project for Social Buzz, a social media platform. This project involved data cleaning, modeling, and analysis to uncover insights into Social Buzz’s most popular content categories. 

> **Data Source**: Data provided by Accenture as part of the Social Buzz case study simulation.

---

## **Project Understanding**

### **Objective**
Social Buzz, a rapidly growing social media company, is preparing for an IPO and aiming to optimize its content engagement. The primary goal of this analysis was to identify the top 5 content categories by popularity, based on user reactions, to guide strategic decisions.

### **Key Deliverables**
1. **Big Data Audit**: Review Social Buzz's data management practices.
2. **IPO Preparation**: Provide guidance for a successful IPO.
3. **Content Analysis**: Identify the top 5 content categories by popularity.

### **My Role**
As a Data Analyst, I performed data cleaning, merging, modeling, and visualization to create a clear, actionable dataset and insights for Social Buzz. I collaborated with team members to align analysis with business objectives and client needs.

---

## **Data Cleaning & Modeling**

### **Datasets Used**
The analysis focused on the following datasets:
- **Reaction Dataset**: Contains information on user reactions, including `Reaction Type` and `Score`.
- **Content Dataset**: Includes details of uploaded content, such as `Content ID`, `Type`, and `Category`.
- **Reaction Types Dataset**: Provides a popularity score for each reaction type.

### **Data Cleaning Process**
1. **Removed Null Values**: Ensured complete rows for accuracy.
2. **Standardized Data Types**: Corrected data types (e.g., scores as integers).
3. **Filtered Columns**: Retained relevant columns, including `Content ID`, `Category`, `Reaction Type`, and `Score`.

### **Data Modeling**
- **Merging Datasets**: Combined the Reaction, Content, and Reaction Types datasets, using `Reaction Dataset` as the base and joining on relevant keys.
- **Aggregating Scores**: Calculated total popularity scores by content category to determine the top 5 most popular categories.

> **Outcome**: A structured and cleaned dataset ready for visualization.

---

## **Data Visualization & Storytelling**

### **Presentation Structure**
The presentation was structured to communicate the data insights in a clear and accessible format:
1. **Agenda**: Outlined the presentation’s goals.
2. **Project Recap**: Reviewed Social Buzz’s business goals and challenges.
3. **Problem Statement**: Defined the objective of identifying the top 5 content categories.
4. **Team Introduction**: Introduced the analytics team and roles.
5. **Process Overview**: Walked through data cleaning, modeling, and analysis steps.
6. **Insights and Results**: Presented visualizations and insights from the analysis.

### **Visualizations and Insights**

- **Top 5 Categories by Popularity**  
  ![Top 5 Categories Bar Chart](path/to/Top5_Categories_Bar_Chart.png)  
  *Description*: Bar chart showcasing the top 5 content categories and their popularity scores.

- **Reaction Volume by Category**  
  ![Reaction Volume Chart](path/to/Reaction_Volume_Chart.png)  
  *Description*: Displays reaction counts across categories, highlighting user engagement levels.

- **Monthly Posting Trends**  
  ![Monthly Trends Line Chart](path/to/Monthly_Trend_Line_Chart.png)  
  *Description*: Line chart illustrating monthly posting trends, showing seasonal engagement patterns.

> **Outcome**: These visuals helped communicate insights effectively, supporting strategic recommendations.

---

## **Client Presentation**

### **Presentation Highlights**
1. **Top Categories Identified**: The top 5 categories identified were Animals, Science, Healthy Eating, Technology, and Food.
2. **Audience Insights**: Engagement in categories like Healthy Eating indicates a health-conscious user base.
3. **Seasonal Posting Patterns**: Higher posting volumes in January suggest a seasonal trend, useful for campaign planning.

### **Recommendations**
- **Diversify Content Algorithms**: Ensure balanced content recommendations.
- **Health-Focused Partnerships**: Collaborate with brands in the healthy eating space.
- **Seasonal Campaign Planning**: Leverage posting trends to drive engagement around key months.

---

## **Key Learnings and Reflections**

### **Skills Developed**
- **Data Cleaning and Preparation**: Advanced skills in preparing complex datasets.
- **Data Modeling**: Proficiency in merging and structuring data across tables.
- **Visualization and Storytelling**: Ability to create compelling data stories for non-technical audiences.

### **Personal Reflection**
This internship taught me the importance of aligning data analysis with business objectives and communicating insights effectively. I gained hands-on experience transforming raw data into strategic insights, which I look forward to applying in future roles.

---

## **Repository Structure**
