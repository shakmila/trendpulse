# TrendPulse - Part 1
## Python Foundations and Data Structures

### Project Overview
This project analyses YouTube trending videos
from three countries: GB, IN and US.

### Dataset
The dataset contains:
- GBvideos.csv
- INvideos.csv
- USvideos.csv
- categories.csv

Total records: 46,230

### Tools Used
- Python
- Google Colab
- Pandas

### Installation
Install dependencies using:

pip install -r requirements.txt

### How to Run
1. Open TrendPulse_Part1.ipynb in Google Colab.
2. Upload all four CSV files from the data folder.
3. Run the notebook cells from top to bottom.

### Data Cleaning
- Missing numeric values are replaced with 0.
- Missing Boolean values are replaced with False.
- Invalid dates are replaced with None.
- Records are retained.

### Classification Thresholds
- Viral Hit: 1 million or more views
  and like ratio >= 0.90
- Steady Performer: 100,000 or more views
  and like ratio >= 0.60
- Divisive: 100,000 or more views
  and like ratio < 0.60
- Low Engagement: Lower engagement
- Unrated: Ratings disabled or no ratings

### Data Structures
- List
- Dictionary
- Tuple
- Set
- Nested Dictionary

### Data Source
Public Trending YouTube Video Statistics dataset.
The dataset is publicly available on Kaggle.