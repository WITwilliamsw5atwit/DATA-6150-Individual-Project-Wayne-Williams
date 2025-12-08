# DATA-6150-Individual-Project-Wayne-Williams
Project Title: English–Chinese News Topic Modeling Using TF–IDF and LDA

Part 1:
Goal: Compares English and Chinese news articles using TF–IDF and Latent Dirichlet Allocation (LDA) topic modeling.

English data comes from the HuffPost News Category Dataset.
Chinese data comes from a Chinese news CSV file.
Chinese text is segmented using Jieba.
The goal is to identify major themes in both languages and compare topic distributions.


Part 2: The design:
Datasets/
    News_Category_Dataset_v3.json
    news_collection.csv

Codes/
    TopicModeling_English_Chinese.ipynb

Pictures/
    figure1_average_topic_weights.png
    english_topics.png
    chinese_topics.png

Report/
    Report.pdf                  (6150_Individual_Project_WayneFormat)
    Report.docx                 (6150_Individual_Project_WayneFormat)

Part 3: Run pip install pandas numpy scikit-learn jieba matplotlib wordcloud

Main Outputs:
English and Chinese LDA topic tables
Figure comparing average topic weights
Preprocessed Chinese segmentation example
All images used in the report are stored in Pictures/.

The final written report is located in the report folder as pdf and word doc. (6150_Individual_Project_WayneFormat)


References:
HuffPost News Category Dataset (Kaggle)
Chinese News Collection CSV
scikit-learn, Jieba, Matplotlib
