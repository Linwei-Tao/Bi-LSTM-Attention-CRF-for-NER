# Instructions:
All of our implementation and experiments and be found in the excel file.
We also provide the Numbers version for MacOS users.

## 1. What is in the Best Model.ipynb
The best model contains all the implemented components and some of them are added into the best model architecture. The setting of the best model is given below:
| Settings      | Value |
| ----------- | ----------- |
| Syntactic Textual Feature Embedding |None|
| Semantic Textual Feature Embedding | Bert Embedding|
| Character Embedding |Ture|
| Domain Embedding |Ture|
| Seq2Seq Model |Bi-LSTM|
| Attention Strategy |Multi-Head Self Attention|
| Input Embedding Dimension  |946|
| Hidden Dimension |952|
| CRF Layer |Ture|
| Number of Layers   | 1        |


## 2. How to open experiment colab notebooks
You can open the corresponding experiment colab notebook by simply clicking the experiment name in the excel
file. The detailed settings are also shown in the table.

## 3.Code Instructions:
For every colab notebook, they are all runable. You can just run the code block one by one. One point need to
specify which is that you should restart the runtime after install the spacy, since our model is based on the
newest spacy.
