# Medical Consumables QMS Starter

一次性医疗器械研发质量体系起点模板，面向一次性手术衣、手术铺单、隔离衣、医用手套、医用口罩、灭菌包布及相关无菌屏障/防护类耗材。

本仓库参考 ISO 13485 质量管理体系思路，以及 GSTT-CSC/QMS-Template 的“用 GitHub/Markdown 管理受控质量文件”的方式，但内容已改造成非软件类一次性医疗器械研发场景。

> 注意：本仓库是研发质量体系起点，不等于已经满足任何注册审评、认证或客户审核要求。使用前应结合目标市场法规、产品分类、适用标准、企业实际流程和质量负责人评审进行修订。

## 适用产品

- 一次性手术衣
- 一次性手术铺单、洞巾、器械台单
- 一次性隔离衣、防护服类产品
- 医用检查手套、外科手套
- 医用口罩、外科口罩、防护口罩
- 灭菌包布、无菌屏障包装材料
- 手术包、产包、护理包等组合包类产品

## 仓库结构

```text
01_Quality_Manual/
  Quality_Manual.md
02_SOP/
  SOP-001-Design-and-Development.md
  SOP-002-Risk-Management.md
  SOP-003-Verification-and-Validation.md
  SOP-004-Document-and-Record-Control.md
  SOP-005-Supplier-Management.md
  SOP-006-Nonconforming-Product-Control.md
  SOP-007-CAPA.md
  SOP-008-Labelling-and-IFU.md
  SOP-009-Monitoring-and-Feedback.md
  SOP-010-Management-Review.md
  SOP-011-Purchasing-and-Supplier-Verification.md
  SOP-012-Internal-Audit.md
03_Forms_Templates/
  F-001-Design-Plan.md
  F-002-Product-Requirements.md
  F-003-Risk-Analysis.md
  F-004-Verification-Validation-Plan.md
  F-005-Verification-Validation-Summary.md
  F-006-Change-Assessment.md
  F-007-Design-Review-Record.md
  F-008-Label-IFU-Review.md
  F-009-Feedback-Complaint-Record.md
  F-010-Nonconforming-Product-Report.md
  F-011-CAPA-Record.md
  F-012-Management-Review-Report.md
  F-013-Supplier-Verification-Record.md
  F-014-Internal-Audit-Report.md
04_Product_Projects/
  README.md
  Surgical_Gown_Level_3/README.md
05_Standards/
  standards-map.md
```

## 推荐使用路径

1. 指定质量负责人、研发负责人、法规负责人、生产/工艺负责人、采购/供应商质量负责人。
2. 先评审并改写 `01_Quality_Manual/Quality_Manual.md`，把组织、职责、产品范围和目标市场写清楚。
3. 评审 `02_SOP/` 中的核心流程，删除不适用内容，补充企业真实流程。
4. 选择一个试点产品，例如 AAMI PB70 Level 3 手术衣，复制 `04_Product_Projects/Surgical_Gown_Level_3/` 作为项目文件夹。
5. 使用 `03_Forms_Templates/` 完成设计计划、产品需求、风险分析、验证确认计划和验证总结。
6. 将所有测试报告、供应商资料、灭菌验证、包装验证、老化验证和设计评审记录链接到项目文件夹。
7. 跑完一个项目后进行内部复盘，补齐缺失 SOP 和模板。

## 文件控制建议

- 主分支保存已批准文件。
- 每次文件修订通过 Pull Request 审批。
- 文件头部保留版本、状态、批准人和生效日期。
- 质量负责人或其授权人员作为 CODEOWNER。
- 重要记录不得只保存在个人电脑，应进入受控仓库或企业文档系统。

## 常见目标市场和标准

标准版本会更新，注册前必须确认最新版和目标市场要求。建议先维护 `05_Standards/standards-map.md`，再映射到每个产品项目。
