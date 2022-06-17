# WeRateDogs-Twitter-Data-Analysis

Project Description
This project analyzes the WeRateDogs twitter page. The dataset is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc.

The WeRateDogs Twitter archive contains basic tweet data for all 2356 of their tweets, but not everything. One column the archive does contain though: each tweet's text, which I used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo). Additional data was gathered from Twitter's API for the tweet Ids in the twitter archive dataset. These additional data includes the like counts, retweet counts etc.

Furthermore, a table of image predictions which contains the results of the neural network classifier that classifies breeds of dogs from alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction was gotten from the Udacity website.
