# ACCENTURE
BUSINESS ANALYTICS PORTFOLIO
# **Accenture Data Analytics Internship - Social Buzz Project**

## **Table of Contents**
- [Overview](#overview)
- [Project Understanding](#project-understanding)
- [Data Cleaning & Modeling](#data-cleaning--modeling)
- [Data Visualization & Storytelling](#data-visualization--storytelling)
- [Client Presentation](#client-presentation)
- [Key Learnings and Reflections](#key-learnings-and-reflections)
- [Data & Visualizations](#data--visualizations)
- [Repository Structure](#repository-structure)

---

## Overview

This repository documents my data analysis work completed during the **Accenture Virtual Internship** as part of a **Data Analytics team** assigned to **Social Buzz**, a fast-growing social media company. With guidance from seasoned Accenture professionals, we tackled Social Buzz’s data challenges, offering insights into their content engagement trends to support their scaling efforts and IPO preparation.

---

## Project Understanding

Our team’s primary objective was to analyze Social Buzz’s vast unstructured data to identify the **top 5 content categories** by popularity, understand engagement trends, and support Social Buzz in developing a data-driven strategy. This internship provided an excellent introduction to Accenture’s approach to project management and client collaboration, where each team member’s role was vital.

### Team Structure
- **Andrew Fleming**: Chief Technical Architect, guiding the data architecture.
- **Marcus Rompton**: Senior Principal, leading data engineering and ensuring data integrity.
- **My Role**: Junior Data Analyst, conducting data cleaning, modeling, and visualization to deliver actionable insights.

### Client and Business Context
- **Client**: Social Buzz, a social media platform with a focus on anonymous, content-first engagement.
- **Challenge**: Managing high volumes of unstructured data (100,000 posts daily), ensuring scalability, and preparing for IPO.
- **Objective**: Deliver content popularity insights and best practices for efficient data management.

---

## Data Cleaning & Modeling

In this phase, I followed Accenture’s best practices to ensure data quality and relevance for analysis, focusing on these steps:

1. **Data Understanding**: Analyzed the data model to identify necessary datasets:
   - Selected **Reaction**, **Content**, and **Reaction Types** datasets to determine content popularity based on reaction scores.
2. **Data Cleaning**:
   - Removed rows with missing values and unnecessary columns.
   - Standardized data formats across datasets.
3. **Data Modeling**:
   - Merged datasets using the **Reaction** table as the base.
   - Calculated popularity scores by aggregating reaction scores across content categories.

Outcome: A clean, structured dataset ready for analysis, focusing on answering Social Buzz’s primary question about the top content categories.

---

## Data Visualization & Storytelling

In line with Accenture’s standards for data storytelling, I created visualizations that clearly communicate findings to stakeholders:

1. **Top 5 Content Categories**: Represented in a **bar chart** displaying each category’s popularity score in descending order, making it easy to identify high-performing content types.
2. **Engagement Insights**:
   - **Total Categories**: Noted that there were 16 unique categories.
   - **Reactions for Top Category**: Highlighted that *Animals* received the highest reactions (1,897).
   - **Most Active Month**: **January** recorded the highest activity, aligning with post-holiday trends. This insight was visualized in a **column chart** to show monthly engagement.
   
Each visualization emphasized how specific types of content, like *Animals* and *Science*, drove engagement on Social Buzz, providing the client with an engaging and actionable narrative.

---

## Client Presentation

In our final presentation, structured as per Accenture’s guidelines, we focused on delivering clear insights and actionable recommendations:

- **Project Summary**: Recap of project goals, key team members, and Social Buzz’s objectives.
- **Top 5 Categories**:
   - **Animals**, **Science**, **Healthy Eating**, **Technology**, and **Food** were presented as the most engaging categories.
   - Discussed each category’s role in attracting user engagement.
- **Insights on User Preferences**:
   - Highlighted user interest in “real-life” and factual content.
   - Identified health-conscious topics as potential campaign areas (e.g., Healthy Eating).
- **Strategic Recommendations**:
   - **Content Balance**: Suggested an algorithm to maintain category variety.
   - **Campaign Opportunities**: Recommended partnerships with health-focused brands to leverage the popularity of the *Healthy Eating* category.

This presentation demonstrated our ability to translate data insights into strategic recommendations that align with Social Buzz’s business goals.

---

## Key Learnings and Reflections

This internship provided hands-on experience in Accenture’s structured approach to data analytics and client engagement:
- **Data Cleaning Skills**: Ensured that datasets were clean, accurate, and relevant to the analysis.
- **Visualization Proficiency**: Created impactful visuals that conveyed findings in a business-friendly way.
- **Client-Focused Communication**: Presented technical insights in a clear, actionable format tailored to Social Buzz’s needs.
- **Team Collaboration**: Learned from the expertise of senior team members, applying best practices for data integrity and client impact.

---

## Data & Visualizations

### Dataset

- **Cleaned Dataset**: [Task 3_Final Content Data set.csv](https://github.com/user-attachments/files/17658972/Task.3_Final.Content.Data.set.csv)

### Visualizations
1. **Top 5 Content Categories**:
   - [Top 5 Categories Bar Chart](https://github.com/user-attachments/assets/a0f0d07c-6a84-48e0-9fd8-a0c591aca024)
): Shows the popularity of each of the top 5 categories.
   
2. **Additional Insights**:
   - **Unique Categories**: Total number of unique content categories identified.
   - **Month with Most Posts**: January, representing the peak of user engagement.
   - **Reactions to Animals Posts**: Highest engagement observed for the “Animals” category.

   **View Additional Insights Visualizations**:
   - [Unique Categories](https://github.com/user-attachments/assets/69122a09-c29b-421c-b43d-0243ae18ee29)
)
   - [Monthly Posts Trend (January Peak)](https://github.com/user-attachments/assets/eae79bd4-f892-489d-b127-5b480c48a100)
)
   - [Reactions to Animals](https://github.com/user-attachments/assets/28530e4d-11be-4646-a80f-80118f661fa0)
)

---
## **Repository Structure**
