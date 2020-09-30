# Sentiment-Analysis-with-seq2seq-Modeling
Using Amazon food Reviews dataset to perfrom sentiment analysis. The Can be downloaded from <a href="https://www.kaggle.com/snap/amazon-fine-food-reviews">HERE</a>  
<ul>
  <li>DataSet: This dataset can be downloaded from  
               <a href="https://www.kaggle.com/snap/amazon-fine-food-reviews">https://www.kaggle.com/snap/amazon-fine-food-review</a> The dataset is quite a huge and time consuming while performing hyoerparameter tuning so only 50000 reviews are taken into consideration out of over half a million reviews.  
  <li> Preprocessing tasks: <p>cleaning and preprocessing like removing special characters, numbers, short words(words with characters length less than 3), stopwords etc.</P>
    <p>The dataset does not implicitly decides positive or negative reviews,instead it rates the reviews in the range 1 - 5 with 1 as the lowest rating and 5 as the highest rating. I have considered reviews with rating above 3 as postive reviews and below it as negative reviews.</p></li>  
   <li>Model Building; Building and obtaining the best performing the deep learning model can tough and time consuming task.The model is build with LSTM.
  I used the pre-written code  from <a href = "https://www.justintodata.com/hyperparameter-tuning-with-python-keras-guide/">https://www.justintodata.com/hyperparameter-tuning-with-python-keras-guide/</a> for tuning hyperparameter. 
