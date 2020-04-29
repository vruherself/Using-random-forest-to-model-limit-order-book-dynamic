# Using-random-forest-to-model-limit-order-book-dynamic
I use the random forest algorithm to forecast mid price dynamic over short time horizon i.e. a few seconds ahead. This is of particular interest to market makers to skew their bid/ask spread in the direction of the most favorable outcome. Most if not all the literature on the topic (see references below) focuses on applying straight out of the box algorithm to create forecast at any point in time. The problem in a real life environment is different. A market maker can provide a standard bid/ask spread most of the time and only when she/he has a statistical hedge she/he can skew the spread in the direction given by the model. This is what I try to do here: creating a forecast only when a statistical hedge exists

I used Python scikit-learn  library. This GitHub repo contains the code, some sample data and the associated explanations (code comments). I'm happy for anyone to re-use my work as long as proper reference to it is made.

I wanted to thank LOBSTER for providing the dataset used here
