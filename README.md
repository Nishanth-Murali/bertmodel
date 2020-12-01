# SYNTHETIC DATA GENERATION

# BERT Generative Text
## Experiments using BERT for text generation

Google's Bidirectional Encoder Representations from Transformers (BERT) has been hailed as a milestone in Machine Learning NLP. The notebooks in this repo experiment with BERT's capabilities, particularly in a text generative context.

To install:

```
pip install -r requirements.txt
jupyter notebook
```
Run the Jupyter Notebook DullBERT.ipynb to generate sample paraphrases (change the range in the for-loop in line #110 to get more lines of output).

# Training of models to evaluate Winogrande dataset

Run the Jupyter Notebook 'NLP_WinoTrain.ipynb' to get the model trained and tested on RoBERTa model and change 'the model_name_or_path' flag in the final command of the ipynb to elgeish/cs224n-squad2.0-albert-base-v2
