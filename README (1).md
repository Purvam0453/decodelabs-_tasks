# Data Cleaning Project

## About This Project

This was one of my first hands-on data projects where I worked on cleaning a messy real-world dataset. The raw data had a lot of issues — blank cells, repeated rows, inconsistent formatting — basically everything that makes analysis a nightmare. So I decided to clean it up properly before doing anything with it.

---

## What I Was Trying to Do

The main goal was simple — take a dirty dataset and make it usable. Sounds easy, but honestly it took more time than I expected. A few things I focused on:

- Getting rid of duplicate rows that were messing up the counts
- Filling in or removing missing values depending on the column
- Fixing date formats (some were DD/MM/YYYY, some MM-DD-YYYY — super inconsistent)
- Cleaning up text columns where some entries had extra spaces or wrong capitalization
- Making sure the final data actually made sense before calling it done

---

## Tools I Used

- **Microsoft Excel** — for most of the basic cleaning tasks
- **Python (Jupyter Notebook)** — for some of the more repetitive stuff that would've taken forever manually
- **SQL** — used a bit for filtering and checking duplicates

---

## Steps I Followed

**1. Handling Missing Values**  
First I went through each column and figured out which ones had blanks. For some columns I filled them with the median or mode, and for others where the missing data was too much, I just dropped those rows.

**2. Removing Duplicates**  
Used Excel's built-in duplicate removal first, then double-checked with Python to make sure nothing slipped through.

**3. Fixing Formats**  
This was honestly the most annoying part. Dates were all over the place. Spent a good amount of time standardizing everything into one consistent format.

**4. Sorting & Filtering**  
Once the data was clean, I sorted it properly and applied filters to do a final visual check.

**5. Validation**  
Did a final pass to catch anything I might've missed — checked for outliers, weird values, anything that looked off.

---

## Files in This Repo

| File | Description |
|------|-------------|
| `raw_dataset.xlsx` | Original data before cleaning |
| `cleaned_dataset.xlsx` | Final cleaned version |
| `data_cleaning.ipynb` | Jupyter notebook with Python steps |
| `README.md` | This file |

---

## What I Learned

Honestly, I underestimated how much work data cleaning actually is. A huge chunk of any data project is just getting the data into a state where you can actually work with it. A few things that really stuck with me:

- Always explore the data first before jumping into cleaning
- Document every change you make — future you will thank you
- Pandas makes repetitive cleaning tasks SO much faster
- Never assume the data is clean just because it came from a reliable source

---

## Results

After cleaning, the dataset went from 1,200+ rows (with a bunch of junk) to a reliable, consistent set that's ready for analysis. No more weird date formats, no duplicates, no random blank cells in critical columns.

---

## Author

**Purvam Nayak**  
Feel free to reach out if you have any questions about the project.
