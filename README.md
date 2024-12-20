# Analysis of Machine Learning and Deep Learning Models

---

## Analysis of LSTM-CBOW Model for Word Embedding

This analysis explores the application of a Long Short-Term Memory (LSTM) network combined with the Continuous Bag of Words (CBOW) approach for learning word embeddings from large text datasets. The process begins by using a country-specific Wikipedia article (with over 5000 words) as the source of textual data. The text is preprocessed through tokenization, stopword removal, and other text-cleaning techniques. The LSTM-CBOW model then leverages this preprocessed text to predict words based on their surrounding context, learning contextual relationships between words. This analysis demonstrates how such a model can be applied to capture semantic meaning and generate high-quality word embeddings that can be used for a range of downstream natural language processing tasks, such as text classification, language modeling, and semantic similarity.

---

## Analysis of PCA on the Abalone Dataset

This analysis explores the application of Principal Component Analysis (PCA) to the Abalone dataset for dimensionality reduction and understanding the underlying structure of the data. The dataset, which contains various attributes related to abalones (marine mollusks), such as physical measurements and classification labels, is used to demonstrate how PCA can be employed to reduce the number of features while retaining as much variance (information) as possible. By applying PCA, we identify the number of principal components required to explain 90-95% of the variance in the data. The goal is to determine how many dimensions are necessary for capturing the majority of the variability in the dataset, which is a common task in exploratory data analysis and machine learning. This analysis provides insights into the data’s structure and showcases the effectiveness of PCA for simplifying complex datasets while preserving essential information for downstream tasks.

---

## Analysis of ResNet vs MobileNet for Image Classification

This analysis focuses on comparing the performance of two popular deep learning architectures, ResNet and MobileNet, for image classification tasks. The dataset used in this study consists of three distinct classes: Boats, Gondola, and Ship, each containing labeled images representing their respective categories. The goal of this analysis is to evaluate how well each model performs on this custom dataset, with a focus on classification accuracy, training efficiency, and generalization capabilities. Both ResNet and MobileNet are pre-trained models known for their high performance in image recognition tasks, but they differ in architecture complexity and resource requirements. ResNet is known for its deep residual networks that help mitigate the vanishing gradient problem in very deep models, while MobileNet is optimized for mobile and embedded devices with fewer computational resources. By comparing the results of these two models on the dataset, we gain insights into how each architecture handles the task of classifying different types of objects in real-world images, with an emphasis on trade-offs between accuracy and efficiency.

---

## N-gram Tokenization and Model Comparison (LSTM vs RNN)

This analysis investigates the performance of Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) models for text prediction tasks. Using a custom dataset, N-gram tokenization (e.g., unigrams, bigrams, trigrams) is applied to prepare the data for training. Both models are tested to predict the next token in a sequence, with a focus on evaluating their ability to capture long-term dependencies in the text. The LSTM model, with its memory capabilities, is compared against the standard RNN, highlighting the strengths of LSTM in handling complex sequences. The results provide insights into which model performs better for text prediction and understanding sequence-based tasks in natural language processing.
