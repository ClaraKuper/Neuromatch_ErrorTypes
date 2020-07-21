Neuromatch_ErrorTypes

Authors: Frauke Esser, Maximilian Hauser, Dominik Kraft, Clara Kuper, Jonathan Orschiedt
Authors are listed alphabetically


Title: To err is human, but where is the error? The search for task-independent neural fMRI-patterns predicting error types.

Scientific question:
How are two/different types of errors represented in the human brain and can error specific signals in the brain be generalized across behavioral tasks?

Brief scientific background:
Being able to flexibly adapt behavior is crucial for everyday life. A first step is to recognize that adaptation is necessary, e.g. if an error was made. However an unspecific signal - that an error was made - will not directly lead to a correct adaptation of behavior. For this there needs to be another/ a further signal which tells what kind of error was made - e.g. whether a response was absent and has to be added or whether a response was made but was not appropriate and has to be changed. Identifying task-unspecific neural signatures that predict these types of errors may prove to be a useful tool in applying neuroscience to emerging technologies.

Proposed analyses:
The analyses would consist of 3 steps:
In step 1 we select a behavioral task A from the HCP dataset. Within this task we will fit a GLM with respect to two error types (omission error and false response) and calculate single contrasts per error vs correct trials to identify error type-dependent neuronal activity (i.e., regions). 
To identify error-independent (i.e., overlapping activity irrespective of error type) we will perform a conjunction analysis in which we take both error type activations together and contrast those vs correct trials. This should result in error type-independent activations/regions.
In step 2.1 we will perform the same analyses as described above for another behavioral task B. Subsequently we will contrast the specific error-type activations across both tasks. This will result in error-type specific task-independent and task-dependent activations/regions.
In step 2.2 we will train a classifier (Random Forest, Support Vector Classifier, K-Nearest Neighbours) on task A which can distinguish between different error types and correct responses. Afterwards we apply this classifier to the fMRI data from task B to decode error types (behavior) in task B from fMRI activation patterns. 

Hypothesis:
We hypothesize that we find error specific regions/activity patterns and error unspecific regions/activity patterns in a specific task. Furthermore, we hypothesize that the error related  activation patterns can be generalized across different behavioral tasks. Due to this we will be able to train a classifier on task A to decode the same error types of task A in task B.

Dataset: HCP 
Keywords: error signals, fMRI, working memory, n-back task, classifying, adaptation
