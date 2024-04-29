# NIDSImplementation
Implementation of NIDS paper in Python (Find detailed notes in the Jupyter Notebook)
HTML file contains results run on the same notebook.
Dataset hosted here: https://drive.google.com/file/d/14rvTu8Kg6EqwiO7zZHaZsYH129g6KQfg/view?usp=sharing

Citation:
Martina Karanfilovska, Teodora Kochovska, Zdravko Todorov, Ana Cholakoska, Goran Jakimovski, Danijela Efnusheva,
Analysis and modelling of a ML-based NIDS for IoT networks,
Procedia Computer Science,
Volume 204,
2022,
Pages 187-195,
ISSN 1877-0509,
https://doi.org/10.1016/j.procs.2022.08.023.
(https://www.sciencedirect.com/science/article/pii/S187705092200761X)
Abstract: As cyber-attacks become increasingly sophisticated, cybersecurity threats continue to increase. Therefore, it becomes a great challenge to detect, identify and prevent adversary attacks. The inability to detect and avert such attacks can break down the credibility of security services, e.g. data confidentiality, availability, and integrity. An intrusion detection system aims to detect, identify and respond to malicious activities involving computing and network resources. This is even more difficult when the network contains Internet of Things (IoT) devices. The process of developing an intrusion detection system is a tremendous challenge due to false alarm rates, low detection rates, unbalanced datasets and response time. This paper gives a comprehensive model of a network intrusion detection system (NIDS) by applying supervised and unsupervised machine learning (ML) over the NF-ToN-IoT-v2 dataset. Using supervised learning, implemented by Azure automated ML (AML), it is shown that the best results are achieved by algorithm XGBoostClassifier, obtaining an F-Score of 98.8%. When a custom made automated ML (AE2EML) is implemented, the best results are achieved by Random Forest Classifier, obtaining an F-Score of 98.6%. Using clustering with PCA (Principal Component Analysis), implemented by PyCaret automated ML, the proposed ML-based NIDS achieves a Silhouette score of 0.553, Calinski-Harabasz index of 1533106 and Davies-Bouldin index of 0.631.
Keywords: Automated Machine Learning; Classification; Clustering; Internet of Things; Intrusion Detection System; NF-ToN-IoT-v2 Dataset
