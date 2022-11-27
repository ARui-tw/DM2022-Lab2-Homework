## Preporcess
1. Organize the data from json to dataframe.
2. Use the `pandas` to do the data analysis.
3. Althought the hashtags is alread in text, I still add it to the head of the text again, so that the hashtags in the end won't be clipped.
4. remove punctuations and change the emojis to text. Also, change some website links and @user to simpiler test, sinces these cannot show emotion.
5. Split data into train and test set.

## Training
1. Use huggingface to do the training.
2. Highly reference the code from [this](https://www.kaggle.com/code/praveengovi/classify-emotions-in-text-with-bert/notebook)
3. Run the triaing with 3090, so that I don't have to wait the whole week.
4. Epooch more than 3 will cause overfitting.
5 Tried to use bert that is finetuned on twitter, but it doesn't work well.