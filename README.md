
# 📚 Book Genre Classification Using LDA & KMeans

This project performs **book segmentation and genre classification** using **Natural Language Processing (NLP)** and **unsupervised Machine Learning**. It extracts text from a PDF book (`Love-Stories.pdf`), tokenizes it into sentences, and clusters those sentences into thematic genres such as **Romance**, **History**, and **Self-Help** using **LDA topic modeling** and **KMeans clustering**.

---

## 🧠 Objective

To segment a book into meaningful sentence clusters and classify them by genre, enabling:
- Thematic analysis
- Content tagging
- Story mining for sentiment and narrative structure

---

## 🛠️ Tools & Libraries Used

| Tool/Library      | Purpose                             |
|-------------------|-------------------------------------|
| `PyPDF2`          | Extract text from PDF               |
| `NLTK`            | Sentence tokenization               |
| `scikit-learn`    | LDA + KMeans + TF-IDF vectorization |
| `matplotlib`      | Plotting graphs                     |
| `WordCloud`       | Generate word clouds                |
| `pandas`          | Data manipulation and storage       |

---

## 📁 File Structure

```
book-genre-classification/
├── Love-Stories.pdf                     # Input book
├── genre_classification.ipynb           # Main notebook with code
├── segmented_stories_with_genre.csv     # Output: genre-tagged sentences
├── README.md                            # This file
└── wordclouds/                          # Optional: generated topic visuals
```

---

## 🧪 How It Works

### 1. **Extract PDF Text**
   - Loads all pages of `Love-Stories.pdf`
   - Cleans and preprocesses the text

### 2. **Sentence Tokenization**
   - Splits full text into individual sentences for fine-grained analysis

### 3. **TF-IDF Vectorization**
   - Converts sentences into numerical vectors based on word importance

### 4. **LDA Topic Modeling**
   - Discovers hidden themes (topics) using Latent Dirichlet Allocation

### 5. **KMeans Clustering**
   - Groups similar sentences into clusters, each representing a thematic segment

### 6. **Keyword Analysis + Word Clouds**
   - Extracts top words for each topic
   - Visualizes each topic using a word cloud

### 7. **Genre Assignment**
   - Manually maps clusters to genres:
     - Cluster 0 → History  
     - Cluster 1 → Romance  
     - Cluster 2 → Self-Help

### 8. **Genre Distribution Plot**
   - Visualizes how many sentences fall into each genre

---

## 📊 Sample Output

| Sentence                                                | Cluster | Genre      |
|---------------------------------------------------------|---------|------------|
| She waited for him through three winters and one war.   | 1       | Romance    |
| The family moved to Brazil and struggled to adapt.      | 0       | History    |
| He believed meditation could bring him clarity.         | 2       | Self-Help  |

---

## 📈 Visualizations

- **Word Clouds**: Show important words per topic
- **Bar Chart**: Shows genre distribution of the text

---

## ✅ How to Run

1. Clone this repository or download files
2. Open `genre_classification.ipynb` in Jupyter Notebook or Google Colab
3. Run all cells sequentially
4. View the final table and charts

---

## 💡 Credits

Built using publicly available tools and inspired by NLP-based story analysis.

---

## 📬 Contact

📧 [talagadadeevibhavaniprasad@gmail.com]
🧑‍💻 [Bhavani Prasad Talagadadeevi]
