## Medium Topic Modeling

This repo contains notebooks for performing topic modeling on the kaggle dataset [Medium Articles (with Content)](https://www.kaggle.com/aiswaryaramachandran/medium-articles-with-content).

The notebook remove_dataset_duplicates,ipynb should be run first. This notebook restructures the input data to a more compact and useable form.

The notebook topic_modeling.ipynb applies further pre-processing to the input data and runs LSA, NMF, and LDA algorithms to extract topics.

The notebook clap_modeling.ipynb attempts to use the topic model output to build a linear model for predicting an article's clap count. Turns out this does not work too well, goes to show that there's no formula for a viral post.

The final notebook best_topics.ipynb uses the NMF topic model and contains code used to visualize the topics and build the backend of a recommender system.
