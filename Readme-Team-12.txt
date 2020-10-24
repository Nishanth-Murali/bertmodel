CSE576: NLP
Synthetic dataset creation
Common Sense Question Answering Dataset

TEAM MEMBERS 		ASU ID
NISHANTH MURALI		1217317790
JUDITH ROSENKE		
JAH MARKABAWI		

README for NISHANTH MURALI (1217317790)

Columns in the dataset:
1. Context
2. Question
3. Potential answer
4. answer label (yes/no) to tell if the answer was correct or not.

CONTRIBUTION:
1. Generated Dataset with the help of BERT modules; BertTokenizer, BertModel, BertForMaskedLM.
2. Used the MCTACO CommonSenseQA dataset to generate similar data items.
3. Built a text file (keywords.txt) that consists of the 10% of the words in the original text file (MCTACO dataset).
4. Used the words in 'keywords.txt' to replace the actual words using Masked Language Modeling.
5.    
