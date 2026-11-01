# InsPLAD：无人机电力线路资产巡检数据集与基准
InsPLAD 是面向无人机电力线路视觉巡检的大规模真实数据集与基准，旨在解决行业缺乏公开真实数据集的问题，助力电力线路自动化巡检研究。
无人机电力线路巡检检测数据:中5种资产存在6种缺陷：4种为腐蚀，1种为部件损坏，1种为存在鸟巢
## 核心信息
- 数据规模：**10,607 张高分辨率无人机彩色图像**
- 资产类型：覆盖**17 种电力线路资产**
- 缺陷类型：5 种资产含**6 类缺陷**（4 类腐蚀、1 类部件破损、1 类鸟巢）
- 标注方式：图像级标注，区分资产正常/缺陷状态

## 支持任务
1. 目标检测：识别 17 类电力线路资产
2. 缺陷分类：对 5 种资产的缺陷做监督分类
3. 异常检测：基于无监督方法区分正常/异常资产

## 数据集特点
- 真实场景挑战：含多尺度目标、背景杂乱、遮挡、光照变化、视角差异等
- 行业首创：首个覆盖多组件与缺陷的电力线路巡检大型真实基准
- 任务全面：同时支撑目标检测、缺陷分类、异常检测三类视觉任务

## 评估指标
- 目标检测：平均精度（AP）
- 缺陷分类：平衡准确率
- 异常检测：AUROC

## 相关论文
1. *InsPLAD: A Dataset and Benchmark for Power Line Asset Inspection in UAV Images*，International Journal of Remote Sensing
2. *Attention Modules Improve Image-Level Anomaly Detection for Industrial Inspection: A DifferNet Case Study*，2024 IEEE/CVF WACV

![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/f3782aa81a3d4ac99853240054b3d656.png)
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/b211052bc1ae4bf58fcb17ef79785100.png)
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/1e255b643ca44c159204341f3be8e3d1.png)


---
**标签**：电力线路巡检、无人机、计算机视觉、数据集、目标检测、缺陷分类、异常检测、深度学习、工业检测
