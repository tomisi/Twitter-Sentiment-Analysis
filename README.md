# Sentiment Analysis with LSTM Model

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([link_to_your_google_colab_notebook](https://colab.research.google.com/drive/1JMy2gfdFpKOufYjN57QqMx8LPm-Ezye2?usp=sharing))

## Project Overview: Analyzing Public Sentiment During the COVID-19 Pandemic (Client Project)
This project focuses on sentiment analysis using a Long Short-Term Memory (LSTM) model applied to a dataset of textual data categorized into Negative, Neutral, and Positive sentiments. The goal was to evaluate the LSTM model's performance compared to traditional machine learning models and baseline methods like VADER sentiment analysis.

## Dataset
The dataset comprises textual data sourced from twitter.

## Models Implemented
- **Support Vector Classifier (SVC)**: Achieved an accuracy of 92%.
- **Logistic Regression**: Also performed well with an accuracy of 91%.
- **Decision Tree**: Achieved 80% accuracy.
- **VADER Sentiment Analysis**: Used as a baseline for comparison, providing sentiment scores based on lexicon and rules.
- **Deep Learning Model (LSTM)**: Implemented using embeddings and LSTM layers. Found challenging due to dataset size and complexity, achieving lower accuracy compared to traditional models.

- The classification report shows varying performance across sentiment classes, with Negative and Neutral sentiments poorly predicted compared to Positive sentiment.

## Conclusion
While simpler models like SVC and logistic regression demonstrated robust performance, the LSTM model's lower accuracy highlights challenges related to dataset size and complexity. Further optimization and exploration of deep learning techniques may be beneficial for improving the performance.

## Usage
To replicate or further develop this project:
- Clone the repository.
- Review the data preprocessing steps.
- Explore model implementations and evaluations in the notebooks provided.
- Experiment with hyperparameter tuning and model architectures to improve results.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
