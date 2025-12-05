# Disaster Tweet Classification with NLP

This project builds a **Bidirectional LSTM model** to classify tweets as **disaster-related** or **non-disaster** with high accuracy.

---

###  Overview

- Developed a **Bidirectional LSTM** model trained on disaster tweets  
- Achieved competitive accuracy on the test set  
- Cleaned and preprocessed text: removed URLs, stopwords, special characters  
- Tokenized text and padded sequences for model input  
- Used **TensorFlow/Keras** for model development, training loops, and evaluation  

---

###  Tech Stack

- Python  
- TensorFlow / Keras  
- NumPy, Pandas, Matplotlib, Seaborn  
- NLTK for stopwords and text preprocessing  
- WordCloud, Plotly / Cufflinks for visualization  

---

###  Key Steps

1. **Data Loading & Exploration**  
   - Loaded training, test, and sample submission CSV files  
   - Analyzed missing values, tweet lengths, top keywords, and locations  

2. **Text Cleaning & Preprocessing**  
   - Removed URLs and HTML tags  
   - Removed stopwords and non-alphabetic characters  
   - Converted text to lowercase  

3. **Visualization**  
   - Generated word clouds for disaster vs non-disaster tweets  
   - Plotted distributions of keywords and locations  

4. **Tokenization & Padding**  
   - Built a tokenizer with out-of-vocabulary token `<XXX>`  
   - Converted tweets to sequences and applied post-padding  

5. **Model Development**  
   - Built **Bidirectional LSTM** with embedding and dense layers  
   - Binary classification output with sigmoid activation  
   - Compiled with **binary crossentropy** and **Adam optimizer**  

6. **Training & Evaluation**  
   - Trained model on training set, validated on split test set  
   - Monitored accuracy and loss curves  
   - Evaluated predictions with confusion matrix  

7. **Submission**  
   - Predicted labels on Kaggle test set  
   - Created submission CSV  

---

###  Results

- Model achieves strong accuracy distinguishing disaster vs non-disaster tweets  
- Visualizations help understand keyword and location patterns  
- Generates predictions ready for Kaggle submission  
