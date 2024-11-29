This project focuses on detecting hate speech in code-mixed Indo-Aryan languages, specifically Hinglish (Hindi-English) and Banglish (Bengali-English), leveraging BERT-based architectures to address the linguistic complexities of these multilingual and informal text forms. Preprocessing includes cleaning, tokenization with WordPiece, and attention masking, while the classification layer uses TFBertModel embeddings with a sigmoid activation function for binary classification. Both models, trained with binary cross-entropy loss and Adam optimizer, achieved accuracies of 72% (Hinglish) and 75% (Banglish), highlighting the impact of dataset quality on performance. Future work involves hyperparameter tuning, exploring advanced architectures, and comparative analysis to enhance cross-lingual hate speech detection.

![hate speech architecture](https://github.com/user-attachments/assets/a2291768-c3c8-44ff-9f0f-6edad8464038)
