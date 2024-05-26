- How would you define machine learning? \
  Machine learning is training a computer on large amounts of data to perform various tasks

- Can you name four types of applications where it shines? \
  Spam filters, particle physics, language learning, ai, bots.

- What is a labeled training set? \ 
  collection of samples of input data. Each sample has a value ascoiated with it called a lable. For example spam or ham mails. 
  Training set that contains the solutions 

- What are the two most common supervised tasks? \
Classification (classify mails) and to predict a target numeric value (What is the price of a car?)

- Can you name four common unsupervised tasks? \
Clustering clustering people together, vizualization (feed lots of data to output into something that can be plottet), dimensionality reduction (simplify data without losing too much info. merge milage and age for a car. Called feuture extraction.). Anomoly detection (Detect unusual data points for example credit card fraud.)

- What type of algorithm would you use to allow a robot to walk in various unknown terrains? \
  Reinforcement learning. Place agent in environment. reward or punish based on interactions with environment.

- What type of algorithm would you use to segment your customers into multiple groups? \
  hierachel clustering supervised learning.
   

- Would you frame the problem of spam detection as a supervised learning problem or an unsupervised learning problem? \
  Supervised

- What is an online learning system? \
Online learning model is a model first trained to complete a task, after the model is "online" or live it can still take feedback/learn from experience 

- What is out-of-core learning? \
- Out of core learning is used for online learning models. Out of core meaning tat the data is not store in the cores memory but can take new input data in batches. This is useful for huge datasets which are 2 large to load into the memory of one pc.

- What type of algorithm relies on a similarity measure to make predictions? \
  instance based learning. flags emails that are similar to a previously known spam emails for example by mail.

- What is the difference between a model parameter and a model hyperparameter? \
  The model parameters are the constants in a specific model for example for a linear model: y = $\theta_1$ x + $\theta_2$.
  A hyperparameter is set constant before the training of the model and is therefor not affacted by the model learning


- What do model-based algorithms search for? What is the most common strategy they use to succeed? How do they make predictions? \
make the best linear regression
 

- Can you name four of the main challenges in machine learning? \
 Not enough data. Data not representative. Bad data. Irrelevant features.

- If your model performs great on the training data but generalizes poorly to new instances, what is happening? Can you name three possible solutions? \
 Lets say you want create a model to predict happiness based on gdp but you only train on scandinavian countries, the model is gonna perform bad on asian countries.   

- What is a test set, and why would you want to use it? \
 A test set is saving some of the data to test how well your model perform. If you use 100% data you have nothing to test on.

- What is the purpose of a validation set? \
   validation or development set is used as intermediate between your training set and the test set. To retrain the best models. 

- What is the train-dev set, when do you need it, and how do you use it? \
 hen real data is scarce (right), you may use similar abundant data (left) for training and hold out some of it in a train-dev set to evaluate overfitting; the real data is then used to evaluate data mismatch (dev set) and to evaluate the final model’s performance (test set)

- What can go wrong if you tune hyperparameters using the test set? \
  Your model might underperform  