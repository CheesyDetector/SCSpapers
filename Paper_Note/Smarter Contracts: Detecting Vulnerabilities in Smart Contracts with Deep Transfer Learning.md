## 现存问题
- 深度学习框架检测智能合约漏洞没有很好研究
- 现有合约漏洞检测工具可扩展性差，面对新的漏洞类型需要重新编写业务逻辑

## 贡献
- ESCORT高效、可扩展。并行检测多种漏洞类型
- ESCORT是第一个支持迁移学习的基于DNN框架的检测器。支持对新漏洞类型的迁移学习，解决了训练新任务的灾难性遗忘问题
- 在3,640,153个类EVM合约字节码上进行验证，在11个漏洞类型上达到平均0.15s和97%的F1分数
- 开发了Demeter工具链，自动爬取合约字节码并上标记
- 