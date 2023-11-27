# Text-Summarizer

This Python script is a basic implementation of a text summarization algorithm using an extractive approach. The code utilizes the Natural Language Toolkit (NLTK) for tokenization and stopwords.

Getting Started
Prerequisites
Make sure you have Python and the NLTK library installed on your system.

bash
Copy code
pip install nltk
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/text-summarizer.git
Navigate to the project directory:

bash
Copy code
cd text-summarizer
Run the script:

bash
Copy code
python text_summarizer.py
Modify the text variable in the script to use your own text for summarization.

Code Explanation
Tokenization: The script tokenizes the input text into words using NLTK's word_tokenize and separates sentences using sent_tokenize.

Frequency Table: A frequency table is created to store the occurrence count of each word in the tokenized text, excluding common stopwords.

Scoring Sentences: Each sentence is scored based on the sum of the frequencies of its constituent words.

Average Sentence Score: The average score of sentences is calculated.

Generating the Summary: Sentences with scores higher than 1.2 times the average score are included in the summary.

Feel free to experiment with different texts and adjust parameters for your specific use case.

Acknowledgments
NLTK Library: https://www.nltk.org/
