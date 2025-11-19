# Canteen Satisfaction Analysis

<table>
  <tr>
    <td align="center" width="100%">
      <!-- Ganti link gambar di bawah ini dengan plot hero kamu -->
      <img width="100%" alt="hero-plot" src="https://via.placeholder.com/1200x400?text=Canteen+Satisfaction+Analysis">
    </td>
  </tr>
</table>

Canteen Satisfaction Analysis is a data-driven project that explores students' perceptions of the university canteen.  
Using R and statistical analysis, this project identifies key satisfaction indicators, visualizes trends, and provides actionable recommendations to enhance service quality, menu variety, pricing, and overall experience.

<br>

## Developer
Defa Danuarta (Data Analyst & Computer Science Student)  
<br>

## Built Time
This project was developed over several days as part of a data analysis learning initiative.  
<br>

---

## Features & Scripts

<table>
  <tr>
    <th>Main Scripts</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><b><code>01_cleaning.R</code></b></td>
    <td>Data cleaning, handling missing values, factor encoding, and initial preprocessing.</td>
  </tr>
  <tr>
    <td><b><code>02_exploration.R</code></b></td>
    <td>Exploratory Data Analysis (EDA), summarizing satisfaction categories, descriptive statistics.</td>
  </tr>
  <tr>
    <td><b><code>03_visualization.R</code></b></td>
    <td>Generating bar charts, segmented plots, and comparison visuals using ggplot2.</td>
  </tr>
  <tr>
    <td><b><code>04_recommendation.R</code></b></td>
    <td>Rule-based recommendation system that identifies improvement areas with lowest satisfaction scores.</td>
  </tr>
</table>

---

## Files description
```
├── .RData                                                     # Environment data saved by R
├── .Rhistory                                                  # Command history from RStudio
├── .gitignore                                                 # Ignore temporary RStudio files
│
├── questionaire_result.xlsx                                   # Original questionnaire result (raw data)
│
├── 1st_cleaned_mutated_questionnaire_results.csv              # Cleaned + mutated version
├── 2nd_encoded_questionnaire_results.csv                      # Encoded Likert categories
├── 3rd_avg_scores_added_questionnaire_results.csv             # Added average satisfaction scores
├── 4th_binning_scores_added_questionnaire_results.csv         # Binned satisfaction categories
├── 5th_grouped_major_added_questionnaire_results.csv          # Grouping by major and additional features
│
├── Canteen Satisfaction.Rmd                                   # Main analysis file (R Markdown)
├── Canteen-Satisfaction.html                                  # Exported HTML report
│
├── LICENSE                                                    # Project license
└── README.md                                                  # Documentation
```

