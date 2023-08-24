# sarcasm_detection_traditional_ML
Project on sarcasm detection in Ukrainian language using three traditional ML classifiers: Random Forest, Multinomial Naїve Bayes and Decision Tree.

[initial dataset](https://github.com/botvyns/sarcasm_detection_traditional_ML/blob/main/3795text_original_tag_cleaned.csv) - data as it is.

[preprocessed](https://github.com/botvyns/sarcasm_detection_traditional_ML/blob/main/data_lemmatized_tagged.csv) - data with added lemmatization and pos tagging.

[data with features](https://github.com/botvyns/sarcasm_detection_traditional_ML/blob/main/sent_contra_added.csv) - data with all extracted features.

[data analysis](https://github.com/botvyns/sarcasm_detection_traditional_ML/blob/main/exploratory_data_analysis.ipynb) - notebook for exploratory data analysis and visualisations.

[preprocessing + features](https://github.com/botvyns/sarcasm_detection_traditional_ML/blob/main/data_preprocessing_and_feature_engineering.ipynb) - notebook for basic preprocessing steps and feature engineering.

[classification](https://github.com/botvyns/sarcasm_detection_traditional_ML/blob/main/classification.ipynb) - notebook with code for classifiers training and testing.

For non-sarastics texts part of this [corpora](https://github.com/saganoren/ukr-twi-corpus) was used. Stop-words were taken from [this source](https://github.com/skupriienko/Ukrainian-Stopwords).
To calculate sentiment [this](https://github.com/skupriienko/Ukrainian-Sentiment-Analysis) and [this](https://github.com/lang-uk/tone-dict-uk) dictionaries were used.
