# Netflix Data Analysis: Global Expansion Strategy (Team 06, ITI 545)

Final Jupyter Notebook submission for the Netflix Project Assignment.

**Challenge chosen:** Challenge 2 - Global Expansion Strategy
**Business question:** Which countries contribute the most content to Netflix, and where could Netflix expand next?

## Repository
GitHub: https://github.com/vishwasgowda1/Netflix-team-06-ITI-545-

## Files
| File | Description |
| --- | --- |
| `Netflix_Challenge2_Global_Expansion.ipynb` | Main notebook: load, clean, EDA, 4 visualizations, insights, conclusions |
| `Netflix_Challenge2_Global_Expansion.html` | Exported, self-contained HTML version of the executed notebook |
| `netflix_catalog.csv` | Dataset (40 titles, 9 columns) |

## How to run
1. Install Python 3.9+ and the libraries: `pip install pandas matplotlib jupyter`
2. Keep `netflix_catalog.csv` in the same folder as the notebook.
3. Open the notebook with `jupyter notebook` and choose **Kernel > Restart & Run All**.

## Workflow in the notebook
1. Load and inspect the dataset
2. Clean the data (placeholder row, duplicate title, inconsistent genre labels, missing values)
3. Exploratory data analysis by country
4. Four labeled visualizations (titles by country, rating by country, movie/TV mix, volume vs quality)
5. Expansion analysis with a rule-based candidate list
6. Five business insights and a conclusions section

## Key findings
- The United States provides about 49% of titles with a known country; the US and UK together about 65%.
- Non-US titles average a rating of 7.97 vs 7.64 for US titles.
- India and Germany are the clearest expansion candidates (small footprint, above-average ratings).
- TV series are the strongest format outside the US.

## Limitations
The dataset has only 40 rows, so results are directional and not representative of Netflix's full catalog.

## Version control
Commit the notebook, HTML export, CSV and this README to the repository above, for example:
`git add . && git commit -m "Add final notebook, export and README" && git push`
