# LEARNING-A-URL-REPRESENTATION-WITH-DEEP-LEARNING-FOR-MALICIOUS-URL-DETECTION

Malicious URLs host unsolicited content and are used to perpetrate cybercrimes. It is imperative to detect them in a timely manner. Traditionally, this is done through the usage of blacklists, which cannot be exhaustive, and cannot detect newly generated malicious URLs. To address this, recent years have witnessed several efforts to perform Malicious URL Detection using Machine Learning. The most popular and scalable approaches use lexical properties of the URL string by extracting Bag-of-words like features, followed by applying machine learning models such as SVMs. There are also other features designed by experts to improve the prediction performance of the model. These approaches suffer from several limitations: 

(i) Inability to effectively capture semantic meaning and sequential patterns in URL strings; 

(ii) Requiring substantial manual feature engineering; 

(iii) Inability to handle unseen features and generalize to test data.

To address these challenges, we propose URLNet, an end-to-end deep learning framework to learn a nonlinear URL embedding for Malicious URL Detection directly from the URL. Specifically, we apply Convolutional Neural Networks to both characters and words of the URL String to learn the URL embedding in a jointly optimized framework. This approach allows the model to capture several types of semantic information, which was not possible by the existing models. We also propose advanced word-embeddings to solve the problem of too many rare words observed in this task. We conduct extensive experiments on a large-scale dataset and show a significant performance gain over existing methods. We also conduct ablation studies to evaluate the performance of various components of URLNet.

