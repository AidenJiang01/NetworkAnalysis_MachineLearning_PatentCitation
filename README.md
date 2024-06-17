# NetworkAnalysis_MachineLearning_PatentCitation
This repository contains a collection of my practice Jupyter notebooks focused on patents and their citation networks. 
The notebooks cover a range of topics, from data collection to model building, including:
 1. Data Collection: Using web scraping and APIs (Pandas, BeautifulSoup, google-patent-api).
 2. Database Interaction: Utilizing DB-API and SQL Magic in Jupyter notebooks (MySQL).
 3. Network Analysis: Analyzing global network structures, node centrality, community detection, and network visualization (NetworkX).
 4. Machine Learning: Training ML models to predict network characteristics using preprocessed attribute features (Scikit-Learn).
 5. Deep Learning: Similar to the above but employing neural network models (Keras, scikeras).
 6. Unsupervised Learning: Using dimensionality reduction and clustering algorithms to capture group structures and comparing them to network position classification (Scikit-Learn).
 7. Convolutional Neural Networks (CNN): A basic practice notebook on CNNs.
 8. Recurrent Neural Networks (RNN): A basic practice notebook on RNNs.

Notebook No.1 collects basic information and family-to-family citations of patents. Uses 'Gate-All-Around' as patent search keyword in Google Patent Search.

Notebooks No.2 to No.6 use patent citation network data among firms in the IPC categories 'G03B' and 'G03F'. These notebooks form a series that ranges from network creation and exploration to feature generation and storage. And also utilize network-related features for building, training, tuning, and evaluating machine learning and deep learning models. The main theme of this series of notebooks is to emphasize the importance of directly analyzing network data to gain insights about network characteristics and structure, which cannot be obtained solely from attribute data plus machine learning/deep learning.

Notebook No.7 and No.8 are just simple practice notebooks demonstrating basic knowledge of CNN and RNN architectures.
