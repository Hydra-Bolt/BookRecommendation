# BookRecommendation

A data science project for analyzing and understanding book trends using a public dataset of books. This repository explores questions such as:

- What is a good length for a book?
- Is there a correlation between book categories and average ratings?
- Are older books generally rated higher?
- Can we classify book categories based on their descriptions?
- Is it possible to build a recommendation system using only book metadata?

## Contents

- `analysis.ipynb` — Main Jupyter notebook containing data exploration, visualization, and analysis.
- `dataset/books.csv` — The dataset of books, including columns like title, author, category, published year, ratings, and more.
- `dataset/` — Folder containing the dataset and any supporting data files.

## Quick Start

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Hydra-Bolt/BookRecommendation.git
   cd BookRecommendation
   ```

2. **Set up your environment** (recommended: [conda](https://docs.conda.io/) or [venv](https://docs.python.org/3/library/venv.html)):
   ```bash
   conda create -n bookrec python=3.10
   conda activate bookrec
   pip install pandas matplotlib numpy seaborn jupyter
   ```

3. **Run the analysis**:
   ```bash
   jupyter notebook analysis.ipynb
   ```

## Dataset Columns

- `isbn13`, `isbn10`: Book identifiers
- `title`, `subtitle`: Book title and subtitle
- `authors`: Author(s)
- `categories`: Book category/genre
- `thumbnail`: Link to book cover image
- `description`: Short description of the book
- `published_year`: Year of publication
- `average_rating`: Average user rating (e.g., from Goodreads)
- `num_pages`: Number of pages
- `ratings_count`: Number of ratings

## Example Analyses

- **Correlation Heatmap:** Explore how features like page count, published year, and ratings relate to each other.
- **Category Popularity:** Visualize which genres are most common and how their ratings compare.
- **Temporal Trends:** See how ratings have changed over the years.
- **Class Imbalance:** Investigate challenges in building machine learning models due to dominant categories.

## Project Ideas

- Build a content-based recommender using book metadata.
- Train a text classifier for predicting book categories from descriptions.
- Explore the impact of publication date or length on user appreciation.

## License

This project is for educational and research purposes. Please check the dataset's source for any additional restrictions.

---

Feel free to fork or contribute by opening issues or pull requests!
