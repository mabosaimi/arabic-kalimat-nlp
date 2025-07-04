# Arabic NLP Project

## Project Overview

This project implements and compares two core NLP tasks on Arabic text data:
- **Text Classification**: Topic classification using the KALIMAT corpus
- **Text Summarization**: Both extractive and generative approaches

We evaluate traditional machine learning methods against modern transformer-based models, focusing on how each handles Arabic-specific linguistic challenges.

## Datasets

1. **KALIMAT Corpus** (Classification):
   - Arabic texts categorized into 6 topics: culture, economy, local news, international news, religion, sports
   - [Dataset source](https://sourceforge.net/projects/kalimat/files/kalimat/document-collection/)

2. **Arabic Summarization Corpus** (Summarization):
   - Collection of Arabic texts with their corresponding summaries
   - [Download Dataset](https://drive.google.com/uc?id=1V7kFgZdlHeTucA9eowNBNy9TG08VDxcY)

## Implementation

- **Traditional ML**: SVM with TF-IDF vectorization
- **Deep Learning**: LSTM and Seq2seq models with attention
- **Transformers**: Arabic BERT-based models
- **Libraries**:
  - scikit-learn, NLTK
  - PyTorch, Hugging Face Transformers
  - pandas, numpy, matplotlib

## Project Links

**Web Interface**:  
[Live Demo](https://nlp-project-tau.vercel.app)  

**API & Models**:  
[Hugging Face Space](https://huggingface.co/spaces/mabosaimi/arabic-summarizer-classifier)  

**Web Interface Code**:  
[GitHub Repository](https://github.com/Fkhrayef/nlp-project)
