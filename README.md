# :space_invader: Feature-space Characteriser
Characterise your feature space with a few simple overview metrics

## Why?
The success of a machine learning model is often dependent on how naturally it works with the underlying data.  

I often find myself approaching new problems with unseen sets of feature-vectors, without any intuition for which methods which might work well and which might fail. It's easy to waste time comparing the performance of incresingly complex models on a feature set which just doesn't encode enough information to be useful.

Getting a quick overview of the density distribution, the number of major clusters, the most important and least important features, or the total information encoded within the space would make it easier to build that intuition over time.

## How?
Don't know yet, haven't written the code. 

Probably some kind of python cli which reads a saved numpy array or torch tensor of vectors, spitting out a load of numbers... Maybe a big jupyter notebook with pretty graphs... Something that I can run on each new dataset before trying various candidate models and comparing performance.
