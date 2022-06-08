# Visualizaling political polarization over time from debate transcripts

Through an analysis of written transcriptions from U.S. presidential and vice-presidential debates, we make progress toward determining terminology and rhetoric that is more commonly used by the Democratic or Republican political parties. We used various NLP models such as Naive Bayes, random forests, deep-learning transformer models (BERT) for classification of text polarity over time.

## Dataset
- **finaldata_party.csv** contains the dataset we use for our project, with _result_ correspond to whether the speaker won the debate and _party_ correspond to his/her political party. We built on data compiled by James Martherus. The original paper can be found [here](https://ssrn.com/abstract=3611815) and the raw data can be found [here](https://github.com/jamesmartherus/debates). 

## Notebooks

- **BERT_model.ipynb** _(written by Aniket Joshi, Reza Averly)_ contains code to train and fit various pretrained NLP models from hugging face including ROBERTA, BERT, DistilBERT

- **MNB Pipeline** _(written by Nikhil Ajgaonkar and Adnan Mahmood)_ contains code to train and fit MNB and to construct polarization plots of custom words using the classification model.


## Contributors
- [Lisa Berger](https://github.com/lbrgr) - Polarization analysis
- [Aniket Joshi](https://github.com/aniketjoshi93) – Data gathering, Cleaning and Processing, BERT
- [Reza Averly](https://github.com/aplayly) – Classification (BERT)
- [Adnan Mahmood](https://github.com/MAdnanM94) – Data Visualization and Classification (MNB)
- [Nikhil Ajgaonkar](https://github.com/nikhil1991-cloud) – Data Visualization and Classification (MNB)


This project was created as part of the [Erdös Institute's DataScience Bootcamp 2022](https://www.erdosinstitute.org/code).
