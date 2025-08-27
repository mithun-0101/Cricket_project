Title :: IPL Data Analysis Project (Analysis:2008–2024)


Overview:
>This project analyzes the Indian Premier League (IPL) dataset (2008–2024) using Python, Pandas, and Matplotlib.
>It focuses on player performance (batting & bowling) and team trends across seasons.
>The aim is to practice data cleaning, aggregation, and visualization using real-world sports data.

Tech Stack::
Python 3
Pandas, NumPy → data analysis
Matplotlib → data visualization
Jupyter Notebook (VS Code) → interactive exploration


Project Structure::


AIML_Cricproject/
│
├── data/
│   ├── matches.csv          # Match-level dataset
│   ├── deliveries.csv       # Ball-by-ball dataset
│
├── notebooks/
│   ├── IPL_Analysis.ipynb   # Main notebook (all analysis + charts)
│
└── README.md                # Project documentation


Features & Analysis::

Top Batsmen
Runs scored across seasons
Bar chart of top 10 run scorers
Top Bowlers
Wicket-takers (excluding run-outs)
Team Performance
Wins per season for each team
Example: Mumbai Indians’ win trend across years
Wins comparison for a specific season (e.g., 2019)

How to Run::

Clone the repo:

git clone https://github.com/mithun-0101/Cricket_project.git
cd AIML_Cricproject


Create a virtual environment & install dependencies:

python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate
pip install pandas numpy matplotlib jupyter


Open the notebook:
jupyter notebook notebooks/IPL_Analysis.ipynb


Run the cells to reproduce the analysis.
Sample Outputs
Top 10 Run Scorers (bar chart)
Top 10 Wicket Takers (bar chart)
Team wins per season (line graph / bar chart)

Future Work::

Add strike rate & batting averages
Add bowling economy & dot-ball %
Explore season-wise MVPs

>>Mainly to add the OpenCV touch to this project

:::>>>Built as a beginner-friendly data analysis project to explore IPL insights.
