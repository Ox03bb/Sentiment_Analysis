 ![Tensorflow](https://img.shields.io/badge/-Tensorflow-ff6f00?style=flat&logo=tensorflow&logoColor=white)  ![sklearn](https://img.shields.io/badge/-sklearn-F89C3F?style=flat&logo=scikit%20learn&logoColor=white&labelColor=3294C7) 
# Sentiment Analysis

Welcome to the Sentiment_Analysis repository. This repository contains two main projects focusing on different aspects of sentiment analysis.

## Projects

### 1. Twitter Sentiment Analysis

This project involves the binary classification of Twitter sentiments as positive, negative, or neutral. The analysis is performed using a Random Forest algorithm, which achieved an accuracy of 92%.

- **Algorithm**: Random Forest
- **Accuracy**: 92%
- **Dataset**: Twitter data with sentiment labels
- **Notebook**: `Twitter_Sentiment_Analysis.ipynb`

### 2. Text-to-Emoji Conversion ("Emojify")

The second project is a Text-to-Emoji conversion system named "Emojify". This system is implemented using an LSTM Neural Network. Despite facing overfitting issues due to the very small dataset size, the model achieved quite acceptable results.

- **Algorithm**: LSTM Neural Network
- **Dataset**: Small text dataset with corresponding emojis
- **Notebook**: `Emojify.ipynb`
- **Challenges**: Overfitting due to small dataset size

## Repository Structure

```
src/
│  │
│  ├── data/                              # Data used for the projects
│  ├── Twitter_Sentiment_Analysis.ipynb   # Notebook for Twitter Sentiment Analysis
│  └── Emojify.ipynb                      # Notebook for Text-to-Emoji Conversion
├──  README.md                              # Repository overview
└── requirements.txt                       # Required dependencies
```

## Getting Started

To get started with the notebooks, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Ox03bb/Sentiment_Analysis.git
   cd Sentiment_Analysis
   ```

2. **Install the required dependencies**:
   Ensure you have the necessary libraries installed. You can install them using pip:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebooks**:
   Open Jupyter Notebook and navigate to the project directory to run the notebooks:
   ```bash
   jupyter notebook
   ```

## Contributing

Feel free to fork this repository, make changes, and submit pull requests. All contributions are welcome!

