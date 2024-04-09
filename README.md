# 4310_final_project

## Feedback from professors:
This should be a feasible and interesting project. You would still be advised to consider:

The dataset. There was no link in the project plan, but I assume your intention was to use the FrontlineInsights|RedditAnalytics|Palestine|Gaza23 dataset? The Kaggle page for that dataset contains a lot of analysis of it. You obviously need to make it clear what you contribute in addition to that analysis.
How do you intend to carry out the named entity recognition? And how will you establish the correctness of your named entity recogniser? If you were to do some (or all?) of that by hand by yourselves, that would most likely take a lot of time, not be a very interesting task, and probably be out of the scope of the course (in terms of effort).
For the (potential) sentiment analysis, be precise on what machine learner(s) you will apply/train. Do you just intend to invoke a basic sentiment analyser (e.g., by using as off-the-shelf, general tool like VADER, or would you develop your own system (possibly then using VADER as a baseline to evaluate against – or as one of the input features to your own learners).
How would you evaluate your results? And on which task(s), exactly? Again keeping in mind that there already is a lot of analysis of various aspects of the dataset on Kaggle. What it is that you want to compare and what you want to compare it to? Is there some related work on a similar task by others (on this dataset or some other dataset) that you straight-forwardly can compare to?


This is a well structured project plan. I assume the dataset is the "Daily Public Opinion on Israel-Palestine War"? 

Up/downvotes is a possibly noisy feature, as you must consider the time since posting - but if you mostly account for automated sentiment, this is likely a better and more objective feature. Interesting regardless!

I would be very interested to see if you can efficiently convey the information visually as it moves through time, e.g. in PCA-like plots. There is functionality for this in BERTopic, which you should also take a look at. https://maartengr.github.io/BERTopic/getting_started/topicsovertime/topicsovertime.html#visualization
