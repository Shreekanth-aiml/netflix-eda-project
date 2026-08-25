# Netflix EDA Project

This project performs an Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset to uncover patterns in content type, release trends, ratings, country-wise distribution, and content acquisition over time.

The analysis is implemented in the root-level `notebook.ipynb` and is designed to answer key questions about Netflix's content library.

## Project Overview

Netflix is one of the largest streaming platforms globally, and its catalog is shaped by a mix of factors such as:

- content type (movie vs TV show)
- release year distribution
- rating categories
- country of production
- year content was added to Netflix
- duration and genre trends

This project explores these dimensions using Python, pandas, seaborn, and matplotlib, with visualizations to support data-driven insights.

## Dataset

The dataset used for this project is the Kaggle Netflix Movies and TV Shows dataset.

It includes fields such as:

- show_id
- type
- title
- director
- cast
- country
- date_added
- release_year
- rating
- duration
- listed_in
- description

The dataset is included in the repository at `data/netflix_titles.csv`. It is the Netflix Movies and TV Shows dataset from Kaggle.

## Repository Structure

```text
netflix-eda-project/
├── data/
│   ├── netflix_titles.csv      # Netflix dataset
│   └── .gitkeep                # Data directory placeholder
├── images/
│   ├── 1.png                   # Visualization output
│   ├── 2.png                   # Visualization output
│   ├── 3.png                   # Visualization output
│   ├── 4.png                   # Visualization output
│   ├── 5.png                   # Visualization output
│   ├── 6.png                   # Visualization output
│   ├── 7.png                   # Visualization output
│   └── 8.png                   # Visualization output
├── notebook.ipynb              # Main EDA notebook
├── README.md                   # Project documentation
├── LICENSE                     # Repository license
└── .gitignore                  # Git ignore rules
```

## Goals of the Analysis

The notebook analyzes the dataset to answer questions such as:

1. What is the split between movies and TV shows?
2. Which countries produce the most Netflix titles?
3. How has the number of added titles changed over time?
4. What are the most common content ratings?
5. Which genres have the longest average movie durations?

It also includes at least six visualizations to summarize the key findings.

## Tech Stack

- Python
- pandas
- NumPy
- matplotlib
- seaborn
- Jupyter Notebook

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Shreekanth-aiml/netflix-eda-project.git
cd netflix-eda-project
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Open the Notebook

```bash
jupyter notebook notebook.ipynb
```

## Key Insights Explored

The analysis highlights trends such as:

- the overall ratio of movies to TV shows
- content growth over the years
- dominant production countries
- rating distribution by audience segment
- relationship between release year and date added

These insights support understanding of Netflix's content strategy and viewer targeting.

## Notes

This project is intended as an educational and internship-style EDA project focused on data cleaning, exploratory analysis, and data storytelling through visualizations.

## License

This project is distributed under the license in [LICENSE](LICENSE).

## Author

_Shreekanth K — Pluto Academy AI & ML Internship, project 01
