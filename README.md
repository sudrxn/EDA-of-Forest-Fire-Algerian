# 🔥 EDA of Forest Fire in Algeria

This project presents an in-depth **Exploratory Data Analysis (EDA)** of forest fire incidents in Algeria, aimed at understanding environmental and meteorological factors that influence wildfire occurrences. Using Python-based tools, this analysis uncovers patterns and correlations that can aid in fire prediction and prevention efforts.

📍 **Dataset Region**: Algeria's forest zones (Bejaia and Sidi Bel-Abbes)  
📁 **Source**: [UCI Machine Learning Repository - Algerian Forest Fires Dataset](https://archive.ics.uci.edu/ml/datasets/Algerian+Forest+Fires+Dataset)

---

## 📌 Objective

The primary goal of this EDA is to:

- Understand the relationship between meteorological variables and forest fires.
- Explore seasonal patterns and fire-prone days.
- Visualize and interpret data to extract meaningful insights.

---

## 🧰 Tools & Libraries Used

- **Pandas** – for data loading and preprocessing  
- **NumPy** – for numerical operations  
- **Matplotlib & Seaborn** – for data visualization  
- **DateTime & Regex** – for date formatting and parsing  

---

## 📊 Key Steps & Insights

✔️ **Data Cleaning**  
- Combined and structured two separate region datasets  
- Removed nulls, handled anomalies, and formatted dates  

✔️ **Feature Engineering**  
- Extracted `day`, `month`, and `season` from the date  
- Created binary classification for `Fire` vs. `No Fire` days  

✔️ **Visualization & Analysis**  
- Heatmaps showing correlation between temperature, wind, humidity, etc.  
- Bar and line plots comparing fire vs. non-fire days  
- Region-wise fire trends and seasonal spikes  
- Observed that **June to September** show maximum fire activity  

---

## 📌 Columns in Dataset

- **Temperature**, **RH (Relative Humidity)**, **Ws (Wind speed)**  
- **Rain**, **FFMC**, **DMC**, **DC**, **ISI** (Fire indices)  
- **BUI**, **FWI** – standard fire weather indexes  
- **Classes** – Binary flag: `fire` / `not fire`

---

## 📦 How to Run

1. Clone the repository:
```bash
git clone https://github.com/sudrxn/EDA-of-Forest-Fire-Algerian.git
cd EDA-of-Forest-Fire-Algerian
````

2. Open the Jupyter notebook:

* Run it on **Jupyter Notebook** or **Google Colab**

3. Make sure required libraries are installed:

```bash
pip install pandas numpy matplotlib seaborn
```

---

## 🌱 Insights & Applications

* Fire activity can be predicted using a combination of **temperature**, **humidity**, and **wind speed**.
* **Prevention strategies** should focus on high-risk periods (mid-year dry months).
* Can be used as a baseline for developing a machine learning model for fire detection.

---

## 👨‍💻 About Me

I'm **Sudershan sharma** – a B.Tech AI & Data Science graduate passionate about data analysis and predictive modeling.
🔗 GitHub: [sudrxn](https://github.com/sudrxn)
📫 Email: [sudarshansharmahere@gmail.com](mailto:sudarshansharmahere@gmail.com)

---

## ⭐ Like the project? Give it a star and follow for more data science content!

```

---

Let me know if you’d like to turn this into a full **multi-page portfolio** or if you want a version with screenshots and visual output previews.
```
