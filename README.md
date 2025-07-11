Chatbot Intent Recognition using BERT
🧠 Project Overview
This project demonstrates how to build a chatbot capable of classifying user intents using BERT (Bidirectional Encoder Representations from Transformers). Leveraging BERT's deep contextual understanding, the model can accurately interpret user queries, making it suitable for applications in customer support, virtual assistants, and more.

📂 Project Files
Customer_Service_Training_Dataset.csv: A CSV file containing user queries and their corresponding intents.

bert_chatbot_colab_ready.ipynb: A Jupyter Notebook for training and testing the BERT model.

README.md: This documentation file.


Dataset
The dataset used in this project is a CSV file containing user queries and their associated intents. Each entry includes:

Query: The user's input.

Intent: The category or purpose of the query.



⚙️ Model Details
Model Architecture: BERT-based model fine-tuned for intent classification.

Training Framework: TensorFlow with the Hugging Face Transformers library.

Evaluation Metrics: Accuracy, Precision, Recall, F1-Score.
