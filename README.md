# News-Category-Classification





In the first part, the code loads a dataset from a CSV file using the Pandas library. Then, it preprocesses the dataset by removing unwanted columns, converting text to lowercase, etc. Finally, it saves the preprocessed dataset to another CSV file.

In the second part, the code uses the Spacy library to perform tokenization and other NLP techniques such as lemmatization and named entity recognition on the preprocessed dataset. It defines a function that takes a text as input and returns the processed text. The function is applied to the dataset using the apply method, and the processed text is added as a new column in the dataset. The resulting dataset is then saved to a CSV file.

In the third part, the code uses the Transformers library to fine-tune a pre-trained BERT model on the processed dataset for question answering. The code loads the processed dataset, a pre-trained BERT model, and a tokenizer. It then fine-tunes the model on the dataset and saves the fine-tuned model to a directory. Finally, the code loads the fine-tuned model, defines a pipeline to generate answers to questions, and tests the pipeline on a sample input.

Note that the code is not fully implemented, and some parts, such as the fine-tuning loop, are missing.






