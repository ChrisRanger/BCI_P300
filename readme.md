# 附件说明
bci
|
|
|-- data                          原数据集及转换后数据集
|   
|-- data_egg                      转换为mne包要求的egg格式数据集文件
|   |-- s1.eeg
|   |-- s1.vhdr
|   `-- s1.vmrk
|-- model                         训练出的模型
|   |-- RF.pickle
|   |-- semi.pickle
|   |-- svm.pickle
|   |-- xgboost.pickle
|   `-- xgboost1.pickle
|-- readme.md                     项目说明文件
`-- src                           代码文件夹
    |-- FeatureExtract.py         时频特征提取        
    |-- classifiers.ipynb         三种P300脑电信号二分类器训练
    |-- question1.ipynb           由二分类器识别字符
    |-- question2.ipynb           通道选择
    |-- question3.ipynb    半监督P300脑电信号二分类器训练
    `-- utlis.ipynb               基础功能实现
