# Task 1 – Data Cleaning and Preprocessing

---

## Dataset Used

Netflix Movies and TV Shows

---

## 📌 Objective

The goal of this task was to clean and preprocess a raw dataset by handling missing values, removing duplicates, standardizing formats, and preparing it for analysis.

Dataset used: **Netflix Movies and TV Shows**

---

## 🛠 Steps Performed

1. **Handled Missing Values**

   * `director`, `cast`, `country`, `date_added`, `rating`, `duration` → filled missing with `"Unknown"` or `"Not Rated"`.

2. **Removed Duplicates**

   * Checked for duplicate rows → none found, but ensured dataset is unique.

3. **Standardized Text Values**

   * Made `type` values consistent (`Movie` / `TV Show`).
   * Trimmed spaces in `country`.

4. **Converted Date Formats**

   * `date_added` column converted to **dd-mm-yyyy** format.
   * Rows with no date marked as `"Unknown"`.

5. **Renamed Column Headers**

   * Converted all column names to **lowercase with underscores**.
   * Example: `listed_in` → `listed_in`, `date_added` → `date_added`.

6. **Checked and Fixed Data Types**

   * `release_year` → Integer.
   * `date_added` → Date (formatted).

---

## 📊 Final Cleaned Dataset Columns

* `show_id`
* `type`
* `title`
* `director`
* `cast`
* `country`
* `date_added`
* `release_year`
* `rating`
* `duration`
* `listed_in`
* `description`

---

## ✅ Deliverables

* **Cleaned Dataset:** `netflix_titles_cleaned.csv`
* **Process Documentation:** This README file

---

⚡ This task gave me hands-on experience with **data cleaning and preprocessing**, which is a critical step before data analysis and visualization.

---
