# Event knowledge in large language models: the gap between the impossible and the unlikely

## Directory structure

Local directories:
* **analyses**: main analysis scripts and results
* **model_scores**: sentence scores for all datasets and all models (ported from **XXX**)
* **probing**: code and results for classifier probing results in LLMs
* **sentence_info**: basic sentence features, such as length and word/phrase frequency

Submodules:
* **XXX**: code to extract model scores
* **XXX**: human ratings

## Dataset name aliases
Dataset 1 - EventsAdapt (based on Fedorenko et al, 2020)

Dataset 2 - DTFit (based on Vassallo et al, 2018)

Dataset 3 - EventsRev (based on Ivanova et al, 2021)

The final set of sentences for each dataset can be found in `analyses/clean_data/clean_ALIAS_SentenceSet.csv`
