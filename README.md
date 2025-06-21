# 🚆🌡️ Train Timetables & Climate Trends – R Visualization with ggplot2

This repository contains solutions for **Assignment 2**, a group project focused on visualizing train timetable data and long-term climate trends using **R**, **ggplot2**, and **Quarto**.

---

## 📚 Assignment Summary

This group assignment includes two major tasks:

1. **Creating a ggplot-based Marey-style visualization** of a train timetable
2. **Analyzing Uppsala’s long-term temperature records (1722–2022)** using time series visualization

---

## 🚄 Task 1 – Marey-style Train Timetable Visualization with ggplot2

Students analyze and recreate a timetable visualization inspired by Marey's 1885 Paris–Lyon train map.

![](https://i.imgur.com/1q8InSB.jpeg)

## 📝 Results:

![](https://i.imgur.com/fPK2fAK.png)

## Code below and assignment description (Swedish):

**Answers:**

![](https://i.imgur.com/OBY6I9N.png)
![](https://i.imgur.com/OBY6I9N.png)
![](https://i.imgur.com/mJMRgz5.png)
![](https://i.imgur.com/BLi9iOK.png)
![](https://i.imgur.com/fPK2fAK.png)

### Tasks include:

- Interpreting line **slopes** (positive/negative) and **steepness** (flat/sharp)
- Reconstructing a timetable for **regional trains (Norrtåg)** between Umeå and Örnsköldsvik
- Creating a numeric variable to represent station positions (e.g., 0–100 km scale)
- Using **ggplot2** to plot multiple daily trips (northbound and southbound) in one diagram

🧭 Coordinates and distances between stops must be respected to scale  
🎨 ggplot aesthetics (e.g., line grouping, labeling) are essential for readability

---

## 🌡️ Task 2 – Temperature Time Series Analysis (Uppsala 1722–2022)

## 📝 Results:

# (1) ![](https://i.imgur.com/a5R4BxP.png)
# (2) ![](https://i.imgur.com/u9R6F1C.png)

# (1) Code below and assignment description (Swedish): 

You will download and process a historical temperature dataset from SMHI covering **109,927 daily measurements**.
![](https://i.imgur.com/4vfjSjX.png)
![](https://i.imgur.com/R6sTPY8.png)
![](https://i.imgur.com/Cwf77GV.png)
![](https://i.imgur.com/Zi9qk5j.png)

# (2) Code below and assignment description (Swedish): 
![](https://i.imgur.com/B8fg8ou.png)
![](https://i.imgur.com/sIJ2n4c.png)

![](https://i.imgur.com/3b7V7dx.png)
![](https://i.imgur.com/SqoeAex.png)
![](https://i.imgur.com/TfFtw5J.png)


### Subtasks include:

- Calculating **annual average temperatures** (`Temp_korr`) from 1722–2022
- Creating a `Temp_diff` column comparing each year to the 301-year mean
- Plotting with **colored bars** (red = warmer, blue = colder) + `geom_smooth()` trend line
- Visualizing the difference between **1993–2022 vs. 1722–1992** monthly averages
- Analyzing whether warming is **evenly distributed across months**

📦 Libraries used: `dplyr`, `ggplot2`, `readr`

---

## 💡 Summary

This project bridges **transportation visualization** and **climate science** using `ggplot2`. Students apply structured, reproducible workflows in R to create meaningful graphics based on real-world and historical data.
