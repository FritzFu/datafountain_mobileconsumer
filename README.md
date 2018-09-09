# datafountain_moblieconsumer

## 9.6
xgboost模型，未做特征工程，简单调参 0.7994

## 9.7
type1模型，feature importance分析 & 初步筛选，结果略微提升 0.79956
train_test重复客户分析，填充后效果不变（考虑可以从train中删除重复客户防止overfit）

## 9.8
train中NA值fill -> 0，略微调参，overfitting后减少eta和ntree，0.795
