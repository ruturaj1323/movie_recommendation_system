# Content-Based Movie Recommendation System

A content-based movie recommendation system that recommends movies based on their **genres and descriptions** using text vectorization and cosine similarity.

## Overview

Finding a movie to watch can be difficult when there are thousands of choices. This project creates a recommendation system that suggests movies similar to a movie selected by the user.

Instead of relying on ratings from other users, the system compares the content of movies to find similar titles.

## Workflow

```text
Movie Dataset
      ↓
Select Relevant Features
      ↓
Combine Movie Information
      ↓
Text Vectorization
      ↓
Cosine Similarity
      ↓
Find Similar Movies
      ↓
Generate Recommendations
```

## Features

* Uses movie genres and descriptions as content features
* Converts movie information into numerical representations
* Calculates similarity between movies
* Recommends movies based on content similarity
* Uses a dataset containing approximately 10,000 movies
* Saves recommendation artifacts for later inference

## How It Works

### 1. Feature Preparation

Relevant movie information such as genres and descriptions is combined to create a representation of each movie.

### 2. Text Vectorization

The combined text information is converted into numerical vectors so that movies can be compared mathematically.

### 3. Cosine Similarity

Cosine similarity is used to measure how similar two movie vectors are.

Movies with higher similarity scores are considered better recommendations.

## Example

If a user selects a movie, the system:

```text
Selected Movie
      ↓
Compare with other movies
      ↓
Calculate similarity scores
      ↓
Sort by similarity
      ↓
Return similar movies
```

## Tech Stack

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Text Vectorization**
* **Cosine Similarity**

## What I Learned

* Building a recommendation system from scratch
* Preparing text-based features
* Applying vectorization to structured data
* Using cosine similarity for recommendations
* Saving trained artifacts for later inference

## Future Improvements

* Add a user interface for easier interaction
* Include additional movie metadata
* Improve recommendation quality with hybrid approaches
* Compare different vectorization techniques

