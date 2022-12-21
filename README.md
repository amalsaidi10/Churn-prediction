**data cleaning:
- how to choose which methods to use to convert categorical data?

Label encoding The following features are categorical and each take on 2 values (mostly yes/no) — therefore are transformed to binary integers(eg:"churned" column )

One-Hot Encoding The following features are categorical, yet not ordinal (no ranking) but take on more than 2 values. For each value, a new variable is created with a binary integer indicating if the value occured in a data entry or not (1 or 0).




Some remark about XGBOOST model

1/In XGBoost you can try to:

*reduce depth of each tree (max_depth),

*increase min_child_weight parameter,

*increase gamma parameter,

*add more randomness using subsample, colsample_bytree parameters,

*increase lambda and alpha regularization parameters

2/ boosting algorithms are ideal for imbalanced datasets “because higher weight is given to the minority class at each successive iteration
