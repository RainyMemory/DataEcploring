# DataExploring

## News Explore 真假新闻数据集分析整理

- 对应`newExplore.ipynb`文件
- 对数据集进行一系类特征观察
- 进行一些特征提取
- 构建一些简单模型或利用预训练模型如BERT，进行真假新闻判定

### 其他相关链接

- 更细致的模型搭建Notebook（github）：https://github.com/RainyMemory/BERT-Notebooks/blob/main/playWithFakeRealNews.ipynb
- 更细致的模型搭建Notebook（kaggle）：https://www.kaggle.com/nifler/distinguish-fake-real-news

## Stroke Data 数据分析与预处理

- 对应`strokeDataExplore.ipynb`文件
- 简单观察数据状态
- 利用Rattle查看/绘制样本分布
- 对一些明显的数据错误进行profilling或删除，进行一些简单的数据清理工作

### 其他相关链接

- Rattle中的数据分布图像：https://github.com/RainyMemory/DataExploring/tree/main/imgsrc/StrokeData

## weather AUS 数据分析与预处理

- 对应`weatherAUSExplore.ipynb`文件
- 利用pandas观察数据状态
- 利用Rattle观察各维度数据分布状态
- 查看各维度outliers状况
- 对一些特征进行重新编码（如One-hot编码）
- 进行了一些outliers removal，Normalization，profilling等数据预处理工作

### 其他相关链接

- Rattle中的数据分布图像：https://github.com/RainyMemory/DataExploring/tree/main/imgsrc/WeatherAUS

## NN Assignment 1

- 来自课程任务，代码对应`ipynb`文件
- 根据获取的大脑信号，对实验者聆听的音乐进行分类
- 主要利用浅MLP进行训练拟合
- 对特征数据进行预处理
- 对模型进行学习充分度分析，利用Progressive Compression方式进行神经元学习差异度分析

### 其他相关链接

- 参考文章及数据集：https://github.com/RainyMemory/DataExploring/tree/main/NN-Assignment1

```
Reference：
1. Rahman, J.S., Gedeon, T., Caldwell, S. and Jones, R., 2020, July. Brain Melody Informatics: 
Analysing Effects of Music on Brainwave Patterns. In 2020 International Joint Conference 
on Neural Networks (IJCNN) (pp. 1-8). IEEE.
2. Gedeon, T. D., & Harris, D. (1992, June). Progressive image compression. Neural Networks, 
1992. IJCNN., International Joint Conference on (Vol. 4, pp. 403-407). IEEE.
```
