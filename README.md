Some remark about XGBOOST model

1/In XGBoost you can try to:

*reduce depth of each tree (max_depth),

*increase min_child_weight parameter,

*increase gamma parameter,

*add more randomness using subsample, colsample_bytree parameters,

*increase lambda and alpha regularization parameters

2/ boosting algorithms are ideal for imbalanced datasets “because higher weight is given to the minority class at each successive iteration
