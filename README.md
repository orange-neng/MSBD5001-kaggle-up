MSBD5001-kaggle-up
===========================
This is my individual project of MSBD 5001 from HKUST 20FAll BDT.
* Project details are in the following content.

### Task Description:
The individual project counts for 20% of the final grade. It's supported by the smart city project of iSingLab (Smart City).
The dataset provides the average traffic speed per hour for a major road in Hong Kong from 2017 to 2018. Part of the dataset is provided as the training data, and your task is to predict the rest. 80% of the dataset is provided as the training data and 20% as the testing data, including the timestamp and the corresponding average speed. We sampled the testing data only from the year 2018 to provide you a training dataset that has the complete data spanning the year 2017. However, the speed information is sometimes missing due to device malfunction.You have to submit the predicted results of these testing samples, which are then compared with the ground truth to evaluate the performance of your model.

****
	
|Author|Xinyue Zhang|
|---|---
|ID|20750194
|Email|xzhangfa@connect.ust.hk


****
## Content
* [Data](#Data)
    * weather.csv  
      This was crawled from the internet.  
      Column:
      * |`weather`|0-sunny/cloudy；1-light rain/shower； 2-moderate rain/heavy rain|
      * |`wind`|wind rating|
    * train.csv
    * test.csv
    * HONG KONG public holiday 2017/2018 （this included in code）
      https://www.gov.hk/tc/about/abouthk/holiday/
      
* [past tries](#文本)
    * try.ipynb
    * try2.ipynb
    * try3-减少特征-xgb.train.ipynb
    * ...
      This 12 files are all my tries to check which features and models should be selected.
      
* [Final code : Final-intergration-20750194.ipynb](#dd)

* [Final result : submission.csv](#文本)

Requirments
------
|environment|version|
|----|-----|
|`python`|3.8|
|`tool`| Jupyter HTML Notebook|
|`system`|MAC OS|
|`packages`|pandas, numpy, sklearn, xgboost, math, matplotlib|

How to start
------
1. Download the whole project.
2. Run directly the file -> Final-intergration-20750194.ipynb.
3. Get submission10.83.csv in the folder.
* submission10.83.csv is the same as the final results -> submission.csv,just different name.

```diff
+ 人闲桂花落，
# 时鸣春涧中。
```
