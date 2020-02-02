# RawData

[POLARDB产品架构与实现](http://www.orczhou.com/index.php/2019/12/polardb-implement-g/)
[本地路径](https://github.com/ChengXiaoZ/RawData/blob/master/file/POLARDB%E4%BA%A7%E5%93%81%E6%9E%B6%E6%9E%84%E4%B8%8E%E5%AE%9E%E7%8E%B0-%E5%91%A8%E6%8C%AF%E5%85%B4_compressed.pdf)

[percona-rds的优点](https://www.percona.com/blog/2019/12/19/the-benefits-of-amazon-rds-for-mysql/)

以下几点Easy Deployment、Fast Storage Options、Backup & Recovery、High Availability、Monitoring/Metrics、Security

备份：功能、正确性、性能、资源
原理、案例、对比
- 全量备份&恢复
  - 物理
    - 文件拷贝
      - pg
      - mysql
    - 快照
      - 步骤
        - 创建
        - 保存
        - 加载
          - 同步
          - 异步
      - lvm
  - 逻辑
    - pg
    - mysql
- 增量备份&恢复
  - 物理
    - pg
  - 逻辑
    - mysql
    - pg
- 闪回
  - 物理
    - pg
  - 逻辑
    - mysql
  - aurora
- 原地clone
  - aurora

