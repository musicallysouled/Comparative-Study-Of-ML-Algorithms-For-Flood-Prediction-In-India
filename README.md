# Comparative-Study-Of-ML-Algorithms-For-Flood-Prediction-In-India
The research aims to conduct a comparative analysis of various ML models for predicting floods in India, primarily utilizing rainfall data. We recognize the significance of ML models in reducing computational costs and enhancing flood prediction accuracy. Our study aims to evaluate the performance of ten ML models, including Light Gradient Boost Machine, Random Forest Classifier, Decision Tree, and K-Nearest Neighbor, among others. The models will be trained and validated using 13 inundation factors, with a particular focus on incorporating the curve number as a new factor for flood prediction.
By leveraging these established methodologies and insights from the aforementioned papers, our comparative study seeks to contribute valuable information and methodologies to aid in flood prediction efforts in the Indian context.

# Solution
Through an extensive review of recent literature, it was evident that while several studies focused on flood susceptibility within specific subdivisions of India, a notable gap existed in terms of research or scholarly articles centered explicitly on flood prediction within the region. This lacuna propelled the choice of this research topic, aimed at addressing this critical void in the domain of flood prediction in India.
![workflow](https://github.com/musicallysouled/Comparative-Study-Of-ML-Algorithms-For-Flood-Prediction-In-India/assets/88243330/42dca0ce-cebd-4da5-a5b2-3f00cabb6526)
# Dataset Selection and Preprocessing
The foundation of this study rested upon a comprehensive numerical dataset encompassing sub divisional monthly rainfall records across India. The initial stages involved meticulous data preprocessing, addressing missing data while ensuring uniformity in feature formats and data types. Moreover, to facilitate machine learning algorithms' compatibility, the target variable underwent transformation into a binary format (0 and 1). Subdivisions were systematically labelled using label encoders, streamlining the dataset for efficient analysis.

# Data Refinement and Scaling
A key aspect of the process involved the meticulous curation of the dataset. Superfluous features were pruned, optimizing the dataset for enhanced computational efficiency. Additionally, columns were rearranged strategically to streamline the data processing pipeline. Given the wide distribution of data, scaling techniques were employed to standardize the dataset for unbiased model training and validation.

# Feature Extraction and Model Training
The extraction of pertinent features relied on historical data and a threshold-based approach, shaping the target variable to forecast flood occurrences accurately. The model was trained and validated using a sub divisional monthly rainfall dataset spanning from 1901 to 2015, with a meticulous evaluation of accuracy scores.
Testing and Model Evaluation
For comprehensive assessment, a distinct dataset comprising records from 2016 to 2021 was utilized to test the trained algorithms, determining their accuracy scores and identifying the most robust model. The selected model underwent further scrutiny using an independent dataset from the year 2022, gauging its accuracy in predicting flood incidents.
This methodical approach, entailing rigorous data handling, feature extraction, model training, and validation, culminated in an intricate yet robust framework for flood prediction in Indian subdivisions.

# Experiments
The comparative study of machine learning algorithms using a rainfall dataset aimed to precisely forecast flood occurrences, a critical target variable in disaster management. The table presents a detailed overview of the algorithms' performance metrics during validation and testing phases, emphasizing their predictive accuracies:
Algorithm	          Validation accuracy score	   Test accuracy score
KNN	                0.990	                       0.991
Logistic Regression	0.992	                       0.991
Decision Tree	      1.0	                         1.0
SVM	                1.0	                         1.0
Naive Bayes	        0.893	                       0.947

Notably, the Decision Tree and SVM models showcased exceptional performance, achieving perfect accuracies of 1.000 during both validation and testing phases. This consistency signifies their robustness and reliability in accurately predicting flood incidents, establishing them as frontrunners among the evaluated algorithms.
Furthermore, KNN and Logistic Regression models demonstrated commendable accuracies hovering around 99.1% to 99.2% across both validation and test sets. While exhibiting slight variations between the two phases, their high accuracy levels underscore their efficacy in flood prediction tasks.
In contrast, the Naive Bayes model, while exhibiting a reasonably good performance, presented a lower accuracy during validation at 89.3%, which notably improved to 94.7% during the testing phase. This improvement highlights its adaptability and potential to enhance predictive accuracy with additional data or refined methodologies.
Visual representation, as depicted in the accompanying graph, further emphasizes the consistency and comparative performance of these models across both validation and testing phases. The clear delineation showcases the Decision Tree and SVM models' steadfast accuracy, setting them apart as robust and reliable tools for precise flood prediction tasks.
![image](https://github.com/musicallysouled/Comparative-Study-Of-ML-Algorithms-For-Flood-Prediction-In-India/assets/88243330/12ed71a2-168e-45e5-b5c6-ce341f8c86be)
This thorough evaluation substantiates the prowess of the Decision Tree and SVM models in flood prediction, advocating for their implementation in real-world scenarios to facilitate proactive disaster management strategies and minimize the adverse impacts of floods in vulnerable regions.
Further assessment with an undisclosed dataset revealed the Decision Tree model achieving a striking validation accuracy of 100%, outshining the SVM model's still commendable 99.77%. This compelling result underscores the Decision Tree's exceptional predictive capability, indicating its potential as a robust and dependable tool for accurately predicting and managing flood events.
![image](https://github.com/musicallysouled/Comparative-Study-Of-ML-Algorithms-For-Flood-Prediction-In-India/assets/88243330/5f5de0df-b0b9-4df9-9e18-343b7a0909aa)

# Conclusion
The culmination of this extensive research journey, involving the rigorous training, validation, and testing of diverse machine learning algorithms on sub divisional monthly rainfall datasets, reveals profound insights into the realm of flood prediction within the Indian landscape.
The validation and testing phases illuminated the exceptional capabilities of various models in discerning patterns and predicting flood occurrences. Notably, the Decision Tree and SVM models showcased unparalleled prowess, exhibiting perfect accuracy scores of 1.0 during both validation and testing phases. This remarkable performance reaffirms their efficacy and reliability in accurately predicting and anticipating flood events within Indian subdivisions.
Moreover, the utilization of an independent dataset to further scrutinize model performance underscored the Decision Tree's supremacy, attaining an unparalleled validation accuracy of 100%. This outperformance, while marginally surpassing the commendable 99.77% accuracy of the SVM model, highlights the Decision Tree's robustness and unwavering precision in forecasting floods, thereby cementing its position as the optimal choice for flood prediction within this context.
The implications of these findings extend far beyond mere predictive accuracies. They signify a crucial milestone in the realm of disaster management, providing a foundational framework for the development of an advanced and reliable flood prediction model tailored explicitly for the diverse geographic and climatic nuances across India. The unequivocal success of the Decision Tree model not only validates its efficacy but also heralds a promising avenue for proactive flood management strategies, contributing significantly to mitigating the socio-economic impact of floods across the nation.
