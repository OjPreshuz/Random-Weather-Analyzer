# 🌦️ Random Weather Analyzer

This project simulates and analyzes weather data using only **NumPy** — without relying on pandas or external APIs. It's a beginner-friendly data analysis project designed to reinforce core NumPy skills, including array manipulation, statistical analysis, and data saving to `.txt`.

---

## 📌 Project Overview

The **Random Weather Analyzer** performs the following tasks:

- Generates simulated temperature and humidity data.
- Calculates key weather statistics like average, max, and min values.
- Identifies hot days and dry days based on defined thresholds.
- Computes the percentage of such days.
- Saves the analyzed data into a `.txt` file in CSV format.

---

## 🔍 Features

- ✅ Synthetic temperature data based on a normal distribution.
- ✅ Synthetic humidity data using a uniform distribution.
- ✅ Hot day detection: temperature > 35°C.
- ✅ Dry day detection: humidity < 50%.
- ✅ Summary statistics (mean, min, max).
- ✅ Data export to `.txt` (CSV-like) format.

---

## 🧪 Dataset Info

Although no real weather data is used here, the project simulates:

- **30 days** of temperature readings with:
  - Mean = 30°C
  - Standard deviation = 5°C

- **30 days** of humidity readings:
  - Ranges from 40% to 90%

---

## 🧾 Code Structure

- **Cell 1**: Generates random weather data
- **Cell 2**: Prints average, min, and max for both temperature and humidity
- **Cell 3**: Counts and calculates the percentage of hot/dry days
- **Cell 4**: Saves the data to a `.txt` file in CSV format

---

## 🧑‍💻 How to Run

1. Open the notebook: `random_weather_analyzer.ipynb`  
2. Run each cell sequentially.
3. The output will show statistics and generate a file named:
   - `random_weather_analyzer.txt`

---

## 📊 Sample Output

