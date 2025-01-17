# Test Case 

测试用例的由来:

![](./product-dev-simple.png)

***通过测试用例验证开发结果是否满足产品需求***

---

## 什么是测试用例 

什么是测试用例？

> Test cases are instructions for testers to follow to ensure programs are functioning properly.

测试用例是一种知道指导说明用来验证程序是否工作正常.

---

## 测试用例Cheatsheet

![](./testcase-overview.png)

---

## 测试场景 VS 测试用例

![](./testcase-testscenario.png)

---

## 测试用例实际使用

1. 测试用例用作开发自测标准
2. 测试用例用作测试标准/Bug确认标准
3. 最为测试工作的最小单元可以组合成:
   1. 测试场景
   2. 满足测试需求,比如回归测试,迭代测试.....
4. 帮助确认测试/产品开发进度
5. 反应实际产品的现实

---

## 测试用例相关流程

- 用例Review: 确认测试用例有效和功能范围
- 测试场景选择: 选择需要的测试用例作为测试场景的子用例
- 测试计划: 选择需要的测试用例/测试场景制定测试计划
- 测试用例执行: 执行测试用例, 确认测试结果,反应实际进度
- 某种程度上也是需求文档的细化

---

## 测试用例的重要

- 记录完整的产品功能细节
- 通过测试用例可以进行测试工作更细致的分配，协调和协作
- 在一定时间中的工作/功能标准，用于验证
- 产品功能知识的分享

---

## 现实的困难和痛点

- 维护成本高,比如需要花费大量时间写操作步骤
- 维护困难,需要持续更新
- 用例过于表面话,隐含知识多,并没有起到太好的知识分享功能
- 重点不够突出，用例数量很多
- 好用的管理工具不多,维护非常繁琐，比如:
  - 重复用例多
  - 不容易及时更新
  - 使用EXCEl等工具，不容易分享和协作
  - 维护耗时时间长
  - UI细节用例很难维护
---

## 测试用例管理策略

功能测试用例：
- 测试用例场景化，减少UI细节维护，突出重点
- UI细节用例，单独列出
- 测试用例场景可以组合
- 测试用例分优先级处理

---

## 相对最容易解决的问题

- 测试用例仓库: 测试用例场景化后集中保存
  - 分模块
  - 分优先级
  - 回归测试用例标签
- 测试场景通过测试用例组合完成
  - 组合常见回归测试用例
  - 组合常见场景
- 测试计划通过测试用例和测试场景组合完成
- 测试结果通过测试用例记录完成，如果修改测试用例也一同修改被原来测试用例
- 测试进度追踪和报告

---

## What/Why/How

- What: Test Cases stored,composed,shared, and tracked
- Why:  collobration!

---

## Pain Points

![](/images/painpoints.png)

---

And Even more:

- How to extract some Alice’s cases to Bob,reduce some duplicated jobs
- How Alice and Bob to co-work with one test cases sets
- .......