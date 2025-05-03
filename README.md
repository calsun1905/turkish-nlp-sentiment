# turkish-nlp-sentiment
NLP project for Turkish sentiment classification using traditional (TF-IDF) and deep learning (LSTM) models, with word embedding visualization.
# Turkish Sentiment Analysis using Word Embedding and Deep Learning

This project explores a Turkish NLP problem using both classic methods (TF-IDF + Logistic Regression) and deep learning (LSTM + Embedding). The project compares performance and includes embedding visualization via TensorFlow Projector.

## 📁 Files

- `colab_notebook.ipynb`: Main code used for preprocessing, training and evaluation
- `meta.tsv` and `vecs.tsv`: Files for embedding visualization (projector.tensorflow.org)
- `report.pdf`: The full report explaining methodology and results
- `data/train.csv`, `data/test.csv`: Dataset files used in the project

## 🧪 Models

- TF-IDF + Logistic Regression
- LSTM + Keras Embedding Layer

## 📊 Results

| Model | Accuracy | Macro F1 |
|-------|----------|----------|
| TF-IDF + LR | 93% | 0.87 |
| LSTM + Embedding | 94% | 0.90 |

## 🌐 Embedding Visualization

You can visualize the learned embeddings at [projector.tensorflow.org](https://projector.tensorflow.org) using `meta.tsv` and `vecs.tsv`.

## 👥 Team

- Abdullah
- Batu
- Ege

## 📄 License & Dataset

- Dataset from Kaggle: https://www.kaggle.com/datasets/winvoker/turkishsentimentanalysisdataset

