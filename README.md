# NLP-word-syntactic-classification-anomaly-detection
## 1- Syntactic Word Classification

I classified words according to their syntactic features. In this work I used Turkish and English words as classification labels and obtained an F1 score of 0.44 despite train data being poor. This features/framework can be used with other datasets for different classification problems, too as long as the label can be identified syntactically.

## 2- Junk Word Classification (Anomaly / Novelty Detection)

In 2nd part, I implemented Novelty Detection via Local Outlier Factor where I identified junk words from actual words, regardless of the language since junk/random words carry distinctive features.

## Character Level Language Classification NLP with LSTM

Using more data, I implemented a character-level language classification using LSTM. F1 score of 0.92 is obtained.
