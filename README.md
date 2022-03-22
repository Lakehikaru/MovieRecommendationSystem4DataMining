# MovieRecommendationSystem4DataMining

### 问题描述

#### 1、问题背景及分析

​		电影数据库（TMDB）是一个由社区建立和维护的电影和电视数据库。起始于2008年，每一条数据都是由社区成员添加，因此在数据准确性和数据容量上都十分出色。其中每个条目都包含了电影或剧集的名称，种类等基本信息。

​		由此，我们可以构建一个推荐系统，根据已有的数据构建模型，为用户提供电影推荐。

#### 2、问题描述

**2.1 数据准备**

使用[The Movies Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)和[TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)中的影视数据，对其进行数据预处理完成初步数据准备。

**2.2 准备采用的方法或模型**

准备结合使用多种推荐系统模型：基于大众喜好的筛选推荐；基于相似内容的推荐；基于相似用户的推荐来多样地完善推荐系统。

**2.3 预期的挖掘结果**

根据数据集建立模型，使得其可以获取最热门的影片，和查询结果内容相似的影片以及和相似爱好用户口味类似的影片。

### 项目评估

项目使用MAE和RMSE测量样本误差。






