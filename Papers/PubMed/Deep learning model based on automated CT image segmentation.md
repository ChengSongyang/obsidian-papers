---
title: "Deep learning model based on automated CT image segmentation for predicting the optimal radiotherapy protocol in limited-stage small cell lung cancer patients: a multicenter study."
title_cn: "基于自动CT图像分割的深度学习模型预测局限期小细胞肺癌最优放疗方案：多中心研究"
authors: "Junfeng Zhao, Zongqian Yuan, Jinquan Yao, Ying Li, Haining Luo, Chengxin Liu"
date: 2026-05
source: "PubMed"
journal: "Translational lung cancer research"
url: "https://pubmed.ncbi.nlm.nih.gov/42170253/"
doi: "10.1093/jrr/rrx102"
tags: [SCLC, radiotherapy, deep-learning, CT-segmentation, treatment-planning]
---

# 基于自动CT图像分割的深度学习模型预测局限期小细胞肺癌最优放疗方案：多中心研究

## 基本信息
- **原标题**：Deep learning model based on automated CT image segmentation for predicting the optimal radiotherapy protocol in limited-stage small cell lung cancer patients: a multicenter study.
- **来源**：PubMed
- **期刊/会议**：Translational lung cancer research
- **日期**：2026-05
- **作者**：Junfeng Zhao, Zongqian Yuan, Jinquan Yao, Ying Li, Haining Luo, Chengxin Liu
- **链接**：[https://pubmed.ncbi.nlm.nih.gov/42170253/](https://pubmed.ncbi.nlm.nih.gov/42170253/)
- **DOI**：10.1093/jrr/rrx102

## 摘要
BACKGROUND: Radiotherapy combined with chemotherapy is the standard treatment regimen for patients with limited-stage small cell lung cancer (LS-SCLC), but the optimal radiotherapy regimen for these patients remains unclear. This study aims to construct an integrated, two-stage "image segmentation-response prediction" deep learning (DL) framework. By leveraging automated tumor segmentation to accurately define tumor habitats, this framework extracts deep imaging features to predict the optimal radiotherapy regimen for LS-SCLC patients. METHODS: This study enrolled patients with LS-SCLC who received chemoradiotherapy at two centers. Center A (Shandong Cancer Hospital and Institute, Shandong First Medical University and Shandong Academy of Medical Sciences) serves as the development cohort, while Center B (Xiaogan Central Hospital) functions as the external validation cohort. To establish the prediction framework, we first employed the VISTA3D model, integrating automatic and point-prompt guidance, to achieve highly precise three-dimensional (3D) tumor segmentation of the primary tumor lesion and its peritumoral habitats. Subsequently, the segmented target regions were fed into a ResNet18-based dual-branch DL model to extract deep radiomic features and generate treatment preference scores, thereby establishing a highly automated and interactive DL model to predict the optimal radiotherapy regimen by differentiating the expected progression-free survival (PFS) between hyperfractionated and conventionally fractionated regimens. Model performance is evaluated using metrics such as area under the curve (AUC). RESULTS: This study involved 446 patients. When performing automatic segmentation using the VISTA3D segmentation model, the model achieved a Dice coefficient of 0.86±0.17 on the external validation cohort, with an AUC of 0.88 [95% confidence interval (CI): 0.71-0.96]. Among patients with a score >0.5 (indicating a predicted survival benefit from hyperfractionated radiotherapy), PFS and overall survival (OS) analyses demonstrated that patients receiving hyperfractionated radiotherapy showed significantly superior outcomes compared to those receiving conventionally fractionated radiotherapy [hazard ratio (HR) =0.55, P<0.001; HR =0.39, P<0.001]. In patients with a score ≤0.5 (indicating no predicted superior benefit from hyperfractionation), there was no significant difference in PFS and OS between those receiving hyperfractionated radiotherapy and those receiving conventional fractionated radiotherapy (HR =1.12, P=0.83; HR =1.14, P=0.85). However, the incidence of grades 3-4 acute esophagitis was significantly lower in patients receiving conventional fractionation radiotherapy (16.0% vs. 9.4%, P<0.01). CONCLUSIONS: The DL model developed in this study, based on automatic segmentation combined with point-prompt technology, can replace prediction models based on manual segmentation. This model effectively assists clinicians in predicting the optimal radiotherapy regimen for LS-SCLC patients, validating the feasibility of a two-stage automated and interactive prediction framework integrating "image segmentation-response prediction". This approach can provide support for clinical decision-making in patients with LS-SCLC, advancing the process of personalized and precision cancer treatment.

## 深度总结

**1. 研究背景与大问题**
放疗联合化疗是局限期小细胞肺癌（LS-SCLC）的标准治疗方案，但最优放疗方案仍不清楚。超分割和常规分割方案各有优劣，缺乏个体化选择工具。如何利用影像学特征预测最优放疗方案是临床需求。

**2. 具体研究问题**
（1）能否构建两阶段"图像分割-反应预测"深度学习框架？（2）自动肿瘤分割能否准确定义肿瘤栖息地？（3）深度影像组学特征能否预测最优放疗方案？

**3. 研究方法**
纳入两个中心接受放化疗的LS-SCLC患者。中心A（山东省肿瘤医院）为开发队列，中心B（孝感市中心医院）为外部验证队列。首先使用VISTA3D模型（整合自动和点提示引导）实现精确三维肿瘤分割（原发肿瘤及周围栖息地）。然后将分割靶区输入基于ResNet18的双分支深度学习模型，提取深度影像组学特征，生成治疗偏好评分，区分超分割和常规分割方案的预期无进展生存期（PFS）差异。

**4. 主要发现**
共纳入446例患者。VISTA3D分割模型在外部验证队列上Dice系数0.86±0.17，AUC 0.88（95% CI: 0.71-0.96）。评分>0.5的患者（预测超分割方案有生存获益）中，超分割方案的PFS显著优于常规分割。

**5. 结论与意义**
该深度学习框架实现了高度自动化的LS-SCLC最优放疗方案预测，具有辅助临床决策的潜力。VISTA3D自动分割模型表现优异，双分支深度学习模型可有效提取预测性影像组学特征。

**6. 局限性与展望**
回顾性研究设计，需前瞻性验证。模型在不同中心间的泛化性需进一步评估。未来可整合更多临床特征（如基因组数据）提升预测性能。

## 个人笔记
（待补充）

---
*Generated by Hermes Paper Monitor - 2026-05*
