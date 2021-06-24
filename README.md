# NLP-with-Disaster-Tweets
NLP를 공부하며 해당 내용을 캐글 NLP-with-Disaster-Tweets에 적용해 본 분석자료입니다. 

<br>

## 1. Load Data

## 2. Exploratory Data
   2.1. weet의 글자 개수, 단어 개수, 문장 개수의 분포
 
   2.2. Stopwords(불용어)의 차이가 있을까
  
   2.3. Wordcloud

## 3. Text Cleaning
   3.1. Url 제거
  
   3.2. 구두점 제거
  
   3.3. 이모티콘 제거
  
   3.4. HTML tag 제거
  
   3.5. Stopwords 제거
  
   3.6. Lemmatization

## 4. Make Dataset & Embedding Layer
   4.1. Tokenization - 단어를 숫자로
 
   4.2. Padding - 모든 문장의 길이를 똑같이
  
   4.3. Embedding Matrix - Glove

## 5. Data Split

## 6. Modeling & Training
   6.1. SimpleRNN
  
   6.2. LSTM
  
   6.3. LSTM with Attention
  
   6.3. Transformer
  
   6.4. BERT
