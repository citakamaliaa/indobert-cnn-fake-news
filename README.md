# Indonesian Hoax Classification with SMOTE Optimization
This study evaluates the performance of five deep learning architectures combined with **SMOTE-based oversampling strategies** (Borderline-SMOTE, KMeans-SMOTE, SVM-SMOTE) and a proposed **Margin Loss function** and **Binary-Crossnetropy Loss function** to handle class imbalance in Indonesian hoax news classification.

## Project Overview
- **Dataset:** Indonesian News Dataset (Balanced & Imbalanced scenarios).
- **Embeddings:** Hybrid features using **IndoBERT** (Transformer) and **Word2Vec**.
- **Imbalance Handling:** Implemented three variants of SMOTE to address data scarcity in the minority class.
- **Loss Functions:** Compared standard **Binary Crossentropy** and **Margin Loss**.

The repository relies on Jupyter Notebooks (`.ipynb`) to ensure transparency of the training process, logs, and visualization. Each notebook represents a specific model architecture and loss function configuration.

**Clone the repository:**
   ```bash
   git clone [https://github.com/citakamaliaa/hoax-news-classification.git](https://github.com/citakamaliaa/hoax-news-classification.git)
   cd hoax-news-classification
