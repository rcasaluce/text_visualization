# IMDb Sentiment Analysis with ScatterText


## Description

This notebook analyzes IMDb movie reviews to understand the differences between positive and negative sentiments. It includes data preprocessing, visualization of review lengths, word cloud generation, and an interactive ScatterText visualization to explore linguistic patterns.


## Scope of the project

This project was developed for educational purposes to enhance learning in data preprocessing, visualization, and sentiment analysis within the XAI course at Scuola Normale Superiore Pisa as part of the final project (2022).

## Requirements

- Python 3.x
- pandas
- matplotlib
- seaborn
- wordcloud
- scattertext
- spacy
- nltk

## Setup

1. **Install Dependencies**

   ```bash
   pip install pandas matplotlib seaborn wordcloud scattertext spacy nltk
   ```

2. **Download Spacy Model and NLTK Stopwords**

   ```bash
   python -m spacy download en_core_web_md
   ```

   In a Python environment:

   ```python
   import nltk
   nltk.download('stopwords')
   ```

## Usage

1. **Prepare the Dataset**

   Ensure the `IMDBDataset.csv` file is located in the `../csv/` directory relative to the notebook.

2. **Run the Notebook**

   Execute all cells in the notebook sequentially. The workflow includes:
   
   - Loading and inspecting the dataset
   - Expanding contractions in the reviews
   - Cleaning the text data
   - Covert labels in numbers
   - Visualizing review length distributions
   - Generating word clouds for positive and negative reviews
   - Creating an interactive ScatterText visualization

3. **View ScatterText Visualization**

   The final step generates an `ScattertextLog2500.html` file, which is displayed within the notebook for interactive exploration.


# License

This project is licensed under the MIT License.

# Acknowledgments

- [ScatterText](https://github.com/JasonKessler/scattertext)
- [Kaggle](https://www.kaggle.com/) for datasets and resources
