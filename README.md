# HR Promotion Evaluator

### 组织诊断与人才评价专家 · Organization Diagnostics & Talent Assessment

An expert system for executive promotion, succession planning, and talent review in large organizations (10,000+ employees). Uses a 6-dimension evaluation framework with **Stack Ranking**, **9-box grid placement**, and **appointment recommendations**.

适合万人规模企业 HRD / CHRO / 干部管理团队在竞聘、晋升、人才盘点场景使用。

---

## 核心能力

| 能力 | 说明 |
|------|------|
| **六维透视模型** | 业绩锚点→管理行为→机制杠杆→关键胜仗→规模推演→红利剔除，六层穿透 |
| **强制绝对排序** | 同一九宫格位置也强制分出名次，杜绝并列 |
| **交叉验真** | 简历 ↔ 述职报告 ↔ 答辩纪要三方对照，识别逻辑裂痕 |
| **速度分级** | 极速（3分钟出结论）/ 标准 / 深度三档，适配评委会现场到关键岗位任命不同场景 |
| **可视化输出** | HTML表格 + 色阶背景 + 排名/任用/绩效标签徽章，决策层一目了然 |
| **红利分离** | Alpha/Beta 拆解，区分"平台红利"与"个人管理增量" |

## 速度模式

| 模式 | 场景 | 耗时 |
|------|------|------|
| ⚡ 极速 | 答辩现场即时出结论 | ~2-3 min |
| 🕐 标准 | 常规竞聘评审 | ~5-8 min |
| 🔬 深度 | 关键岗位任命/CEO-1级 | ~10-15 min |

## 安装

```bash
claude plugin install HR-promotion-evaluator@luobaopeng-hash
```

## 使用方式

上传候选人材料（简历 + 述职报告 + 答辩纪要），直接说明场景即可触发：

```
这是一组客户区域经理候选人材料，帮我做一个竞聘评估
```

如需赶时间：
```
快速出结论，赶着上评委会
```

触发词：`竞聘` `干部选拔` `人才评价` `晋升` `述职评估` `人才盘点` `九宫格` `任用建议` `HR评审` `promotion evaluation` `talent assessment`

## 版本

v5.6 — 新增速度分级 + HTML可视化表格输出

## License

MIT
