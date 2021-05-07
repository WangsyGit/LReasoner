# LReasoner
The source code of Paper "Logic-Driven Context Extension and Data Augmentation for Logical Reasoning of Text"

Our ensemble system is the **first to surpass human performance on both EASY set and HARD set of ReClor** ([EvalAI leaderboard])(https://evalai.cloudcv.org/web/challenges/challenge-page/503/leaderboard/1347). If you find this paper useful, please cite this paper:
```
@
```

## Setting up
1. To set up the environment, please install the packages in the `requirements.txt`.
```
pip install -r requirements.txt
```

2. To get the datasets, you can refer to the paper [ReClor: A Reading Comprehension Dataset Requiring Logical Reasoning](https://openreview.net/pdf?id=HJgJtT4tvB) to get the original data. We also provide our preprocessed data in `reclor-data` folder. Or you can start from the original data and preprocess it by the following steps:
 1) exrtact the logical symbols and identify the logical expressions in the context, then infer the entailed logical expressions;
 2) select a logical expreesion in the context and construct the negative samples based on it.
```
cd DataPreprocess
python extract_logical_expressions_v2.py
python construct_negative_samples_v2.py
```

## Usage


## Result
