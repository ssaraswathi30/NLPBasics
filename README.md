# NLP Analysis of Amazon Cell Phone Reviews

A comprehensive Natural Language Processing analysis project focusing on text preprocessing, POS tagging, linguistic pattern analysis, and Named Entity Recognition using Amazon Cell Phone reviews dataset.

## 🎯 Project Overview

This project demonstrates advanced NLP techniques including:
- **Dataset Preparation**: Text cleaning and normalization
- **POS Tagging**: Part-of-speech analysis and linguistic patterns
- **Visualization**: Distribution analysis and word clouds
- **HMM Implementation**: Hidden Markov Model for POS tagging
- **NER Analysis**: Named Entity Recognition combined with POS tagging

## 🚀 Quick Start

### Using Conda (Recommended)

```bash
# Create environment
conda env create -f environment.yml

# Activate environment
conda activate nlp_analysis

# Launch Jupyter
jupyter notebook nlp_analysis.ipynb
```

### Using pip

```bash
# Create virtual environment
python -m venv nlp_env
source nlp_env/bin/activate  # On Windows: nlp_env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook nlp_analysis.ipynb
```

## 📋 Requirements

- Python 3.7+
- See `requirements.txt` for complete package list
- Dataset: `Amazon Cell Phone reviews.csv`

## 📁 Project Structure

```
NLPBasics/
├── nlp_analysis.ipynb          # Main analysis notebook
├── Amazon Cell Phone reviews.csv  # Dataset
├── requirements.txt            # pip requirements
├── environment.yml            # conda environment
├── setup_guide.md            # Detailed setup guide
└── README.md                 # This file
```

## 🔍 Analysis Components

### 1. Dataset Preparation (2 Marks)
- **Text Cleaning**: Remove punctuation, numbers, special characters, stop words
- **Normalization**: Apply stemming and lemmatization with comparative analysis

### 2. POS Tagging & Linguistic Analysis (3 Marks)
- **POS Tagging**: Use pretrained models to label parts of speech
- **Pattern Analysis**: Identify noun compounds, verb-object pairs, adjective phrases
- **Linguistic Insights**: Analyze contribution to meaning and NLP applications

### 3. Visualization (1 Mark)
- **Distribution Charts**: Bar plots and pie charts of POS frequencies
- **Word Clouds**: Visual representation of most common terms
- **Comparative Analysis**: Content vs function words

### 4. HMM POS Tagging (2 Marks)
- **Custom Implementation**: Hidden Markov Model with Viterbi algorithm
- **Training & Testing**: Train on sample data, test on first four entries
- **Performance Comparison**: Accuracy metrics vs NLTK tagger

### 5. Combined POS & NER (2 Marks)
- **Dual Analysis**: Apply both POS tagging and Named Entity Recognition
- **Relationship Study**: Analyze complementary benefits
- **Practical Applications**: Information extraction, sentiment analysis

## 📊 Key Features

- ✅ Complete justifications for all methodologies
- ✅ Comprehensive error handling and data validation
- ✅ Interactive visualizations and statistical summaries
- ✅ Custom HMM implementation with detailed explanations
- ✅ Real-world application examples and use cases

## 🛠️ Troubleshooting

See `setup_guide.md` for detailed installation instructions and common issue solutions.

## 📈 Expected Results

- Text preprocessing reduces noise while preserving semantic content
- POS analysis reveals grammatical patterns in product reviews
- Linguistic structures support advanced NLP tasks
- HMM demonstrates probabilistic approach to sequence labeling
- Combined analysis shows synergistic benefits for text understanding

## 🤝 Contributing

Feel free to submit issues, fork the repository, and create pull requests for improvements.

## 📄 License

This project is for educational purposes as part of NLP coursework.
