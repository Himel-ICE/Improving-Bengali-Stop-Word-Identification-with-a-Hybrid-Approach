# Bengali NLP: Stopword Detection

A robust NLP pipeline built to identify and filter Bengali stopwords using contextual features. Designed with flexibility to integrate into broader tasks like sentiment analysis and cyberbullying detection.

---

## Introduction

This project explores **context-aware stopword detection** for the Bengali language, a low-resource linguistic domain often underrepresented in NLP research. By leveraging positional cues, morphological features, and CountVectorizer representation, the pipeline not only filters irrelevant tokens but also enhances downstream tasks like sentiment analysis and cyberbullying detection.

The motivation stems from the challenges unique to Bengali: rich morphology, syntactic variability, and limited annotated resources. Our goal is to build a reproducible and modular framework that improves feature extraction and model accuracy in text classification tasks.

---

## Features

- Context-aware stopword detection using token position and frequency
- CountVectorizer based feature extraction
- Bengali corpus preprocessing: tokenization, POS tagging
- Modular design for text classification and model evaluation

### Current Limitations

- Dataset size is modest and curated for initial testing
- Annotation strategies are rule-based and require human review for refinement
- Contextual ambiguity in Bengali makes automatic labeling particularly challenging
