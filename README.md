# Job Market Hiring Trends EDA
 
An exploratory data analysis of 1,095 job postings across 6 categories (UI/UX, Data Scientist, Software Developer, HR, Business Analyst, Cloud), examining hiring patterns by workplace type, geography, department, and employment type.
 
## Business Question
 
Which job categories are more remote-friendly than others, where are companies concentrating their hiring geographically, and how do employment structures (department, contract type) differ across roles? This kind of analysis helps job seekers target roles/locations strategically and helps recruiters/analysts benchmark hiring trends across functions.
 
## Dataset
 
- **Source:** `job_data_cleaned.csv`
- **Size:** 1,095 job listings
- **Columns:** `Category`, `Workplace` (Remote/On-site/Hybrid/Not Specified), `Location` (City, Region, Country), `Department`, `Type` (Full Time/Contract/Part Time/Temporary/Other/Not Specified)
## Approach
 
1. **Cleaned** the data — standardized "Not Specified" values as missing, split `Location` into City/Region/Country
2. **Analyzed** category distribution, workplace type by category (cross-tabulation), top hiring countries/cities, department frequency, and employment type by category
3. **Visualized** findings with bar charts, a stacked bar comparison of workplace type by category, and a word cloud of hiring locations
4. **Tools used:** Python (pandas, matplotlib, wordcloud), Jupyter Notebook
## Key Findings
 
*(Replace these with your actual numbers once you've run the analysis — this is the section recruiters read first, so be specific.)*
 
- **Category distribution:** [e.g. "UI/UX and Data Scientist roles account for the largest share of postings, at X% and Y% respectively."]
- **Remote-friendliness by category:** [e.g. "Data Scientist roles are the most remote-friendly at X% Remote, compared to only Y% for HR roles."]
- **Geographic concentration:** [e.g. "The United States, United Kingdom, and India together account for X% of all postings; London is the single most common city."]
- **Employment type patterns:** [e.g. "Contract roles are notably more common in Cloud (X%) than in Business Analyst (Y%) postings."]
## Visuals
 
| Chart | Description |
|---|---|
| `category_distribution.png` | Job postings by category |
| `workplace_by_category.png` | Workplace type (Remote/On-site/Hybrid) by category |
| `top_countries.png` | Top 10 countries by job postings |
| `location_wordcloud.png` | Word cloud of hiring locations |
 
## Repository Structure
 
```
job_listing_data_cleanup/
├── job_listing_data_cleanup.ipynb   # full analysis notebook
├── job_data_cleaned.csv              # source dataset
├── category_distribution.png
├── workplace_by_category.png
├── top_countries.png
├── location_wordcloud.png
└── README.md
```
 
## How to Reproduce
 
```bash
pip install pandas numpy matplotlib wordcloud
jupyter notebook job_listing_data_cleanup.ipynb
```
Run all cells in order — the notebook loads the CSV, cleans it, and generates all charts.
 
## Conclusion
 
*(2-3 sentences tying the findings back to a real-world recommendation — e.g. "Job seekers prioritizing remote flexibility should focus on Data Scientist and Cloud roles, while those open to relocation may find the most opportunities concentrated in [top country/city].")*
 
