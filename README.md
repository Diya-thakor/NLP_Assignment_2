**NLP Assignment 2 - Team 9 - German**

In task 1, 5 different tokenizers were trained and the best tokenizer (tokenizer_5) was chosen to train our model.

In task 2, LlamaForCasualLM pre-trained model was chosen and it was adjusted in such a way we get <100M params (20.84M in our case).
Then our data was tokenized using the tokenizer_5 and the adjusted model was trained using our tokenized dataset.
