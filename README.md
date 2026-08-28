# 🎬 Netflix - Content Strategy & Business Analytics

<div align="center">

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Data%20Analysis-4DABCF?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-pink?logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4EAEAA?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
[![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?logo=googlecolab&logoColor=fff)](#)

**A Data-Driven Netflix Content Strategy Case Study using Python & Exploratory Data Analysis**

**Quick access:** [📓 View the notebook](./notebooks/Netflix_Business_Case_Study.ipynb) · [![Open Notebook In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Hazardous9hub/Netflix-Business-Case-Study/blob/main/notebooks/Netflix_Business_Case_Study.ipynb) ·  [📊 View the dataset](./data/netflix.csv) · [📄 Read the PDF report](./reports/SHIVALING_NETFLIX%20Business%20Case%20Study.pdf)

</div>

---

## ⭐ Project Highlights

- Analysed **8,807 Netflix titles** across **12 catalogue variables** using Python-based exploratory data analysis.
- Found that the catalogue contains **6,131 Movies** and **2,676 TV Shows**.
- Preprocessed country data to examine content associated with **124 countries**.
- Identified **2019** as the peak year for titles added in the analysed catalogue.
- Evaluated catalogue patterns across content type, genre, rating, country, creators, and time.

> **Scope note:** These findings describe catalogue metadata—not viewer behaviour or preferences.

</div>

---

## 📋 Table of Contents

- [⭐ Project Highlights](#-project-highlights)
- [🎯 Project Overview](#-project-overview)
- [📊 Dataset](#-dataset)
- [🔍 Business Problem](#-business-problem)
- [❓ Business Questions](#-business-questions)
- [📈 Analysis Performed](#-analysis-performed)
- [💡 Key Findings](#-key-findings)
- [🎯 Business Recommendations](#-business-recommendations)
- [🛠️ Tech Stack](#️-tech-stack)
- [📁 Project Structure](#-project-structure)
- [☁️ Run in Google Colab](#️-run-in-google-colab)
- [🚀 How to Use](#-how-to-use)
- [👨‍💻 Author](#-author)

---

## 🎯 Project Overview

Netflix is one of the world's leading streaming platforms, offering a large catalogue of Movies and TV Shows across multiple countries, genres, ratings and creators.

This project performs **Exploratory Data Analysis (EDA)** on Netflix's content catalogue to identify patterns in content type, countries, genres, ratings, release years, creators and catalogue growth.

The objective is to generate **data-driven insights that could support Netflix's content production and geographic growth decisions**.

### 🎯 Business Objective

> Analyze the data and generate insights that could help Netflix in deciding which type of shows/movies to produce and how they can grow the business in different countries.

---

## 📊 Dataset

The dataset contains **8,807 Netflix titles across 12 variables**.

### 📌 Dataset Features

| Feature | Description |
|---|---|
| `show_id` | Unique ID for every Movie / TV Show |
| `type` | Movie or TV Show |
| `title` | Title of the Movie / TV Show |
| `director` | Director of the Movie / TV Show |
| `cast` | Actors involved |
| `country` | Country where the content was produced |
| `date_added` | Date the title was added to Netflix |
| `release_year` | Original release year |
| `rating` | TV / content rating |
| `duration` | Movie duration or number of seasons |
| `listed_in` | Genre / category |
| `description` | Summary description |

### 📁 Dataset

The dataset used in this project is available in:

[📊 Open the Netflix dataset](./data/netflix.csv)

---

## 🔍 Business Problem

Netflix has a large and diverse content catalogue covering different:

- 🌍 Countries
- 🎬 Content types
- 🎭 Genres
- 🔞 Ratings
- 🎥 Directors
- 👥 Cast members

The business challenge is to understand the composition of this catalogue and identify patterns that can support decisions around:

- Content production
- Genre strategy
- Regional expansion
- Movie vs TV Show investment
- Audience targeting

---

## ❓ Business Questions

This case study explores the following questions:

1. What is the distribution of Movies vs TV Shows?
2. How has Netflix's catalogue changed over time?
3. Which countries contribute the most content?
4. Which genres are most represented?
5. Which ratings dominate the catalogue?
6. Which directors appear most frequently?
7. Which actors appear most frequently?
8. How does content type vary across countries?
9. When are titles most frequently added to Netflix?
10. How does the catalogue differ between Movies and TV Shows?

---

## 📈 Analysis Performed

The analysis follows a structured Exploratory Data Analysis workflow:

```text
Business Understanding
        ↓
Data Loading
        ↓
Data Understanding
        ↓
Data Quality Checks
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Univariate Analysis
        ↓
Bivariate Analysis
        ↓
Multivariate Analysis
        ↓
Business Insights
        ↓
Recommendations
```

### 🔎 Major Analysis Areas

- Dataset structure and characteristics
- Data types and descriptive statistics
- Missing-value analysis
- Duplicate-value analysis
- Movie vs TV Show distribution
- Release-year analysis
- Date-added analysis
- Rating distribution
- Country analysis
- Genre analysis
- Director analysis
- Cast analysis
- Country × Content Type analysis
- Historical catalogue growth

---

## 💡 Key Findings

### 🎬 Movies vs TV Shows

The dataset contains:

| Content Type | Titles |
|---|---:|
| 🎬 Movies | **6,131** |
| 📺 TV Shows | **2,676** |

Movies therefore form the larger share of the Netflix catalogue represented in this dataset.

---

### 🌍 Geographic Distribution

After preprocessing the country information, the analysis identifies content associated with **124 countries**.

The United States and India are among the largest contributors to the catalogue, followed by several other major international markets.

---

### 🎭 Genre Distribution

The analysis identifies several highly represented categories, including:

- International Movies
- Dramas
- Comedies
- International TV Shows
- Documentaries

---

### 🔞 Ratings

**TV-MA** is identified as the most common rating in the analysed catalogue.

---

### 📅 Catalogue Growth

The number of titles added to Netflix increased rapidly during the late 2010s.

The case-study analysis identifies **2019 as a peak year for catalogue additions**.

---

### 🎥 Creator Diversity

The catalogue contains a large number of directors and cast members, indicating a broad creator ecosystem rather than dependence on only a small group of creators.

---

## ⚠️ Analytical Note

This project analyses **Netflix catalogue metadata**.

It does **not** contain individual viewer behaviour such as:

- Watch time
- Completion rate
- User ratings
- Retention
- Churn
- Subscriber-level engagement

Therefore, catalogue frequency should not automatically be interpreted as direct evidence of viewer preference.

For example:

> A genre appearing frequently indicates strong representation in the catalogue, but does not by itself prove that viewers prefer that genre.

---

## 🎯 Business Recommendations

Based on the case-study analysis:

### 🎬 Content Strategy

- Continue investing in TV Shows while maintaining a strong Movie catalogue.
- Continue developing content across popular genres such as Drama, Comedy and International Movies.
- Maintain a balance between Movies and TV Shows to serve different audience preferences.
- Continue expanding high-quality original content.

### 🌍 Geographic Strategy

- Increase focus on localized content in markets such as India, Japan and South Korea.
- Use country-level content analysis to identify regional opportunities.
- Combine country, genre and content-type information when evaluating expansion opportunities.

### 🎥 Creator Strategy

- Continue building relationships with successful directors and actors.
- Maintain a diverse creator ecosystem to support a broad content catalogue.

### 👨‍👩‍👧 Audience Expansion

- Consider increasing family and children's content to reach broader audience segments.

### 📊 Future Data Strategy

For stronger business decisions, catalogue analysis should ideally be combined with:

- Viewing behaviour
- Watch time
- Subscriber growth
- Engagement
- Completion rate
- Retention
- Churn

---

## 🛠️ Tech Stack

```text
├── 🐍 Python
├── 📊 Pandas
├── 🔢 NumPy
├── 📈 Matplotlib
├── 🎨 Seaborn
└── 📓 Jupyter Notebook & Google Colab
```

---

## 📁 Project Structure

```text
Netflix-Business-Case-Study/
│
├── data/
│   └── netflix.csv
│
├── notebooks/
│   └── Netflix_Business_Case_Study.ipynb
│
├── reports/
│   └── SHIVALING_NETFLIX Business Case Study.pdf
│
├── .gitattributes
├── .gitignore
├── README.md
└── requirements.txt
```

---

## 🚀 How to Use

### Option 1: ☁️ Run Analysis in Google Colab

Run the complete analysis in your browser—no local installation required:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Hazardous9hub/Netflix-Business-Case-Study/blob/main/notebooks/Netflix_Business_Case_Study.ipynb)

> In Colab, select **Runtime → Run all** to execute the notebook.

### Option 2: 📖 Explore the Project

You can explore the following files directly in this repository:

- [📓 **Python Notebook**](./notebooks/Netflix_Business_Case_Study.ipynb) — complete exploratory analysis
- [📊 **Netflix Dataset**](./data/netflix.csv) — source data used for the analysis
- [📄 **PDF Report**](./reports/SHIVALING_NETFLIX%20Business%20Case%20Study.pdf) — detailed case-study report

### Option 3: 💻 Run Locally

Clone the repository:

```bash
git clone https://github.com/Hazardous9hub/Netflix-Business-Case-Study.git
```

Navigate into the project:

```bash
cd Netflix-Business-Case-Study
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
notebooks/Netflix_Business_Case_Study.ipynb
```

---

## 👨‍💻 Author

<div align="center">

**Shivaling** 🧑‍💻

*Data Science Enthusiast | Data Analytics*

📧 **Email**: shivalingb09@gmail.com  
🐙 **GitHub**: [Hazardous9hub](https://github.com/Hazardous9hub)  
💼 **LinkedIn**: [Shivaling Battarki](https://www.linkedin.com/in/shivaling-93000/)

</div>

### 🛠️ Skills Demonstrated

- ✅ Exploratory Data Analysis
- ✅ Data Cleaning
- ✅ Data Quality Analysis
- ✅ Missing Value Analysis
- ✅ Feature Engineering
- ✅ Data Visualization
- ✅ Categorical Analysis
- ✅ Business Analytics
- ✅ Insight Generation
- ✅ Business Recommendations

---

<div align="center">

## ⭐ Star This Project

If you found this analysis helpful or interesting, please consider giving it a star! It helps others discover the work and encourages me to create more content.

<div align="center">

[⭐ Star this Repo](https://github.com/Hazardous9hub/Aerofit-Treadmill-Business-Case-Study/stargazers)

**Made with ❤️ using Python**
</div>
