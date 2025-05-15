# pyspark-sms-spam-detector

This project classifies SMS messages as spam or ham using PySpark, TF-IDF, and Naive Bayes in a scalable ML pipeline.

## 🔧 Technologies Used:
- PySpark (Spark SQL, MLlib)
- Google Colab
- NLP preprocessing
- Naive Bayes classifier

## 🚀 Steps:
1. Tokenization & stop word removal
2. CountVectorizer + TF-IDF
3. Label encoding (`ham`/`spam`)
4. Naive Bayes training
5. Accuracy evaluation

## 📂 Dataset:
- Source: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)
- Format: TSV with labels (`ham`, `spam`) and message text

## 📚 Run in Google Colab:
You can open and run the notebook directly in Colab by uploading it or linking to the GitHub raw file.
