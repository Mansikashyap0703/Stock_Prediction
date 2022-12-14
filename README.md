# Stock_Prediction
Stock_prediction using python(tensor flow).
# overview
 Build a model that will predict whether a stock price will increase or decrease the next day
- We will be basing our prediction on the amount of volume exchanged by the end of a certain day
- The price of a stock at the end of the day is different than at the beginning of the next day. We want to retrieve
    this difference and figure out if stock price will go up or down based on previous data
- If model predicts that stock price will go up, buy at the end of the day and sell right away the next day
- Model won't be even close to 100% accurate as this is nigh impossible to achieve with regards to stocks but will be
    generally more than 60% accurate which will result in a net gain over the long run
- Start by exploring the data sets
- Then look how to import, format, and manipulate the retrieved data
- Build and train computational graph
- Test the accuracy of our results
- At the end, the model will be able to take in the volume exchanged for a day and predict whether the stock price will
    increase or decrease the next morning as a result
