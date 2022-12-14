# NLP-Stock-Price-Prediction
Used neural networks to explore the relationship between the content of financial news and the direction of 
stock returns, i.e., their classification into positive or negative returns.

An NLP technique was first used to transform  unstructured data into numerical data which makes it easy to interpret by the algorithm. 
Term Frequency- Inverse Document Frequency (Tf-idf) is the NLP technique used on news data relevant to each company extracted previosuly. 
It will help us determine words or phrases in a headline that impact or lead to movements in returns of stock prices, 
the term-frequency component finds the most frequently occurred words and the inverse document frequency component helps to appropriately re-weights words by de-weighting the common words like = "the", "and", etc.
By using this technique we can analyse large datasets of text to find a relationship between news headlines and stock price movements.

Trained a two-layer neural network with three units (neurons) to explain return directions based on financial news.
Further analysis was completed on different hyperparameters by varying number of hidden layers and nodes in each layer.

Finally explored how well a neural network can predict the direction of future returns of a stock based on our text data
