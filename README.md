# BigDataHw2

### XGBoost

#### 參數1
```python
fixed_parameters = {
               'max_depth':8,
               'min_child_weight':3,
               'learning_rate':0.3,
               'colsample_bytree':0.8,
               'subsample':0.8,
               'gamma':0,
               'max_delta_step':0,
               'colsample_bylevel':1,
               'reg_alpha':0,
               'reg_lambda':1,
               'scale_pos_weight':1,
               'base_score':0.5,
               'seed':5,
               'objective':'binary:logistic',
               'silent': 1}
```
#### 結果1：
##### Means
![](https://github.com/taida957789/BigDataHw2/blob/master/xgboost1_mean.png)
##### Standard
![](https://github.com/taida957789/BigDataHw2/blob/master/xgboost1_mean.png)



#### 參數2
```python
fixed_parameters = {
               'max_depth':20,
               'min_child_weight':5,
               'learning_rate':0.4,
               'colsample_bytree':0.6,
               'subsample':0.9,
               'gamma':0,
               'max_delta_step':0,
               'colsample_bylevel':1,
               'reg_alpha':0,
               'reg_lambda':1,
               'scale_pos_weight':1,
               'base_score':0.6,
               'random_state':5,
               'objective':'binary:logistic',
               'silent': 1}
```
#### 結果2：
##### Means
![](https://github.com/taida957789/BigDataHw2/blob/master/xgboost2_mean.png)
##### Standard
![](https://github.com/taida957789/BigDataHw2/blob/master/xgboost2_mean.png)


#### 參數3
```python
fixed_parameters = {
               'max_depth':36,
               'min_child_weight':5,
               'learning_rate':0.4,
               'colsample_bytree':0.6,
               'subsample':0.9,
               'gamma':0,
               'max_delta_step':0,
               'colsample_bylevel':1,
               'reg_alpha':0,
               'reg_lambda':1,
               'scale_pos_weight':1,
               'base_score':0.6,
               'random_state':5,
               'objective':'binary:logistic',
               'silent': 1}
```
#### 結果3：
##### Means
![](https://github.com/taida957789/BigDataHw2/blob/master/xgboost3_mean.png)
##### Standard
![](https://github.com/taida957789/BigDataHw2/blob/master/xgboost3_mean.png)
