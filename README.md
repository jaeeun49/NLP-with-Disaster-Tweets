# NLP-with-Disaster-Tweets
NLP를 공부하며 해당 내용을 캐글 NLP-with-Disaster-Tweets에 적용해 본 분석자료입니다. 


[NLP with Disaster Tweets.ipynb](https://github.com/jaeeun49/NLP-with-Disaster-Tweets/blob/main/NLP%20with%20Disaster%20Tweets.ipynb)

<br>

## 1. Load Data

## 2. Exploratory Data
   - tweet의 글자 개수, 단어 개수, 문장 개수의 분포 
   - Stopwords(불용어)의 차이가 있을까  
   - Wordcloud

## 3. Text Cleaning
   - Url 제거 
   - 구두점 제거  
   - 이모티콘 제거  
   - HTML tag 제거 
   - Stopwords 제거 
   - Lemmatization

## 4. Make Dataset & Embedding Layer
   - Tokenization - 단어를 숫자로
   - Padding - 모든 문장의 길이를 똑같이
   - Embedding Matrix - Glove

## 5. Data Split

## 6. Modeling & Training
   - SimpleRNN  
   - LSTM  
   - LSTM with Attention 
   - Transformer 
   - BERT
