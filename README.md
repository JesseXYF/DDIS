# DDIS 实验  
本研究主要解决基于药物的转录组数据构建更加精确的药物-药物相互作用(drug–drug interactions,DDIs)预测模型中的两个主要问题:
1）药物转录组数据中的机器噪声.
2）本文探究了将药物看做序列信息是否更有利于DDIs的预测。

## 文件目录结构  

<div>
    <div style="float:left">/codes/</div>
    <div style="float:right">实验代码，包含数据预处理、模型训练、模型对比等</div>
</div>


<div>
    <div style="float:left">/data/original_data/</div>
    <div style="float:right">LINCS L1000数据库中已积累了多种药物诱导的转录组数据</div>
</div>

<div>
    <div style="float:left">/data/feature_processed_data/</div>
    <div style="float:right">采用GCN框架进行数据预处理后的数据</div>
</div>

<div>
    <div style="float:left">/result/</div>
    <div style="float:right">存放中间结果、最终结果等</div>
</div>

## 项目执行所需工具包支持及验证通过的版本号  

| 工具包    | numpy  |pandas  |tensorflow |skmultilearn  |sklearn  |
| ----------| -------| -------| ----------| -------------| --------| 
| 版本号    | 。。。 |。。。。| 。。。。。| 。。。。。。 | 。。。。|

## 代码说明
代码执行顺序:
`先执行 "P1_preprocessing_GCN_data.py" ` ,对原始数据进行预处理；
`再执行 "P2_LSTM_GCN_train_RNN_2layer.py"` ,用预处理后的数据训练模型；
`最后执行 "P3_compare_model.py"` ，对比模型性能。

1. 数据预处理

   `inits.py、Layer.py、Model.py`　;对GCN框架的初始化
   
   `P1_preprocessing_GCN_data.py`　;用GCN框架进行数据预处理
   
    
2. 模型训练
   
   `P2_LSTM_GCN_train_RNN_2layer.py` 　;采用LSTM_GCN框架训练RNN模型

3. 对比模型

   `P3_compare_model.py` 　;对比 "MLARAM", "MLkNN", "BRkNNa", "BRkNNb", "RF", "MLTSVM"六种模型性能
   
    
## 结果文件  
* 分析以下结果文件 
    * /result/。。。/。。。　　　xxx
    * /result/。。。/。。。　　 xxx 
    
    