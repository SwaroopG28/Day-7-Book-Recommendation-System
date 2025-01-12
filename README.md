## 📚 **Day 7: Book Recommendation System – Goodreads Dataset**

### 📄 **Project Overview**
This project focuses on building a **Content-Based Book Recommendation System** using metadata from the **Goodreads Books Dataset**. The system suggests books similar to a given title based on features like title, authors, and publisher.

**Dataset Link:** [Goodreads Books Dataset](https://www.kaggle.com/datasets/jealousleopard/goodreadsbooks)

---

### 🎯 **Objective**
- Build a recommendation system to suggest books based on metadata.
- Use **Natural Language Processing (NLP)** techniques to calculate similarities between books.

---

### 📊 **Dataset Description**
- **Columns Used:**
  - `title`: Book title.
  - `authors`: Author(s) of the book.
  - `average_rating`: Average rating of the book.
  - `publisher`: Publisher of the book.
  - `language_code`: Language of the book.


---

### 🛠️ **Steps Performed**

#### **1. Data Preprocessing**
- Selected relevant columns: `title`, `authors`, `average_rating`, `publisher`, `language_code`.
- Combined `title`, `authors`, `publisher`, and `language_code` into a single feature for similarity calculations.

#### **2. Feature Engineering**
- Used **TF-IDF Vectorizer** to convert text data into numerical features.
- Calculated **cosine similarity** between books to measure their similarity.

#### **3. Recommendation System**
- Built a function to recommend books based on a given title:
  - **Input:** Book title.
  - **Output:** Top 10 similar books based on cosine similarity.

---

### 📈 **Results**
- Successfully recommended books based on input titles.
- Tested the system with popular book titles like `"Harry Potter"` and `"The Hunger Games"`.
