🎧 Spotify Audio DNA — Descriptive Analysis

Statistical analysis of audio features in popular Spotify tracks





📌 Project Overview

This project explores the audio characteristics of Spotify tracks using descriptive statistics and visual analysis.

The goal is to understand patterns in features such as Energy, Valence, Acousticness, Loudness, Key, and Duration and turn those patterns into simple insights that can be useful for music analysis and playlist curation.

The analysis focuses on three areas:

Central tendency

Variation and skewness

Correlation between audio features

📂 Dataset

Source: Spotify Tracks Dataset via Hugging Face

Sample Size: 3,000 tracks

Main Features: Energy, Valence, Acousticness, Loudness, Key, and Duration

⚙️ Analysis Process

1. Central Tendency

The first part of the analysis looks at the typical values of the main audio features.

Histograms were used for continuous variables such as Energy, Valence, and Acousticness, while a column chart was used for Key.

Key Results

Feature

Mean

Median

Mode

Valence

0.46

0.45

N/A

Energy

0.79

0.82

N/A

Acousticness

0.15

0.04

N/A

Key

5.25

5.00

1 (C♯/D♭)

Visualizations

<p align="center">
  <img src="Distribution of Valence.png" width="45%" />
  <img src="Distribution of Energy.png" width="45%" />
  <img src="Distribution of Acousticness.png" width="45%" />
  <img src="Distribution of Key.png" width="45%" />
</p>

2. Variation & Skewness

The second part measures how consistent or varied the audio features are.

Feature

Standard Deviation

Skewness

Observation

Valence

0.2272

0.0250

Balanced

Energy

0.1825

-0.6298

Higher-energy tracks are more common

Acousticness

0.2400

1.4000

Acoustic tracks are less common

Key Findings

Energy: The distribution is concentrated toward higher energy values.

Valence: The distribution is close to symmetrical, showing variety in the mood of popular tracks.

Acousticness: The positive skew indicates that highly acoustic tracks are less common in this dataset.

3. Correlation Analysis

The final part examines relationships between different audio features using Pearson correlation.

Feature Pair

Correlation (r)

Relationship

Loudness vs. Energy

0.70

Strong positive

Acousticness vs. Energy

-0.61

Moderate negative

Duration vs. Energy

0.02

Very weak / almost none

Visualizations

<p align="center">
  <img src="Loudness vs Energy.png" width="45%" />
  <img src="Acousticness vs Energy.png" width="45%" />
  <img src="Duration vs Energy.png" width="45%" />
</p>

Key Findings

Loudness and Energy: A strong positive correlation suggests that louder tracks in this dataset also tend to have higher energy values.

Acousticness and Energy: The negative correlation shows that more acoustic tracks tend to have lower energy values.

Duration and Energy: The correlation is close to zero, indicating little relationship between track duration and energy.

Note: Correlation shows association between variables; it does not by itself prove causation.

📊 Statistical Methods Used

Mean

Median

Mode

Standard Deviation

Skewness

Pearson Correlation

Google Sheets Functions

AVERAGE()

MEDIAN()

MODE()

STDEV()

SKEW()

CORREL()

🛠️ Tools & Skills

Google Sheets

Descriptive Statistics

Data Cleaning & Exploration

Data Visualization

Statistical Analysis

Data Storytelling

Business-oriented Data Analysis

💡 Business Insights

Based on the analysis:

Higher-energy tracks are strongly represented in the dataset.

Loudness has a strong positive relationship with Energy.

Acousticness has a negative relationship with Energy.

Track Duration shows almost no relationship with Energy.

Valence is relatively balanced, suggesting that popular tracks can cover a broad range of moods.

These observations can be useful when exploring playlist composition and audio-feature trends.

📁 Project Files

Spotify-Audio-DNA-Descriptive-Analysis/
│
├── README.md
├── spotify-tracks-dataset - Data.csv
│
├── Acousticness vs Energy.png
├── Distribution of Acousticness.png
├── Distribution of Energy.png
├── Distribution of Key.png
├── Distribution of Valence.png
├── Duration vs Energy.png
└── Loudness vs Energy.png

👤 Author

Aashish Kumar Jha

B.Tech CSE — Artificial Intelligence & Machine Learning

Interested in Data Analytics, Data Science, SQL, Power BI, Python, and Machine Learning
