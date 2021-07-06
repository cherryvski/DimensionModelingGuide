# HowToBuildYourOwnDataWarehouse

本项目将讲述如何进行维度建模。

## 什么是维度建模

​	数据仓库的目标是方便用户存取、展示一致性的信息，并且能够输出可用于决策分析的有用的数据。建设数据仓库的核心便是维度建模。

​	维度建模是一种简化数据存储的方式，它能够让使用者更容易理解数据，并且提升数据查询性能，同时还能够灵活、快速地响应业务需求的变化。维度建模通过其构建的星型模型（Star Schema），将反映企业活动的度量与维度的关系反映出来，从而让使用者能够快速理解模型表达的内容，从而使用模型来开发相应的数据指标。同时，相比于3NF建模，维度建模允许冗余，因此在查询相同的数据的时候，维度建模能够减少关联查询的次数，从而提升查询的性能。并且，使用维度建模可以以迭代、增量的方式来建设整个数据仓库。

## 如何进行维度建模

[业务需求调研](https://github.com/cherryvski/HowToBuildYourOwnDataWarehouse/blob/main/doc/1.md)

[总线矩阵设计](https://github.com/cherryvski/HowToBuildYourOwnDataWarehouse/blob/main/doc/2.md)

[维度模型设计](https://github.com/cherryvski/HowToBuildYourOwnDataWarehouse/blob/main/doc/3.md)

## 如何规范维度建模的过程

