#Multinoulli distribution

I was actually learning softmax loss function and was confused by that softmax function has a multinoulli distribution. 
That was alot of confusion for me and the mathematics going with it. But finally I defined it in simple terms which I am 
going to present here.

Let's first understand the mathematical jargon here.

According to the definition of Multinoulli distribution a random variables X having k states with its associated probabiities can be distributed called Multinoulli distribution. For an experiment with k outcomes (10 in case of CIFAR10) each one will have its success score whether i^th outcome was occured or not if it occured then X_i =1 if not then X_k = 0. If we repeat the experiment number of times then each success or failure of outcome we will have thier associated probabilities ( they will sum up to 1).

I know most of you was in trouble when defining it within mathematical terms. let try to undertand it more easily in terms of machine learning. 

 As working in machine learning let we have to classify three examples of [cat, car , frog], Let we have n number of training examples for classfying these three examples with our machine learning algorithm. So here at output we will have a probabilistic score through softmax loss function. 
 
 
 
 Link 1: https://www.statlect.com/probability-distributions/multinoulli-distribution 
