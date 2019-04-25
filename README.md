# 使用网格搜索优化CatBoost参数
该文件参考格里菲斯大学研究员James Lyons的文章《Using Grid Search to Optimise CatBoost Parameters》，
地址：https://effectiveml.com/using-grid-search-to-optimise-catboost-parameters.html
中文介绍：https://cloud.tencent.com/developer/news/171443

在参数搜索中，由于不同的参数组合太多，故使用局部网格搜索，而不是全网格搜索，最终得到相当接近最优设定的结果。
