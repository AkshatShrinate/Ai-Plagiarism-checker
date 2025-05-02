AI Plagiarism Checker
This project is an AI-powered tool designed to detect plagiarism by calculating the cosine similarity between text inputs. It processes large text datasets, vectorizes the content using NLP techniques, and identifies the degree of similarity between different pieces of text. Built using Python, scikit-learn, and other data processing libraries, this tool helps in evaluating potential text re-use in academic, professional, or creative writing. The project includes dataset preprocessing, similarity calculation, and model evaluation workflows.

The approach utilizes an LSTM-based neural network trained on tokenized and padded textual data, with hyperparameters such as embedding dimensions, LSTM units, dense layer size, and learning rate optimized using Keras Tuner's RandomSearch. With minimal tuning (just one trial and two epochs), the model was trained and evaluated for performance using accuracy metrics, a confusion matrix, and a classification report. The final model was saved for future use, along with the tokenizer to maintain consistency in text preprocessing.

Note: Avoid the Invalid Notebook Error. The file runs just fine when downloaded 

Accuracy score:
Before Hyperparameter tuning: 84.5%
After Hyperparameter tuning: 83.7%

How to Use
1) Clone the repository
Run the following commands 
git clone https://github.com/AkshatShrinate/Ai-Plagiarism-checker.git
cd Ai-Plagiarism-checker

@)Install the required libraries
(Make sure you have Python installed)
pip install -r requirements.txt


3) Prepare your dataset
The Dataset link : https://www.kaggle.com/datasets/ruvelpereira/mit-plagairism-detection-dataset/data

4)Run the code
Open the .ipynb notebook.
Execute cells step-by-step to preprocess the data, vectorize the text, and compute the cosine similarity.

