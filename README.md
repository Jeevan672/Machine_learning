# Machine_learning

## What Is Machine Learning?
Machine Learning is the science (and art) of programming computers so they can
learn from data.

Here is a slightly more general definition:

[Machine Learning is the] field of study that gives computers the ability to learn
without being explicitly programmed.

—Arthur Samuel, 1959

And a more engineering-oriented one:

A computer program is said to learn from experience E with respect to some task T
and some performance measure P, if its performance on T, as measured by P, improves
with experience E.

—Tom Mitchell, 1997

For example, your spam filter is a Machine Learning program that can learn to flag
spam given examples of spam emails (e.g., flagged by users) and examples of regular
(nonspam, also called “ham”) emails. The examples that the system uses to learn are
called the training set. Each training example is called a training instance (or sample).
In this case, the task T is to flag spam for new emails, the experience E is the training
data, and the performance measure P needs to be defined; for example, you can use
the ratio of correctly classified emails. This particular performance measure is called
accuracy and it is often used in classification tasks


# Types of Machine Learning Systems
There are so many different types of Machine Learning systems that it is useful to
classify them in broad categories based on:

• Whether or not they are trained with human supervision (supervised, unsuper‐
vised, semisupervised, and Reinforcement Learning)

• Whether or not they can learn incrementally on the fly (online versus batch
learning)

• Whether they work by simply comparing new data points to known data points,
or instead detect patterns in the training data and build a predictive model, much
like scientists do (instance-based versus model-based learning)

These criteria are not exclusive; you can combine them in any way you like. For
example, a state-of-the-art spam filter may learn on the fly using a deep neural net‐
work model trained using examples of spam and ham; this makes it an online, model based, supervised learning system.
Let’s look at each of these criteria a bit more closely.


Machine Learning systems can be classified according to the amount and type of
supervision they get during training. 

There are four major categories:

supervised learning

unsupervised learning

semisupervised learning

Reinforcement Learn‐ing.

