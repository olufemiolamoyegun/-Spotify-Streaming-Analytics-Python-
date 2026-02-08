Spotify Streaming Analytics
Description

This repository contains a product and growth analytics project analyzing music streaming behavior using a synthetic Spotify-style dataset. The analysis focuses on track popularity, audio features, and listener engagement to generate data-driven insights that support product and playlist optimization decisions.

The dataset is synthetic and created strictly for portfolio and educational purposes.

Dataset

File: Spotify_Tracks_Synthetic.csv

Records: 5,000+ tracks

Type: Synthetic, non-Kaggle, portfolio-safe

Key Columns

streams

popularity

danceability

energy

tempo

duration_ms

Objectives

Identify factors influencing track popularity

Analyze relationships between audio features and listener engagement

Understand distribution patterns typical of streaming platforms

Tools & Libraries

Python

Pandas

NumPy

Matplotlib

Seaborn

Analysis Overview

The analysis includes:

Data validation and cleaning

Exploratory Data Analysis (EDA)

Distribution analysis of streams and popularity

Correlation analysis between audio features and engagement metrics

Identification of high-performing track profiles

Key Findings

Higher energy and danceability are positively correlated with increased streams

Extremely long track durations are associated with lower listener engagement

Track popularity follows a long-tail distribution common in digital content platforms

Business Use Cases

Playlist optimization based on high-engagement audio features

Data-informed music promotion strategies

Support for experimentation and A/B testing in playlist curation

Project Structure
.
├── Spotify_Tracks_Synthetic.csv
├── spotify_analysis.ipynb
├── README.md
└── visualizations/

How to Run

Clone the repository

Install required Python libraries

Open the notebook and run all cells

pip install pandas numpy matplotlib seaborn

Author

Olufemi Olamoyegun
Data Analyst | Python | Product & Growth Analytics
