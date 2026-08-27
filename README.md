\# 🎬 Netflix - Content Strategy \& Business Analytics



<div align="center">



!\[Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python\&logoColor=white)

!\[Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?logo=pandas\&logoColor=white)

!\[Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter\&logoColor=white)

!\[Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-pink?logo=python\&logoColor=white)

!\[Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4EAEAA?logo=python\&logoColor=white)

!\[NumPy](https://img.shields.io/badge/NumPy-Data%20Analysis-4DABCF?logo=numpy\&logoColor=white)



\*\*A Data-Driven Netflix Content Strategy Case Study using Python \& Exploratory Data Analysis\*\*



</div>



\---



\## 📋 Table of Contents



\- \[🎯 Project Overview](#-project-overview)

\- \[📊 Dataset](#-dataset)

\- \[🔍 Business Problem](#-business-problem)

\- \[❓ Business Questions](#-business-questions)

\- \[📈 Analysis](#-analysis)

\- \[💡 Key Findings](#-key-findings)

\- \[🎯 Business Recommendations](#-business-recommendations)

\- \[🛠️ Tech Stack](#️-tech-stack)

\- \[📁 Project Structure](#-project-structure)

\- \[🚀 How to Use](#-how-to-use)

\- \[👨‍💻 Author](#-author)

\- \[📄 License](#-license)



\---



\## 🎯 Project Overview



This project analyzes Netflix's catalogue of Movies and TV Shows to understand its content distribution, geographic reach, genres, ratings, creators and historical catalogue growth.



The objective is to use exploratory data analysis to generate insights that could support Netflix's content and market strategy.



\### 🎯 Business Objective



> Analyze the data and generate insights that could help Netflix decide which type of shows/movies to produce and how they can grow the business in different countries.



\---



\## 📊 Dataset



The dataset contains \*\*8,807 Netflix titles across 12 variables\*\*.



\### 📌 Dataset Features



| Feature | Description |

|---|---|

| `show\_id` | Unique identifier for the title |

| `type` | Movie or TV Show |

| `title` | Name of the title |

| `director` | Director(s) associated with the title |

| `cast` | Cast members |

| `country` | Country/countries associated with the title |

| `date\_added` | Date the title was added to Netflix |

| `release\_year` | Original release year |

| `rating` | Content rating |

| `duration` | Movie duration or TV Show seasons |

| `listed\_in` | Genre/category information |

| `description` | Description of the title |



\---



\## 🔍 Business Problem



Netflix has a large and diverse content catalogue spanning multiple countries, genres and content types.



The business challenge is to understand the composition of this catalogue and identify patterns that could help inform decisions around:



\- Content production

\- Genre strategy

\- Regional expansion

\- Movie vs TV Show investment

\- Audience targeting



\---



\## ❓ Business Questions



The analysis addresses questions such as:



1\. What is the distribution of Movies vs TV Shows?

2\. How has Netflix's catalogue changed over time?

3\. Which countries contribute the most content?

4\. Which genres are most represented?

5\. Which ratings dominate the catalogue?

6\. Which directors and actors appear most frequently?

7\. How does content type vary across countries?

8\. When are titles most frequently added to Netflix?

9\. How does the catalogue differ between Movies and TV Shows?



\---



\## 📈 Analysis



The project follows a structured Exploratory Data Analysis workflow:



```text

Business Understanding

&#x20;       ↓

Data Loading

&#x20;       ↓

Data Understanding

&#x20;       ↓

Data Quality Checks

&#x20;       ↓

Data Cleaning

&#x20;       ↓

Feature Engineering

&#x20;       ↓

Exploratory Data Analysis

&#x20;       ↓

Univariate Analysis

&#x20;       ↓

Bivariate Analysis

&#x20;       ↓

Multivariate Analysis

&#x20;       ↓

Business Insights

&#x20;       ↓

Recommendations

🔬 Analysis Areas

Dataset structure and data types

Missing-value analysis

Duplicate analysis

Movie vs TV Show distribution

Release-year analysis

Catalogue additions over time

Ratings analysis

Country analysis

Genre analysis

Director analysis

Cast analysis

Country × Content Type analysis

💡 Key Findings



The case-study analysis identifies several notable patterns:



🎬 Content Mix



The dataset contains:



6,131 Movies

2,676 TV Shows



Movies therefore represent the larger share of the catalogue in this dataset.



🌍 Geographic Distribution



After preprocessing the country field, the analysis identifies content associated with 124 countries.



The United States and India are among the largest contributors to the catalogue.



🎭 Genre Distribution



Major categories represented in the catalogue include:



International Movies

Dramas

Comedies

International TV Shows

Documentaries

🔞 Ratings



TV-MA is identified as the most common rating in the analysed catalogue.



📅 Catalogue Growth



The historical date\_added analysis shows substantial catalogue expansion during the late 2010s, with 2019 identified as a peak year in the case-study analysis.



⚠️ Analytical Note



This dataset describes Netflix's content catalogue, not individual user behaviour.



Therefore, catalogue frequency should not automatically be interpreted as viewer preference.



For example:



A genre appearing frequently indicates strong catalogue representation, but does not directly prove that viewers prefer that genre.



Viewer-level variables such as:



Watch time

Completion rate

Engagement

Retention

Churn

Subscriber behaviour



would be required to make stronger conclusions about audience demand.



🎯 Business Recommendations

🎬 Content Strategy

Maintain a balanced portfolio of Movies and TV Shows.

Continue evaluating opportunities in high-representation genres.

Identify catalogue gaps by country and genre.

Consider localized content strategies for regional markets.

🌍 Geographic Strategy

Evaluate country-level catalogue representation when considering regional expansion.

Combine country, genre and content-type information rather than relying on a single metric.

Explore opportunities for localized production in underrepresented markets.

📊 Data-Driven Decision Making



For future strategic decisions, catalogue analysis should ideally be combined with:



Viewing behaviour

Subscriber growth

Watch time

Retention

Completion rate

Content-level engagement

🛠️ Tech Stack

├── 🐍 Python

├── 📊 Pandas

├── 🔢 NumPy

├── 📈 Matplotlib

├── 🎨 Seaborn

├── 📓 Jupyter Notebook

└── 🔬 Exploratory Data Analysis

📁 Project Structure

Netflix-Business-Case-Study/

│

├── data/

│   └── netflix\_titles.csv

│

├── notebooks/

│   └── Netflix\_Business\_Case\_Study.ipynb

│

├── reports/

│   └── SHIVALING\_NETFLIX Business Case Study.pdf

│

├── src/

│

├── .gitignore

├── .gitattributes

├── requirements.txt

├── README.md

└── LICENSE

🚀 How to Use

Option 1 — View the Project



Explore the repository files directly on GitHub:



📓 Python Notebook — complete analysis

📊 Dataset — Netflix catalogue data

📄 PDF Report — case-study report

Option 2 — Run Locally



Clone the repository:



git clone https://github.com/Hazardous9hub/Netflix-Business-Case-Study.git



Navigate into the project:



cd Netflix-Business-Case-Study



Install dependencies:



pip install -r requirements.txt



Launch Jupyter:



jupyter notebook



Open:



notebooks/Netflix\_Business\_Case\_Study.ipynb

👨‍💻 Author

<div align="center">



Shivaling 🧑‍💻



Data Analytics | Data Science Enthusiast



🐙 GitHub: Hazardous9hub



💼 LinkedIn: Shivaling Battarki



</div>

🛠️ Skills Demonstrated

✅ Exploratory Data Analysis

✅ Data Cleaning

✅ Missing Value Analysis

✅ Feature Engineering

✅ Data Visualization

✅ Categorical Analysis

✅ Business Analytics

✅ Insight Generation

✅ Business Recommendations

📄 License



This project is licensed under the MIT License.



<div align="center">



⭐ If you find this project useful, consider starring the repository.



Made with ❤️ using Python \& Data Analytics



</div> ```



