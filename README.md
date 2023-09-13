# NotNimbleMiner
NotNimbleMiner
NotNimbleMiner is a project aimed at extracting and classifying sensitive information from clinical notes using natural language processing techniques. This repository contains code for a comprehensive pipeline that tokenizes clinical notes from XML files, creates word embeddings, explores vocabulary, assigns labels, and trains a multi-label classification model.

**Key Features:**
1) Tokenization of Clinical Notes: Efficiently processes XML files to extract and tokenize clinical notes.
2) Word Embedding Model: Creates word embeddings using Word2Vec to capture semantic relationships within the clinical text.
3) Vocabulary Exploration: Allows users to interactively explore and select relevant terms for classification.
4) Multi-Label Classification: Trains a Logistic Regression model to automatically classify clinical notes based on selected terms.
5) Evaluation Metrics: Provides classification reports for model performance assessment.
**Usage:**
1) Tokenize Clinical Notes: Input your XML files containing clinical notes to start the tokenization process.
2) Explore Vocabulary: Interactively select terms for classification based on similarity scores.
3) Train Multi-Label Classifier: Train a Logistic Regression model on the selected terms and tokenized data.
4) Evaluate Model: Assess model performance using classification reports.
**Requirements:**
1) Python 3.x
2) Libraries: spaCy, numpy, xml.etree.ElementTree, gensim, scikit-learn
