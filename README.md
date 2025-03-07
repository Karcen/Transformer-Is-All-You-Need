<h1>Abstract</h1>

Sentiment analysis is a crucial task in natural language processing (NLP) with applications ranging from social media monitoring to consumer feedback evaluation. While transformer-based models like DeBERTa have set new benchmarks, challenges such as limited training data, class imbalance, and computational overhead persist. In this paper, we propose a comprehensive framework that incorporates Word2Vec-based text augmentation and explores multiple modifications to the standard DeBERTa model. Our framework not only enhances model performance but also maintains computational efficiency.

We evaluate our approach on the SST-5 dataset, a benchmark for fine-grained sentiment analysis. Our text augmentation pipeline employs transformations such as synonym replacement, random insertion, deletion, and swapping, all grounded in rigorous mathematical formulations. For model architectures, we explore baseline, transformer-enhanced, FFN-enhanced, and adapter-enhanced variants of DeBERTa.

Our experimental results show that the baseline DeBERTaForSentiment and DeBERTaLSTM models achieve an accuracy of 23.08\%, with a low F1-score of 0.0750. In contrast, the DeBERTaFFN model significantly outperforms these baselines, reaching an accuracy of 28.55\% and an F1-score of 0.1430. This improvement highlights the effectiveness of additional feature transformations within the transformer-based architecture.

The findings suggest that while LSTM layers do not enhance DeBERTa’s performance, the addition of FFN layers provides a noticeable improvement in classification accuracy and robustness. The relatively low overall performance underscores the difficulty of fine-grained sentiment analysis, emphasizing the need for further research. Future work will focus on exploring more advanced adapter-based approaches, domain-specific pretraining, and dynamic augmentation techniques to enhance the generalization capability of sentiment analysis models.


**Keywords: sentiment analysis; DeBERTa; Transformer**
