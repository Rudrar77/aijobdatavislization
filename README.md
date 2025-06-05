# AI Job Data Visualization

This project performs an in-depth exploratory data analysis and visualization of AI job market data using Python libraries such as Pandas, Matplotlib, and Seaborn. The dataset includes job listings with salary, experience level, company information, remote work data, required skills, and geographic locations.

---

## Project Description

The analysis focuses on uncovering trends and insights from the AI job market dataset, including:

* **Salary distribution by experience level**
* **Relationship between years of experience and salary**
* **Top industries by average salary**
* **Remote work trends by industry and company size**
* **Comparison of on-site vs remote jobs**
* **Most in-demand AI skills and their average salaries**
* **Job posting trends over time**
* **Salary and benefits by company size**
* **Top job posting locations and salary variations by location**
* **Heatmap of average salary by industry and location**

All steps are implemented in a Jupyter Notebook for interactive exploration.

---

## Dataset

* Contains 15,000+ AI job postings from over 50 countries
* Fields include salary (USD), experience level, company size, remote work ratio, posting date, skills, and location

---

## Installation & Setup

### Requirements

* Python 3.6 or higher
* Jupyter Notebook

### Install dependencies

```bash
pip install pandas matplotlib seaborn numpy
```

### Running the notebook

1. Clone this repository:

```bash
git clone https://github.com/Rudrar77/aijobdatavislization.git
cd aijobdatavislization
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook
```

3. Open the notebook file (e.g. `AI_Job_Data_Visualization.ipynb`) and run cells sequentially.

---

## Code Highlights

* **Data loading and cleaning:** Handles missing values, date parsing, and numeric conversions.
* **Visualizations:** Includes boxplots, lineplots, bar charts, pie charts, and heatmaps to represent key metrics visually.
* **Skill analysis:** Extracts and counts required skills, showing top 20 demanded skills and corresponding average salaries.
* **Trend analysis:** Tracks job postings over time and compares salary/benefits by company size and location.

---

## Project Structure

* `aijob.csv` — Dataset containing AI job listings
* `AI_Job_Data_Visualization.ipynb` — Jupyter Notebook with all analysis and visualizations

---

## License

This project is licensed under the MIT License.

---

