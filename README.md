## Overview

DaisyRec is a Python toolkit dealing with rating prediction and item ranking issue.

The name DAISY (roughly :) ) stands for Multi-**D**imension f**AI**rly comp**A**r**I**son for recommender **SY**stem.

## Examples to run:

The default top-K number is set to 50, you can change top-K number by modifying `topk` argument in `run_*.py`.

```
python run_itemknn.py --sim_method=pearson --topk=15
python run_point_fm.py --loss_type=CL
```

More details of arguments are available in help message, try:

```
python run_itemknn.py --help
```

---

## Dependencies

- torch (>=1.1.0)
- Numpy (>=1.18.0)
- Pandas (>=0.24.0)
- scikit-learn (>=0.21.3)

## Metrics

- Pre (Precision)
- Rec (Recall)
- HR (Hit Rate)
- MAP (Mean Average Precision)
- MRR (Mean Reciprocal Rank)
- NDCG (Normalized Discounted Cumulative Gain)
- F1 (F1-Score)
- AUC (Area Under Curve)

## Experiments Results

