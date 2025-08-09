# BookBuddy-KNN 📚🤖

A book recommendation engine built using **K-Nearest Neighbors (KNN)** on the Book-Crossings dataset. This project was completed as part of the **FreeCodeCamp Machine Learning with Python Certification**. 🎓

---

## Project Overview

This recommendation system suggests books similar to a given book based on user ratings. Using the KNN algorithm with cosine similarity, the engine identifies books that share similar rating patterns among users.

To ensure meaningful recommendations, the dataset is filtered to only include users with at least 200 ratings and books with at least 100 ratings, removing sparse or unreliable data. ✨

---

## Dataset

- The Book-Crossings dataset contains over 1.1 million ratings for 270,000 books by 90,000 users.
- Ratings are on a scale of 1-10.
- The data files used are:
  - `BX-Books.csv`
  - `BX-Book-Ratings.csv`
- Dataset downloaded from: [https://cdn.freecodecamp.org/project-data/books/book-crossings.zip](https://cdn.freecodecamp.org/project-data/books/book-crossings.zip)

---

## Features

- Data cleaning and filtering for statistical significance 🧹
- Sparse matrix representation of book-user ratings 🗃️
- K-Nearest Neighbors algorithm with cosine distance metric 📏
- A function `get_recommends(book_title)` returning 5 closest books and their distances 🎯

---

## How to Use

1. Clone the repository.  
2. Run the Jupyter notebook or Python script after downloading the dataset.  
3. Use the function:

```python
get_recommends("The Queen of the Damned (Vampire Chronicles (Paperback))")
```

to get a list of 5 similar books and their distances.

---

## Example Output

```python
[
  "The Queen of the Damned (Vampire Chronicles (Paperback))",
  [
    ["Catch 22", 0.7939],
    ["The Witching Hour (Lives of the Mayfair Witches)", 0.7448],
    ["Interview with the Vampire", 0.7345],
    ["The Tale of the Body Thief (Vampire Chronicles (Paperback))", 0.5376],
    ["The Vampire Lestat (Vampire Chronicles, Book II)", 0.5178]
  ]
]
```

---

## Technologies Used 🛠️

  * Python 3.x 🐍
  * Pandas 🐼
  * NumPy 🔢
  * SciPy (Sparse Matrices) 📊
  * scikit-learn (NearestNeighbors) 📚
  * Jupyter Notebook 📓

---

## License 📄

This project is for educational purposes and is licensed under the MIT License.

---

## Acknowledgements 🙏

  * Dataset provided by FreeCodeCamp: book-crossings.zip
  * Original dataset source: Book-Crossings
  * FreeCodeCamp for the certification project structure and guidance. 🎓

---

*Happy reading and recommending!* 📚✨

