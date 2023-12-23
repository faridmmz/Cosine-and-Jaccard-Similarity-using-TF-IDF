# Cosine and Jaccard Similarity using TF-IDF

This project was part of our Information Retrieval course and is one of our proudest works so we hope you find it interesting also use it in any way you wish. Good luck!

This project involves processing text data in both Persian and English languages, including normalization, Stemming, tokenization, and further analysis using TF-IDF calculations and cosine/jaccard similarity measures. For both English and Persian datasets, we find the top 10 similar documents to our given query and report them with their according scores.


## Libraries Used 

### For English Dataset
- `nltk`
- `pandas`
- `re`
- `glob`
- `os`
- `numpy`
- `string`

### For Persian Dataset
- `hazm`
- `pandas`
- `re`

## Functions Implemented
1. **Tokenization and Normalization:**
   - Tokenize the text by words.
   - Normalize the tokens by lowercasing.

2. **Stemming:**
   - Perform stemming on normalized tokens.

3. **Inverted Index:**
   - Build an inverted index based on all of the English dataset.
   - Build an inverted index based on the first 1000 documents of the Persian dataset.

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

## How to Use
1. Connect Google Drive to access the English dataset, the persian dataset is downloaded in the code.
2. Use provided functions for preprocessing, TF-IDF calculation, and similarity measurement.
3. Input a query to find the top 10 similar documents.

For any inquiries or further information don't hesitate to contact us!


