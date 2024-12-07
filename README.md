# Indian Election 2024 Analysis Project

## Overview
This project provides an in-depth analysis of the Indian Election 2024 results using Python and Power BI. By leveraging historical election data (2014 and 2019) and the latest 2024 election results, the project aims to uncover insights into voting patterns, party performances, and key metrics like victory margins.

## Features
- **Python Analysis (pandas, numpy, seaborn):**
  - Party-level and candidate-level performance analysis.
  - Victory margins, seats won, and vote distribution visualizations.
  - Comparative analysis of alliances (INDIA vs NDA).
- **Power BI Visualizations:**
  - Comprehensive dashboards for election data.
  - Interactive charts and maps for deeper insights.
- **Historical Data Integration:**
  - Results from the 2014 and 2019 elections for context and trend analysis.

## Folder Structure
```
Indian-Election-2024-Analysis-Project/
│
├── Indian election 2024 analysis project/
│   ├── Election_2024_analysis_using_python(pandas,numpy_&_seaborn).ipynb
│   ├── power bi/
│       ├── INDIA ELECTION.pbix
│       ├── data/
│           ├── 2024 result/
│           │   ├── INDIA alliance.csv
│           │   ├── NDA alliance.csv
│           │   ├── OVERALL FOR EACH PARTY 2024.csv
│           │   └── election_results_2024.csv
│           ├── images/
│           │   ├── Party_logo_data/
│           │   ├── background image/
│           │   └── party leader images/
│           ├── india_election_2014.csv
│           └── india_election_2019.csv
└── README.md
```

## Notebooks
### [Election_2024_analysis_using_python(pandas,numpy_&_seaborn).ipynb](Indian election 2024 analysis project/Election_2024_analysis_using_python(pandas,numpy_&_seaborn).ipynb)
This Jupyter Notebook includes:
1. **Data Import and Preprocessing**
   - Importing election datasets (2014, 2019, 2024).
   - Cleaning and organizing data.
2. **Analysis**
   - Party with the highest and lowest victory margins.
   - Seats won by each party.
   - Votes for key leaders like Narendra Modi, Rahul Gandhi, and Amit Shah.
   - Top trailing parties by votes and seats.
3. **Visualizations**
   - Bar charts, distribution plots, and other visual aids for election insights.

## Power BI Dashboard
### [INDIA ELECTION.pbix](Indian election 2024 analysis project/power bi/INDIA ELECTION.pbix)
This Power BI file includes:
- Interactive dashboards showcasing:
  - Victory margins by constituency.
  - State-wise performance.
  - Party and alliance-level seat and vote share.

## Datasets
1. **2024 Election Results**
   - `INDIA alliance.csv`: Seats won by INDIA alliance parties.
   - `NDA alliance.csv`: Seats won by NDA alliance parties.
   - `OVERALL FOR EACH PARTY 2024.csv`: Combined results for all parties.
   - `election_results_2024.csv`: Detailed constituency-level results.
2. **Historical Data**
   - `india_election_2014.csv`: Constituency-level data for 2014 elections.
   - `india_election_2019.csv`: Constituency-level data for 2019 elections.
3. **Images**
   - Party logos, background visuals, and leader photos for dashboards.

## How to Use
### Prerequisites
- **Python 3.8+**
- Libraries: pandas, numpy, seaborn, matplotlib, jupyter
- **Power BI Desktop** (for `.pbix` files)

### Steps
1. Clone the repository:
   ```bash
   git clone <repository-link>
   ```
2. Navigate to the project folder:
   ```bash
   cd Indian-Election-2024-Analysis-Project
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Indian election 2024 analysis project/Election_2024_analysis_using_python(pandas,numpy_&_seaborn).ipynb"
   ```
4. Explore the Power BI Dashboard:
   - Open `INDIA ELECTION.pbix` in Power BI Desktop.
   - Analyze interactive visualizations.

## Insights
1. **Party Performance**:
   - BJP secured the highest number of seats.
   - Congress showed significant improvements compared to 2019.
2. **Alliances**:
   - NDA outperformed INDIA alliance in margin of victories.
   - INDIA alliance gained a foothold in key constituencies.
3. **Vote Distribution**:
   - Detailed analysis of votes for top leaders.
   - Visualization of trailing parties in both votes and seats.

## Future Work
- Add predictive models for future elections based on historical trends.
- Integrate machine learning to predict key constituencies.
- Expand dashboards with real-time election updates.
