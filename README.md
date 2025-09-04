# Data Analysis Assignments

## Assignment 1: IMDb TV Shows Analysis

This assignment focuses on exploring and analyzing the top 250 TV shows from the IMDb dataset.

### Tasks

1. **Read and Extract Data**
   - Read the `imdb_tv_250.csv` file.
   - Extract `title`, `year`, and `rating` for each TV show.
   - Store the results in a list of lists called `movies_lst`.

2. **Convert to Tuples**
   - Convert `movies_lst` into a list of tuples (`movies_tpl`) for better memory efficiency and data safety, as tuples are immutable.

3. **Show Information Function**
   - Define a function `show_info(rank)` that prints information about a show based on its rank.
   - Includes validation for invalid ranks.

4. **Sort by Year**
   - Sort all shows by year.
   - Print the 10 oldest TV shows from the dataset.

5. **Title Word Count**
   - Count and print how many TV shows have titles with more than 3 words.
   - **Result:** 43 shows.

6. **Bar Chart: Shows Released per Year**
   - Use Matplotlib to create a bar chart showing the number of TV shows released each year.

7. **Histogram: Ratings Distribution**
   - Prepare a histogram to visualize the distribution of TV show ratings.

---

## Assignment 2: Travel Data 2023 Analysis – AE2 Individual Project

This project involves analyzing traveler behaviors using a travel dataset.

### Key Steps

- Cleaned the dataset by handling missing values.
- Created a new metric: **expenditure per night**.
- Visualized spending patterns across:
  - Demographics
  - Countries
  - Travel purposes
- Extracted insights into typical traveler expenditures.
