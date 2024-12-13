# Organize Repositories Related to the KDD Cup 2023
The repositories below provide source code for solving tasks of the KDD Cup 2023.

# NVIDIA MERLIN
For the product recommendation task, Tasks 1 and 2, they generated candidates using KNNs, Transformers, and CNNs. They then applied XGBoost and CatBoost to rank the candidates. For Task 3, they utilized the result from previous tasks and integrated Random Forest and XLM-RoBERTa. 

## Machine Learning Algorithms
- K-Nearest Neighbors
- Transformers
- CNNs
- XGBoost
- CatBoost
- Random Forest
- XLM-RoBERTa

## Performance
- Task 1: 0.41188(MRR@100)
- Task 2: 0.46845(MRR@100)
- Task 3: 0.27152(BLEU Score)

## Source Code 
https://gitlab.aicrowd.com/BenediktSchifferer/kdd2023cup_nvidiamerlin

## Models
- bert-base-multilingual-uncased: https://huggingface.co/google-bert/bert-base-multilingual-uncased
- xlm-roberta-base: https://huggingface.co/FacebookAI/xlm-roberta-base
- xlm-roberta-large: https://huggingface.co/FacebookAI/xlm-roberta-large
- sentence-transformers/allenai-specter: https://huggingface.co/sentence-transformers/allenai-specter
- sentence-transformers/distiluse-base-multilingual-cased-v: https://huggingface.co/sentence-transformers/distiluse-base-multilingual-cased-v2
- sentence-transformers/stsb-xlm-r-multilingual: https://huggingface.co/sentence-transformers/stsb-xlm-r-multilingual
- sentence-transformers/clip-ViT-B-32-multilingual-v1: https://huggingface.co/sentence-transformers/clip-ViT-B-32-multilingual-v1

## Reference
Deotte, C., Onodera, K., Puget, J.-F., Schifferer, B., Titericz, G. (2023). [Winning Amazon KDD Cup'23](https://openreview.net/forum?id=J3wj55kK5t). In *Amazon KDD Cup 2023 Workshop*.

# unirec
They only provide source code for Task 1. They used SASRec and XLM-RoBERTa to generate candidates and XGBoost to rank them.

## Machine Learning Algorithms
- SASRec
- XLM-RoBERTa
- XGBoost

## Performance
- Task 1: 0.40477(MRR@100)

## Source Code 
https://gitlab.aicrowd.com/CXL/unirec-task1-amazon-kddcup-2023

## Reference
Lei, Y., Chen, X., Lian, D., Zhang, P., Lian, J., Li, C., Xie, X. (2023). [Practical Content-aware Session-based Recommendation: Deep Retrieve then Shallow Rank](https://openreview.net/forum?id=6MdSsLgDei). In *Amazon KDD Cup 2023 Workshop*.

# AIDA
They provide source code for both Tasks 1 and 2. They used Multilayer Perceptron to generate candidates and XGBoost to rank them.
## Machine Learning Algorithms
- Multilayer Perceptron
- XGBoost

## Performance
- Task 1: 0.40317(MRR@100)
- Task 2: 0.45047(MRR@100)

## Source Code
https://github.com/karrich/KDD-CUP-2023-solution

## Reference
Liu, S., Zhang, C., Han, X., Wu, W., Zhang, W. (2023). [A Two-stage Ranking Framework for Multilingual Recommendation (Team: AIDA)](https://openreview.net/forum?id=0XrovX52cO). In *Amazon KDD Cup 2023 Workshop*.
