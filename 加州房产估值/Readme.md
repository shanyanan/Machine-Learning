加州房产估值项目介绍
=================
### 该项目是基于1999年美国加州人口普查数据集，利用数据集对加州地区的房价做预测

项目流程
---------
### 1、整体内容
### 2、定义工作内容
### 3、获取数据
### 4、探索并理解数据
* 利用matplotlib做数据可视化分析
* 数据清洗，缺失值处理
* 处理文本数据和类别属性
### 5、为机器学习准备好数据
* 特征标准化
### 6、选择模型并训练
* 线性回归模型（LinearRegression）
* 决策树（DecisionTree）
* 随即森林（RandomForest） 效果最好
### 7、模型调优
* 网格搜索（选择最优的模型参数）
* 随即搜索
### 8、呈现解决方案
在测试集上进行测试，最终使用网格搜索算法得出的最优参数模型

### 数据集相关变量
* longitude 经度
* latitude 纬度
* housing_median_age 房龄中位数
* total_rooms 总共的房屋数
* total_bedrooms 总共的卧室数
* population 人口数
* household 户数
* median_income 收入中位数
* median_house_value 房价中位数
* ocean_proximity 离海距离

