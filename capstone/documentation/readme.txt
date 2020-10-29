Instructions on feeding the model with new data

To predict the popularity of a song the model hasnt seen before:
1. You have to use Spotify Web API to generate the audio features of the song
2. Put the scores of the features into a list in the order the features were fed into the model
3. Run the "predict()" to predict the popularity of that song. 