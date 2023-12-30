# Cross-Domain Sentiment Analysis for Mental Health Awareness on Twitter

## Overview:

This project focuses on leveraging sentiment analysis and topic modeling to enhance mental health awareness on Twitter. The methodology involves diverse data preprocessing, advanced topic modeling using LDA, BERTopic, and SBERT, and training/testing sentiment analysis models (MNB, BERT, DistilBERT).

## Purpose:

The primary aim is to identify and support users expressing negative sentiments, fostering a supportive online environment. Insights gained from sentiment analysis models contribute to targeted mental health outreach, providing valuable resources where needed.

## Steps:

1. **Data Pre-Processing:**
   - Achieved data balance in the Sentiment140 dataset.
   - Uniformly assigned labels, streamlined preprocessing for standardized inputs.
   - Strategically sub-setted the mental health dataset for focused analysis.

2. **Topic Modeling:**
   - Employed LDA, BERTopic, and SBERT for nuanced topic modeling.
   - Used ChatGPT to extract keywords, contributing to a refined master keyword list.
   - Applied master keyword list to enhance the mental health dataset.

3. **Models:**
   - Utilized MNB as a baseline model for sentiment analysis.
   - BERT and DistilBERT chosen for nuanced sentiment classification.
   - DistilBERT showcased superior performance with 85% accuracy.

4. **Results:**
   - MNB served as a baseline with 50.16% accuracy.
   - BERT achieved 78% accuracy, showcasing nuanced sentiment capture.
   - DistilBERT outperformed with 85% accuracy, decoding subtle linguistic nuances.

5. **User-Centric Analysis:**
   - Identified users expressing negative sentiments using DistilBERT.
   - Created an anonymized user list for targeted mental health support.

## Implications:

- Proactively extend mental health resources to users expressing negative sentiments.
- Leverage findings to enhance user engagement on Twitter with well-being-related content.

## Conclusion:

This project contributes to the ongoing discourse on mental health awareness by utilizing advanced sentiment analysis and topic modeling techniques. The insights gained provide a foundation for targeted support initiatives and user-centric strategies.

## Ethical Considerations:

- Prioritized user privacy by selectively anonymizing Twitter datasets.
- Proactively addressed biases in data preprocessing and model analysis for fair results.

## Declaration of Generative AI Tool Use:

- Leveraged ChatGPT for enhanced topic modeling analysis, acknowledging both advantages and limitations.
- Ensured careful validation of results obtained through the generative AI tool.

---

Dataset used:
- Senti140 Dataset: https://www.kaggle.com/datasets/kazanova/sentiment140.
- Mental Health Dataset: https://www.kaggle.com/datasets/infamouscoder/mental-health-social-media.
