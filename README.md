# Extractive-Summarization-Technique
This project implements an extractive summarization technique using Natural Language Processing (NLP) in Python. The goal of this tool is to generate concise summaries of longer documents by selecting and combining the most important sentences from the original text.

Extractive summarization identifies the most relevant sentences within a document based on factors such as word frequency and sentence relevance, creating summaries without altering the original wording.


# Features
Summarizes long text documents into concise summaries.

Utilizes NLP techniques for tokenization, stopword removal, and word frequency analysis.

Generates summaries by ranking and extracting key sentences.

Lightweight and easy to use.


# Technologies Used
**Python:** Core programming language.

**NLTK (Natural Language Toolkit):** For text preprocessing (tokenization, stopword removal).

**Heapq:** For extracting top-ranked sentences based on scores.

**Collections (Counter):** For calculating word frequencies.

# How It Works
**1. Input Text:** Provide the document or long text to summarize.

**2. Text Preprocessing:**

      Sentence Tokenization: Splits the text into sentences.

      Word Tokenization: Splits sentences into words.

      Stopword Removal: Removes common, irrelevant words (e.g., "the", "is").

**3. Word Frequency Calculation:** Identifies the most important words by calculating their normalized frequency.

**4. Sentence Scoring:** Assigns scores to sentences based on the frequency of words they contain.

**5. Summary Extraction:** Selects the top-ranked sentences and combines them to create a summary.

# Setup Instructions

**1. 1. Clone the Repository**
      
      git clone https://github.com/your-username/extractive-text-summarizer.git
      
      cd extractive-text-summarizer

**2. Install Dependencies**

Ensure you have Python installed. Install required libraries using pip:
      
      pip install nltk

**3. Download NLTK Resources**

Run the following commands to download necessary NLTK resources:

      import nltk
      nltk.download('punkt')
      nltk.download('stopwords')

**4. Run the Program**

Run the summarizer.py script:

      python summarizer.py

Provide your input text and set the number of sentences you want in the summary.

# Input Example

      Natural Language Processing (NLP) is a sub-field of artificial intelligence (AI) that focuses on the interaction between computers and humans through natural language. The ultimate goal of NLP is to enable computers to understand, interpret, and respond to human language in a way that is both meaningful and useful. NLP is used in various applications such as machine translation, chatbots, sentiment analysis, and text summarization.

# Output Example
      Summary: NLP is used in various applications such as machine translation, chatbots, sentiment analysis, and text summarization. The ultimate goal of NLP is to enable computers to understand, interpret, and respond to human language in a way that is both meaningful and useful.


# Project Files
  
  **summarizer.py:** Python script implementing extractive summarization.
  
  **README.md:** Documentation of the project.
  
  **example_texts/:** Folder containing example text files for testing.
  
  **output/:** Folder to store summary outputs (optional).


# Future Enhancements

Support for multiple languages using multilingual NLP libraries like spaCy or Hugging Face.

Integration with web scraping tools to summarize web content.

Advanced sentence scoring using machine learning techniques.

GUI for user-friendly interactions.


# License

This project is licensed under the MIT License. See the LICENSE file for details.


