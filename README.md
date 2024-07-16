# Executive-Summary-AI

This project involves creating a system that highlights sentences in a text by assigning scores based on their relevance and importance. Higher-scored sentences are highlighted or extracted to generate a concise summary, effectively capturing the main ideas and key information from the original document. The project leverages various natural language processing (NLP) techniques to achieve this goal.

### Key Features:
**IDE Used:** Jupyter Notebook with Python
**Libraries Used:** spaCy, Headq
**Tasks Performed:**
1.Load spaCy Model: Utilize spaCy's pre-trained models for efficient NLP processing.
2.Tokenization: Break down text into individual tokens (words, punctuation, etc.).
3.Lemmatization and POS Tagging: Reduce words to their base forms and tag parts of speech.
4.Stop Words Removal: Eliminate common words that do not contribute to the meaning.
5.Punctuation Removal: Remove punctuation marks from the text.
6.Word Frequency Calculation: Calculate the frequency of each word.
7.Normalization of Word Frequencies: Normalize word frequencies to a common scale.
8.Sentence Tokenization: Split the text into individual sentences.
9.Sentence Scoring: Assign scores to sentences based on the importance of their words.
10.Summary Extraction: Extract and highlight sentences with the highest scores to form the summary.

### Deployment:
The project has been deployed using Streamlit, a powerful and user-friendly framework for creating interactive web applications. The Streamlit app can take various input formats such as images, files, and documents, making it versatile for different use cases.

**Deployment Highlights:**

- Interactive Interface: Users can upload documents, images, or files directly into the Streamlit app.
- Real-Time Processing: The app processes the input in real-time, displaying the summarized text with highlighted sentences.
- User-Friendly: Intuitive and easy-to-use interface suitable for users without a technical background.
- By combining robust NLP techniques with an interactive Streamlit deployment, this project provides an effective solution for generating concise and informative summaries from various types of documents.
