# 📚 Book Dataset Analysis Project

This project performs a comprehensive analysis of a book recommendation dataset using R. The goal is to explore user behavior, rating patterns, and book popularity across different demographics such as age, country, and publication year.

---

## 🔍 Project Overview

This project answers four analytical questions based on book ratings provided by users:

1. **Publisher Analysis**:  
   Calculate and visualize the average book rating for each publisher, focusing on younger users (under 30). Identify the top publishers with the highest and most frequent ratings.

2. **User Age Group Distribution**:  
   Analyze how book ratings vary by different age groups (e.g., 0–18, 19–30, etc.) using boxplots and summary statistics.

3. **Country-wise Rating Comparison**:  
   Compare how average ratings differ between countries, split by users under and over 30 years of age.

4. **Impact of Publication Year**:  
   Explore the relationship between user age and book ratings for books published after the year 2000. Compare patterns in two randomized subsets of the data.

---

## 🗂️ Dataset Information

- `Books.csv` – Contains book metadata such as title, author, publisher, and year of publication.
- `Ratings.csv` – Contains user IDs, book ISBNs, and their corresponding ratings.
- `Users.csv` – Includes demographic details of users such as age and location.

---

## 🧰 Tools & Libraries Used

- **R** and **R Markdown** for analysis and reporting
- **Libraries**: `dplyr`, `ggplot2`, `kableExtra`, `httr`, `tidyr`
- **Visualization**: Boxplots, bar charts, violin plots using `ggplot2`

---

## 🧪 How to Run

1. Open the `.Rmd` file in **RStudio**.
2. Make sure the `Books.csv`, `Ratings.csv`, and `Users.csv` are available and paths are correct.
3. Click on **Knit** to generate HTML, PDF, or Word output.
4. Review each section of the report for the respective question analysis.

---

## 📈 Output Examples

- Bar charts of top publishers by average rating  
- Boxplots showing rating spread across age groups  
- Side-by-side bar charts comparing average ratings by age and publication year  

---

## 👤 Author

- **Name**: Nabin B K  
- **Date**: May 2025  
- **Course**: Data Science

---

## 📄 License

This project is for educational and academic purposes.

# Book Dataset Analysis

This project analyzes a book dataset using R. It includes:
- Data cleaning and preprocessing
- Statistical analysis of book ratings by age and country
- Visualization of insights
- Use of `dplyr`, `ggplot2`, and base R

## Files
- `Books.csv`, `Ratings.csv`, `Users.csv`: Input datasets
- `Book Analysis.Rmd`: R Markdown file with all analysis and visualizations

## How to run
Open the Rmd file in RStudio and knit it to view the report.

## Author
Nabin B K

