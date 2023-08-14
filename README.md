# Data-Leakage
"A scenario when ML model already has information of test data in training data, but this information would not be available at the time of prediction, called data leakage. It causes high performance while training set, but perform poorly in deployment or production."


Data leakage, a very interesting topic. If anyone has not heard of it before and someone asked them about this, it is pretty sure that the answer we will get will be quite interesting. Some will say that a portion of data will be masked or removed accidentally while training. Is it not? But here is the answer. Sometimes when we train a model and test it, the accuracy we get is very high and no overfitting occurs. We think that the model is ready to be deployed and we deploy it. Boom, it fails in production. You do not get same level of performance in production as you got in testing. This is often called data leakage.
