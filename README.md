# FinSenti

FinSenti is a Jupyter Notebook-based project designed to analyze and classify sentiments in financial text data. This notebook employs Natural Language Processing (NLP) techniques to preprocess text, generate visual insights, and build a classification model to predict sentiments.

## Features
- **Text Preprocessing:** Includes tokenization, stemming, and lemmatization.
- **Text Analysis:** Visualizes text data with word clouds and performs sentiment analysis.
- **Text Vectorization:** Converts text data into numerical format using TF-IDF.
- **Model Training and Evaluation:** Uses a RandomForestClassifier to classify sentiments, with data balancing handled by SMOTE.
- **Interactive Prediction (Future Plans):** Integration with Streamlit for interactive sentiment predictions.

## Installation

1. **Clone the Repository:**
```
git clone https://github.com/MLVoyager3791/FinSenti.git
cd FinSenti
```

2. **Install Dependencies:**\
Ensure you have Python 3.7+ installed, then run:
```
pip install -r requirements.txt
```
The requirements.txt file should include:
```
pandas
nltk
wordcloud
textblob
scikit-learn
imbalanced-learn
jupyter
```

## Usage

1. **Open the Jupyter Notebook:**\
Launch Jupyter Notebook:
```
jupyter notebook
```
Then, open run.ipynb in the Jupyter interface.

2. **Run the Notebook:**\
Follow the instructions in the notebook to load data, preprocess text, analyze sentiments, and train models.\
Review the visualizations and classification results.

## Future Plans

**Streamlit Integration:** Future updates will include transforming this notebook into a Streamlit application for interactive analysis and prediction of financial text sentiments.

## Example

1. **Running the Notebook:**\
The notebook will guide you through each step, including data loading, preprocessing, analysis, and model training.

2. **Interactive Features (Planned):**\
The future Streamlit app will allow users to input their own text for real-time sentiment predictions.

## Contributing

Contributions are welcome! Please submit issues or pull requests to enhance the functionality of the tool.
