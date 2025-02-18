This is a natural language processing project that prompts the user to review a movie that they have seen. It then utilizes an LSTM on a large database of reviews from Rotten Tomatoes. This model will input the user review and output a rating as a percent (higher is better)

Currently the performance isn't ideal, but could be a lot worse: MAE of around 0.12 and R^2 of around 0.35. Part of this is due to computation limits on my end limiting the size of the model I can make as well as the number of epochs I can run. Another possible problem is inconsistencies in the dataset and inconsistencies in style of review, for example some people think that a 5/10 is really bad and some people think it's very middle-of-the-road. I need to do some EDA to explore this in depth. I also need to try Word2Vec instead of fastText to see how they copare.


Changelog:

v0.1 - this version is fully functional, but has several issues with clarity and an issue with VSCode, issues with proper masking
v1.1 - Fully functional, improved clarity, masking works as intended 
