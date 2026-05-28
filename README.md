# Python Page Recommendation System

## Overview

A Python-based recommendation system that predicts pages a user might like based on mutual interests and shared liked pages between users.

The recommendation score is calculated dynamically by analyzing user similarity and ranking suggested pages accordingly.

---

## Features

* Page recommendation system
* Mutual interest analysis
* Recommendation scoring
* User similarity matching
* JSON-based dataset handling
* Sorting recommendations by score

---

## Technologies Used

* Python
* JSON
* Dictionaries
* Sets
* Sorting Algorithms

---

## How It Works

1. Load user data from a JSON file
2. Compare the target user with other users
3. Find shared liked pages using set intersection
4. Calculate recommendation scores
5. Rank pages based on similarity
6. Return recommended pages

---

## Example Output

```python
Pages You Might Like for User 1:
['Machine Learning', 'Data Science', 'AI']
```

---

## Project Structure

```text
project-folder/
│
├── data_1.json
├── recommendation_system.py
└── README.md
```

---

## Future Improvements

* Add graphical user interface
* Use larger real-world datasets
* Improve recommendation accuracy
* Build a web-based version
* Add collaborative filtering techniques

---

## Author

Shashank DP
Data Science Student @ BMSCE
