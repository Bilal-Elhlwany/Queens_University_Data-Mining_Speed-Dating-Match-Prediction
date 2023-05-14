# Queens_University_Data-Mining_Speed-Dating-Match-Prediction

**Speed Dating Match Prediction**
![inbox_4409738_bfec644abd12b3ec43c8b06aa3d27653_5f0dd150ec40c](https://github.com/Bilal-Elhlwany/Queens_University_Data-Mining_Speed-Dating-Match-Prediction/assets/100938358/be49dcbb-00f7-4177-81a0-f576bb35e07e)

In this assignment, we are going to predict the outcome of a specific speed dating session based on the profile of two people, so we can implement a recommendation system to better match people in speed dating events. We did have another online dating dataset (Tinder-like) but that one is super dirty which requires extensive cleaning, so we do this one instead. This is a binary classification task. Given a data sample (information about the dating session), we are going to predict the probability (0-1, float) that the dating session will lead to a successful match.

The dataset is clean, but has a lot of missing values. The strategy for missing value replacement has to be tuned. Also, as you can guess, this dataset is highly unbalanced (mostly unmatched). The idea of this assignment is to treat the complete workflow from data preprocessing to model training as a single pipeline, and search for the hyperparameters for this pipeline.
Enjoy! https://www.kaggle.com/t/ce4423128c564b79abe239e18b52e095

**Steps:**

**✔️ Meme competition [optional]:**

Include/find a MEME that you liked related to data science/data mining/machine learning. You can upload yours here.

**✔️ Problem Formulation:**

Define the problem. What is the input? What is the output? What data mining function is required? What could be the challenges? What is the impact? What is an ideal solution?
(You can put your answers in markdown format in your notebook - Text Cell)

**✔️ Document your code:**

Put detailed comment on each line of the code to show your understanding of the your code. Also describe: What is the experimental protocol used and how was it carried out? What preprocessing steps are used?
(You can put your answers in markdown format in your notebook - Text Cell)

**✔️ Model Tuning and Documentation:**

Now based on the template, try to improve the model's performance on the public leaderboard by following the data science life-cycle for tuning. You can try different features, different hyperparameters/configurations of the model, and even a different model. For each trial, document the reason why you want to make the certain change and the expected outcome, before running the code. Record the observed performance and your thought on it. The final result is not important, but the process is. Documentation of your thought process is very important, since most people forgot why they test certain model/hyperparameter after they got the result (it takes time). It also helps a lot when you got stuck. You can organize the notebook by listing

thoughts and observations for trial 0, plan for trial 1

code for trial 1

thoughts and observations for trial 1, plan for trial 2

code for trial 2

…
You have to tune at least 6 times. All the tried solutions should be different (e.g. different feature sets/different preprocessing/model/tuning method/tuning range). Requirements - covered at least:

one grid search trial,
and one random search trial,
and one bayesian search trial

**✔️ Answer the questions below (briefly):**

**🌈 Why a simple linear regression model (without any activation function) is not good for classification task, compared to Perceptron/Logistic regression?**

**🌈What's a decision tree and how it is different to a logistic regression model?**

**🌈What's the difference between grid search and random search?**

**🌈What's the difference between bayesian search and random search?**

**Deliverable:**

🔥 A single python notebook containing the documentation of how you reach the final design as well as the answers to the questions.

Note: Emoji allowed and encouraged so it will be more fun for us to grade it.

There are a lot of resources available online, especially for medium.com. For posts that requires tokens/credits, you can open and read that page in incognito mode of your browser.
