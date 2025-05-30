#  News Sentiment Analysis – Task 1

This repository contains the setup and exploratory analysis for **Week 1 – Predicting Price Moves with News Sentiment** challenge. The focus is on configuring version control, setting up a Python development environment, automating CI/CD workflows, and performing Exploratory Data Analysis (EDA) on financial news headlines.


##  Project Structure


##  Objectives (Task 1)

 ✅ Setup Git and GitHub with proper branching.
 ✅ Establish a clean Python environment.
 ✅ Configure automated testing using GitHub Actions.
 ✅ Perform EDA on financial news data.


## Key Analyses Performed

### Descriptive Statistics
- Headline length distributions
- Article count per publisher
- Temporal trends in article frequency

### Text Analysis (Topic Modeling)
- Keyword extraction
- Topic identification using NLP

### Time Series Analysis
- News volume over time
- Publishing time patterns

### Publisher Analysis
- Top publishers by frequency
- Domain analysis of publisher emails



## Tech Stack

- Python 3.13
- Jupyter
- Pandas, NumPy, Seaborn, Matplotlib
- scikit-learn, NLTK
- Git, GitHub Actions


## Development Setup

# Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate (Windows)

# Install dependencies
pip install -r requirements.txt
