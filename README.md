# Arabic Sentiment Analysis

This project implements an Arabic sentiment analysis model using machine learning and transformer models. It can classify Arabic text into sentiment categories such as Positive, Negative, or Neutral.

## Features

- Pretrained transformer-based model for Arabic text sentiment classification
- Supports common Arabic dialects and Modern Standard Arabic (MSA)
- Easy to use with saved model and tokenizer files
- Web app interface using Streamlit for real-time sentiment analysis

## How It Works: Tweet Sentiment Classification

The core of this project is a pretrained transformer-based model that is fine-tuned to classify Arabic text, especially tweets, into three sentiment categories:

- **Positive** (إيجابي)
- **Negative** (سلبي)
- **Neutral** (محايد)

### Tweet Input Processing

- The model accepts raw Arabic tweet text as input, including common dialects and Modern Standard Arabic (MSA).
- Text preprocessing and tokenization are performed using a specialized Arabic tokenizer compatible with the transformer model.

### Model Prediction

- The preprocessed input is passed through the transformer model, which outputs sentiment scores for each category.
- The category with the highest confidence score is selected as the predicted sentiment.

### Output

- The model returns the predicted sentiment label along with a confidence score.
- This sentiment can be displayed in Arabic with emojis or icons for clarity in the web app interface.

### Why Transformer Models?

- Transformer models like BERT are powerful at understanding the context and nuances in Arabic, including dialectical variations.
- They outperform traditional machine learning models on sentiment tasks by capturing semantic meaning rather than relying on keyword matching.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Reemabdi/Arabic-Sentiment-Model.git
   cd Arabic-Sentiment-Model

2. pip install -r requirements.txt
   
## Usage

Run the Streamlit app:

```bash
streamlit run app.py


