UC Boulder MSDS course work <br>
DTSA 5511 Deep Learning

## Mini-Project <br> NLP with Disaster Tweets


This [notebook](https://github.com/elfchildRichter/NLP_Disaster_Tweets) employs GRU and BERT for handling NLP classification tasks, with the objective of predicting which tweets pertain to real disasters and which do not. The data is sourced from [Kaggle](https://www.kaggle.com/competitions/nlp-getting-started), comprising 7613 entries for training and 3263 entries for testing.

<br>

## Summary

| Model | Public Score |
| --- | --- |
| GRU | 0.77750 |
| BERT | 0.79558 |
| BERT_Tuned | 0.81489 |

<br>

- GRU is designed for sequential data processing. It outperforms traditional RNNs by efficiently capturing long-term dependencies. However, its ability to handle subtle semantic differences in text may be limited.

- BERT is a Transformer-based model designed to understand and capture semantic relationships and contextual information in text.

- BERT_Tuned model enhanced performance by optimizing hyperparameters, achieved a public score of 0.81489.

<br>

### Directions for Improvement

- Expand the training dataset by introducing more diverse types of disasters and language usage to improve the model's generalization ability.

- Improve text cleaning and preprocessing steps, such as better tokenization, removing irrelevant characters, synonym replacement, etc.

- Conduct detailed hyperparameter tuning, such as adjusting the learning rate, batch size, number of hidden units, etc., to find the optimal model configuration.

- Try combining the strengths of different models to achieve better performance.

- Explore the latest NLP models and techniques to see if they offer superior performance on this task.