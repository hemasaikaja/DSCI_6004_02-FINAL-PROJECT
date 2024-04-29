

# Efficient Text Summarization with Natural Language Processing

## Project Overview
This project explores the use of Natural Language Processing (NLP) techniques for the automatic summarization of text, aiming to reduce vast amounts of information into concise summaries. It leverages algorithms such as LSTM, Seq2Seq, and TextRank to process text data from diverse sources like Amazon Reviews and BBC News Summary datasets.

## Features
- **Text Summarization Models**: Includes LSTM, Seq2Seq, and TextRank algorithms.
- **Datasets**: Utilizes Amazon Reviews and BBC News Summary for training and evaluation.

https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews

- **Evaluation Metrics**: Uses ROUGE and BLEU scores to assess model performance.

## Getting Started

### Prerequisites
- Python 3.8 or above
- Pip package manager

### Installation
1. Clone the repository:
    ⁠bash
   git clone https://github.com/hemasaikaja/DSCI_6004_02-FINAL-PROJECT.git
   
⁠ 2. Navigate to the project directory:
    ⁠bash
   cd your-repo-name
   
⁠ 3. Install the required packages:
    ⁠
   

⁠ ### Usage
Run the main script to process the input data and view the summarization results:



## Models and Performance
- **LSTM Model**: Processes sequential data but exhibits limited ability to capture the essence of reference summaries.
- **Seq2Seq Model**: Better at handling unigram matches and longest common subsequences, but struggles with bigram overlaps.
- **TextRank Model**: Shows superior performance with nearly perfect scores in ROUGE and BLEU metrics, effectively generating summaries that closely resemble reference texts.

## Deployment
The summarization system is deployed with a user-friendly interface allowing easy interaction with the models. It includes intuitive widgets for adjusting parameters and displaying outputs.

## Contributing
We welcome contributions from the community. Please fork the repository, make your changes, and submit a pull request.

## Authors
- Hema Sai Kaja
- Snithika Patel Talasani 



## Acknowledgments
- Thanks to all contributors who have invested their time in improving this project.
- Special thanks to Professor Mr. Khaled Sayed, whose guidance was invaluable.

## References

Detailed citations and references of the datasets, models, and methodologies used are included within our project documentation.  ⁠

This README.md file is structured to provide clarity and ease of access to all necessary information for anyone looking to understand or contribute to the project.