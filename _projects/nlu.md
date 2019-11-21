---
title: "NLU Project"
collection: projects
permalink: /projects/nlu
type: "Lecture Project"
venue: "Institute for Machine Learning, ETH Zürich"
location: "Zurich"
code: https://gitlab.ethz.ch/pchaudha/nlu-project2
report: https://gitlab.ethz.ch/pchaudha/nlu-project2/blob/master/NLU_Project2.pdf
---

In a team of two:
* Implementing a simple LSTM Language model to perform various experiments.
* Implementing a system that can solve the Story Cloze task. In the Story Cloze Task we were given a four-sentence short story and two alternatives for the last, fifth sentence that ends the story. Our designed system should decide which among those two are correct. The main challenge lies in the fact that the training data consists of five-sentence short stories that include the correct ending but there is no incorrect ending provided. Due to this to use the training data, we need to either generate wrong endings or use another source for training. The validation set consists of correct and incorrect endings but it is much smaller than training dataset to train. We approached this task by using alternate reading comprehension dataset RACE and training on data generated from it. 
• Tools: Python, Tensorflow
