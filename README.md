# Cosine and Jaccard Similarity using TF-IDF

This project involves processing text data in both Persian and English languages, including normalization, rooting, tokenization, and further analysis using TF-IDF calculations and cosine/jaccard similarity measures.

## English Dataset

### Libraries Used
- `nltk`
- `pandas`
- `re`
- `glob`
- `os`
- `numpy`
- `string`

### Functions Implemented
1. **Tokenization and Normalization:**
   - Tokenize the text by words.
   - Normalize the tokens by lowercasing.

2. **Stemming:**
   - Perform stemming on normalized tokens.

3. **Inverted Index:**
   - Build an inverted index based on the first 1000 records of the English dataset.

4. **TF-IDF Calculation:**
   - Calculate TF, IDF, and TF-IDF by leveraging the inverted index.

5. **Cosine Similarity:**
   - Implement a function to calculate cosine similarity.
   - Rank documents based on cosine similarity.

6. **Jaccard Similarity:**
   - Implement a function to calculate Jaccard similarity.
   - Rank documents based on Jaccard similarity.

7. **Document Ranking:**
   - Normalize document scores based on document length.
   - Rank documents using cosine similarity.
   - Display the top 10 documents.

### How to Use
1. Connect Google Drive to access the English dataset.
2. Use provided functions for preprocessing, TF-IDF calculation, and similarity measurement.
3. Input a query to find the top 10 similar documents.

## Persian Dataset

### Libraries Used
- `hazm`
- `pandas`
- `re`

### Functions Implemented
1. **Tokenization and Normalization:**
   - Remove punctuations from titles and content.
   - Concatenate relevant information for further analysis.

2. **Inverted Index:**
   - Build an inverted index based on the Persian dataset.

3. **TF-IDF Calculation:**
   - Calculate TF, IDF, and TF-IDF for the Persian dataset.

4. **Cosine Similarity:**
   - Implement a function to calculate cosine similarity.
   - Rank documents based on cosine similarity.

5. **Jaccard Similarity:**
   - Implement a function to calculate Jaccard similarity.
   - Rank documents based on Jaccard similarity.

### How to Use
1. Download the Persian dataset from the provided link.
2. Use provided functions for preprocessing, TF-IDF calculation, and similarity measurement.
3. Input a query to find the top 10 similar documents.

Feel free to customize this README template based on specific details you'd like to highlight or add. If you have any additional instructions or notes, they can be included in the relevant sections.
