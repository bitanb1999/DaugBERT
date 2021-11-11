# DAugBERT: A Causality Prediction Pipeline Using Back-translation Data Augmentation with BERT

Establishing causal connections between correlating events lies at the heart of scientific study, from the natural to social sciences. However, despite the critical role that causal connections play in the sciences, linguistic causality has not been given quite the same importance in Natural Language Processing (NLP). In this project, we treat causality as a predictive task and attempt to automatically label causal language in the United Nations General Debates. We make use of BERT, a multi-layer bidirectional transformer, trained on a manually annotated dataset. Our model, trained on the back-translation aided re-balanced training set, is able to label causality on the test set with up to an 82% accuracy.

### Authors: Bitan Biswas, Hanna Béchara, Slava Jankin, Paulina Garcia Corral

#### Note: The data folder has the augmented dataset as well as the non-augmented one. The augmented dataset is named as UNbalanced whereas the other one is named as UNnon_augmented.
1. UNnon_augmented (64% accuracy on BERT implementation)
2. UNbalanced for TextBlob based Back Translation (82% accuracy on BERT implementation)
3. UNbalancedGoogle for Google Translate package based back-translation (86% accuracy on BERT)
4. UNbalancedPy for Python translate package based back-translation (85.2% accuracy on BERT)
The DAugBERT_consolidated_notebook has all the implementations of DAugBERT along with their training and testing accuracy.
