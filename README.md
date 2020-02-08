# Google_QUEST_Q-A_Labeling_Competition
Improving automated understanding of complex question answer content

# Data Description
Build better subjective question-answering algorithms because of a lack of data and predictive models. That’s why the CrowdSource team at Google Research, a group dedicated to advancing NLP and other types of ML science via crowdsourcing, has collected data on a number of these quality scoring aspects.

In this competition, you’re challenged to use this new dataset to build predictive algorithms for different subjective aspects of question-answering. The question-answer pairs were gathered from nearly 70 different websites, in a "common-sense" fashion. Our raters received minimal guidance and training, and relied largely on their subjective interpretation of the prompts. As such, each prompt was crafted in the most intuitive fashion so that raters could simply use their common-sense to complete the task. By lessening our dependency on complicated and opaque rating guidelines, we hope to increase the re-use value of this data set. What you see is what you get!

# File Description
train.csv - the training data (target labels are the last 30 columns)
test.csv - the test set (you must predict 30 labels for each test set row)
sample_submission.csv - a sample submission file in the correct format; column names are the 30 target labels

# Evaluation Metric
Submissions are evaluated on Spearman-rho score between the predicted classes and the observed targets.
