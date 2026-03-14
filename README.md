# Netflix_Data_Analysis
it helps to analyse movies 
# 🎬 Netflix Data Analysis

Exploratory Data Analysis (EDA) of a Netflix movies dataset to uncover trends in genres, popularity, ratings, and release patterns using Python and interactive visualizations.

---

## 📌 Project Overview

This project performs a comprehensive analysis of Netflix movie data sourced from TMDB (The Movie Database). It explores various aspects of the dataset — from genre distributions to popularity trends — and draws meaningful insights about what types of content resonate most with audiences.

---

## 📂 Project Structure

```
Netflix-Data-Analysis/
│
├── Netflix_Data_Analysis.ipynb   # Main Jupyter Notebook with full EDA
├── NetflixData.csv               # Dataset used for analysis
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```

---

## 📊 Dataset

The dataset (`NetflixData.csv`) contains information about Netflix movies with the following columns:

| Column | Description |
|---|---|
| `Release_Date` | Date the movie was released |
| `Title` | Movie title |
| `Overview` | Short description of the movie |
| `Popularity` | Popularity score from TMDB |
| `Vote_Count` | Number of user votes |
| `Vote_Average` | Average user rating |
| `Original_Language` | Language the movie was originally made in |
| `Genre` | Genre(s) associated with the movie |
| `Poster_Url` | URL to the movie poster image |

---

## 🔍 Analysis Performed

- **Data Loading & Preview** — Loading the dataset and inspecting its structure
- **Data Cleaning** — Handling missing values and data type conversions
- **Genre Analysis** — Most frequent genres on Netflix
- **Popularity Analysis** — Most popular movies and genre-wise popularity comparison
- **Vote & Rating Analysis** — Distribution of ratings and vote counts
- **Release Year Trends** — How movie releases have grown over time
- **Language Distribution** — Breakdown of movies by original language

---

## 💡 Key Insights

- **Drama** is the most frequently occurring genre in the dataset.
- **Adventure** movies have the highest average popularity score.
- **Action** and **Science Fiction** also attract strong audience engagement.
- Movie releases increased significantly **after the year 2000**, reflecting the rapid growth of streaming platforms.
- The popularity distribution is **highly skewed** — most movies are average, while only a few become blockbuster hits.

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Pandas** — Data manipulation and analysis
- **Plotly Express** — Interactive visualizations
- **Jupyter Notebook** — Development environment

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Netflix-Data-Analysis.git
cd Netflix-Data-Analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch the notebook

```bash
jupyter notebook Netflix_Data_Analysis.ipynb
```

> **Note:** If you're using Google Colab, upload `NetflixData.csv` to `/content/` and run all cells directly.

---

## ☁️ Run on Google Colab

You can also open and run this notebook directly in Google Colab:

1. Upload `Netflix_Data_Analysis.ipynb` to [Google Colab](https://colab.research.google.com/)
2. Upload `NetflixData.csv` to the Colab session storage
3. Run all cells

---

## 📃 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

Made with ❤️ — feel free to fork, star ⭐, and contribute!

