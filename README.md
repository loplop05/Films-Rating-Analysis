# 🎬 Films Rating Analysis

An exploratory data analysis project investigating whether **Fandango inflates movie ratings** compared to other review platforms — replicating and extending the findings of FiveThirtyEight's famous study.

---

## 📌 Overview

This project analyzes film ratings across multiple platforms to detect discrepancies and potential bias in how movies are scored. Using real-world scraped data from Fandango and aggregated scores from other major review sites, the analysis uncovers meaningful differences in how ratings are displayed vs. what users actually voted.

---

## 📂 Repository Structure
```
Films-Rating-Analysis/
│
├── Solutions.ipynb           # Main analysis notebook (EDA, visualizations, conclusions)
├── all_sites_scores.csv      # Aggregated ratings from multiple review platforms
├── fandango_scrape.csv       # Scraped Fandango ratings and star display data
└── README.md                 # Project documentation
```

---

## 🔍 Key Questions Explored

- Does Fandango display higher star ratings than users actually voted?
- How do Fandango ratings compare to IMDb, Rotten Tomatoes, and Metacritic?
- Is there a systematic rounding-up bias in Fandango's displayed scores?
- Which platform gives the most "honest" representation of film quality?

---

## 📊 Datasets

| File | Description |
|------|-------------|
| `fandango_scrape.csv` | Scraped Fandango ratings including displayed stars vs. actual vote scores |
| `all_sites_scores.csv` | Compiled ratings from Fandango, IMDb, Rotten Tomatoes, and Metacritic |

> Data sourced from [FiveThirtyEight's public dataset](https://github.com/fivethirtyeight/data/tree/master/fandango), originally collected by Walt Hickey.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python 3 | Core programming language |
| Pandas | Data loading, cleaning, and manipulation |
| Matplotlib | Plotting and visualization |
| Seaborn | Statistical data visualization |
| Jupyter Notebook | Interactive analysis environment |
| NumPy | Numerical computations |

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab

### Installation
```bash
# Clone the repository
git clone https://github.com/loplop05/Films-Rating-Analysis.git
cd Films-Rating-Analysis

# Install dependencies
pip install pandas matplotlib seaborn numpy jupyter
```

### Run the Notebook
```bash
jupyter notebook Solutions.ipynb
```

---

## 📈 Key Findings

- Fandango consistently **rounds up** displayed star ratings compared to the actual user vote average.
- Fandango's ratings skew noticeably **higher** than those of Rotten Tomatoes, Metacritic, and IMDb for the same films.
- The gap between Fandango's displayed stars and true vote scores suggests a **systematic inflation bias** — potentially driven by its role as a ticket-selling platform.

---

## 📚 Background

This project is inspired by the [FiveThirtyEight investigation](https://fivethirtyeight.com/features/fandango-movies-ratings/) by Walt Hickey, which found that Fandango's rating system was inflated, calling into question the integrity of review scores on platforms with commercial interests in ticket sales.

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**loplop05**  
[GitHub Profile](https://github.com/loplop05)
