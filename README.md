# stock-sentiment-correlation-analysis
10 Academy Week 1 - Tasks
## Author : Amanuel Mandefrow


## Git and GitHub
Tasks: 
Setting up Python environment
Git version control 
CI/CD 
Key Performance Indicators (KPIs):
Dev Environment Setup.
Relevant skill in the area demonstrated.
Suggested folder structure:
```
├── .vscode/
│   └── settings.json
├── .github/
│   └── workflows
│       ├── unittests.yml
├── .gitignore
├── requirements.txt
├── README.md
├── src/
│   ├── __init__.py
├── notebooks/
│   ├── __init__.py
│   └── README.md
├── tests/
│   ├── __init__.py
└── scripts/
    ├── __init__.py
    └── README.md
```
Minimum Essential To Do
Create a github repository that you will be using to host all the code for this week.
Create at least one new branch called ”task-1” for your analysis
Commit your work at least three times a day with a descriptive commit message
Perform Exploratory Data Analysis (EDA) analysis on the following:
Descriptive Statistics:
Obtain basic statistics for textual lengths (like headline length).
Count the number of articles per publisher to identify which publishers are most active.
Analyze the publication dates to see trends over time, such as increased news frequency on particular days or during specific events.
Text Analysis(Sentiment analysis & Topic Modeling):
Perform sentiment analysis on headlines to gauge the sentiment (positive, negative, neutral) associated with the news.
Use natural language processing to identify common keywords or phrases, potentially extracting topics or significant events (like "FDA approval", "price target", etc.).
Time Series Analysis:
How does the publication frequency vary over time? Are there spikes in article publications related to specific market events?
Analysis of publishing times might reveal if there’s a specific time when most news is released, which could be crucial for traders and automated trading systems.
Publisher Analysis:
Which publishers contribute most to the news feed? Is there a difference in the type of news they report?
If email addresses are used as publisher names, identify unique domains to see if certain organizations contribute more frequently.

