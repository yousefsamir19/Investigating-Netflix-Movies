# 🎬 Netflix 1990s Movie Duration Analysis

This project performs **exploratory data analysis (EDA)** on the `netflix_data.csv` dataset to better understand **movies from the 1990s decade**.

---

## 🎯 Project Objectives

- ✅ Analyze Netflix movies released in the **1990s** (1990–1999).
- ✅ Determine the **most frequent movie duration** during that decade.
- ✅ Identify and count how many **short Action movies** (less than 90 minutes) were released.

---

## 📁 Files Included

- `netflix_data.csv`: Netflix titles dataset with columns like type, genre, duration, and release year.
- `netflix_1990s_analysis.py`: Python script containing all analysis and visualization code.
- `README.md`: This file, explaining the project purpose.

---

## 📊 Analysis Performed

1. **Filtered** the dataset to keep only:
   - Type: `"Movie"`
   - Release year between **1990 and 1999**
2. **Visualized** movie duration distribution using a histogram.
3. **Identified** the **most common movie duration** (approximate by viewing the histogram).
   - Saved this value as `duration`
4. **Filtered** movies by genre:
   - Selected `"Action"` genre
   - Further filtered to include only those **under 90 minutes**
5. **Counted** how many short action movies met the above conditions and saved the result as `short_movie_count`

---

## 📷 Visualization Example

A histogram shows the distribution of movie durations (X-axis: minutes, Y-axis: number of movies), helping estimate the most common duration in the 1990s.

---

## 🛠 Technologies Used

- numpy
- pandas
- matplotlib
