# Natural Language Processing for Sentiment Analysis of Customer Feedback

This project focuses on leveraging Natural Language Processing (NLP) techniques to process and analyze unstructured text data from customer feedback forms. By applying topic modeling and sentiment analysis, the project helps categorize customer opinions and detect emerging trends, providing actionable insights to improve customer satisfaction.

## Features

- **Sentiment Analysis**: Analyzes customer feedback to determine the overall sentiment (positive, negative, or neutral).
- **Topic Modeling**: Uses Latent Dirichlet Allocation (LDA) to categorize topics discussed by customers in their feedback.
- **Trend Analysis**: Tracks sentiment trends over time to identify patterns or changes in customer opinions.
- **Streamlit Dashboard**: An interactive web application built using Streamlit to visualize sentiment trends and provide insights to the product development team.

## Technologies Used

- **Python**: Main programming language for processing and analysis.
- **spaCy**: NLP library used for text processing and tokenization.
- **NLTK**: Used for additional natural language processing tasks such as text classification.
- **Gensim**: For topic modeling using Latent Dirichlet Allocation (LDA).
- **Streamlit**: Framework used to create an interactive web application to visualize sentiment trends.
  
## Installation on Google Colab

To run this project on Google Colab, follow these steps:

1. **Open the notebook in Google Colab**:  
   Click on the [Google Colab link](https://colab.research.google.com/) to create a new notebook, or directly upload your project notebook.

2. **Install necessary libraries**:  
   Use the following code to install all required dependencies within the Colab environment:
   
   ```python
   !pip install spacy
   !pip install nltk
   !pip install gensim
   !pip install streamlit
    ```
