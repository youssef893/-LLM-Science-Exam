# -LLM-Science-Exam
It is a Kaggle competition to make LLM to solve multiple choice questions
https://www.kaggle.com/competitions/kaggle-llm-science-exam

# Dataset
It is a dataset consists of 200 multiple choice questions and their answer

# Clean dataset
- removing punctuations
- convert to lower case
- lemmatization
- using BERT tokinezer to tokenize text

# Model
using BERT model (bert-based-case) to train on how to choose the right answer
## Model Configrations
- learning rate = 5e-5
- train batch size = 4
- validation batch size = 4
- epochs = 3
- weight decay = 0.01
validation loss = 1.368
