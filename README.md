# datafountain_moblieconsumer

## 9.6
xgboost模型，未做特征工程，简单调参 0.7994

## 9.7
type1模型，feature importance分析 & 初步筛选，结果略微提升 0.79956
train_test重复客户分析，填充后效果不变（考虑可以从train中删除重复客户防止overfit）

## 9.8
train中NA值fill -> 0，略微调参，overfitting后减少eta和ntree，0.795

## 9.9
na处理，rf填充age，删除total_fee为空的训练集，重新train后结果提升，0.811

## 9.14
drop train中的重复项（7w+），多训练了几轮xgboost，结果提升，0.816
