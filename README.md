# Rate-Severity-of-Toxic-Comments

## Project Description


See https://www.kaggle.com/c/jigsaw-toxic-severity-rating.

From [**Kaggle**](https://www.kaggle.com/c/jigsaw-toxic-severity-rating/data):
> In this competition you will be ranking comments in order of severity of toxicity. You are given a list of comments, and each comment should be scored according to their relative toxicity. Comments with a higher degree of toxicity should receive a higher numerical value compared to comments with a lower degree of toxicity.
> 
> **Disclaimer:** The dataset for this competition contains text that may be considered *profane, vulgar, or offensive*.




### Data Description

"*Your task is to predict a score that represents the relative toxic severity of the comment. Comments with a higher degree of toxicity should receive a higher numerical value compared to comments with a lower degree of toxicity; scores are relative, and not constrained to a certain range of values.*"

> Note, there is no training data for this competition. You can refer to previous Jigsaw competitions for data that might be useful to train models. But note that the task of previous competitions has been to predict the probability that a comment was toxic, rather than the degree or severity of a comment's toxicity.
> 
> **Toxic Comment Classification Challenge**\
> **Jigsaw Unintended Bias in Toxicity Classification**\
> **Jigsaw Multilingual Toxic Comment Classification**
> 
> While we don't include training data, we do provide a set of paired toxicity rankings that can be used to validate models.
> 
> #### Files
> 
> **comments_to_score.csv** - for each comment text in this file, your task is to predict a score that represents the relative toxic severity of the comment. Comments with a higher degree of toxicity should receive a higher numerical value compared to comments with a lower degree of toxicity; scores are relative, and not constrained to a certain range of values. NOTE: the rerun version of this file has ~14k comments that will be scored by your submitted model.\
> **sample_submission.csv** - a sample submission file in the correct format\
> **validation_data.csv** - pair rankings that can be used to validate models; this data includes the annotator worker id, and how that annotator ranked a given pair of comments; note, this data contains comments that are not found in comments_to_score.
