# Sberbank-Russian-Housing-Market
Sberbank Russian Housing Market 是kaggle平台上的一个房价预测比赛，这次的比赛特征工程做的并不多，主要还是通过对数据的清洗来提高模型的精确度，因为比赛的数据有很多都是不合理的.所使用的模型xgboost或者lightgbm都行，这次比赛lightgbm貌似效果好些。训练模型的时候，将数据按照product_type的OwerOccupier和Investment分成两个不同的数据集进行训练，对于测试也是分别用所训练得到的模型分别预测，最后将结果结合。具体原因可以看[https://www.kaggle.com/c/sberbank-russian-housing-market/discussion/35684](https://www.kaggle.com/c/sberbank-russian-housing-market/discussion/35684) 