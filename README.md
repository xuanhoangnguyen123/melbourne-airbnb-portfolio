# Melbourne Airbnb Data Cleaning and Exploration

RMIT University coursework using Python, pandas and Matplotlib. The notebook cleans Melbourne listing data, compares prices by room type and neighbourhood, and plots the geographic distribution of listings.

- Filled missing minimum-night values with the median, removed rows missing review counts and deduplicated listing IDs.
- Standardised room-type labels and corrected invalid availability and latitude values.
- Produced 10,040 cleaned records with unique listing IDs.

## Run the notebook

Install the packages with `python -m pip install -r requirements.txt`. Start Jupyter with `jupyter notebook`, open `melbourne_airbnb.ipynb` and run all cells from the project folder.

`airbnb_input.csv` contains real coursework records with listing titles, host names and host IDs omitted. The source supplied for this coursework was named `A1data.csv`. The notebook writes `airbnb_cleaned.csv`, which was checked against the original cleaned coursework file for all retained columns.
