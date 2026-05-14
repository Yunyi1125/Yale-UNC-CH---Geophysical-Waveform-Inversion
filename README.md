# Yale / UNC-CH — Geophysical Waveform Inversion

参赛项目：[Kaggle · Yale/UNC-CH - Geophysical Waveform Inversion](https://www.kaggle.com/competitions/waveform-inversion/overview)

该赛题关注**地球物理全波形反演（FWI）**：从观测到的地震波形等信息中恢复地下介质属性，结合物理约束与机器学习/深度学习方法。

## 本仓库内容

| 文件 | 说明 |
|------|------|
| [`convnext_train.ipynb`](convnext_train.ipynb) | ConvNeXt 训练流程（全尺寸地震数据、非方形输入等；基于社区 HGNet-V2 starter 思路扩展） |
| [`caformer_train.ipynb`](caformer_train.ipynb) | CAFormer 相关训练实验 |

运行环境以 **Kaggle Notebook / GPU** 为主；依赖见各 Notebook 内 `pip` 与 `import`（如 PyTorch、MONAI 等）。

## 许可证与数据

竞赛数据与规则以 [Kaggle 赛题页面](https://www.kaggle.com/competitions/waveform-inversion/rules) 为准；本仓库仅包含个人代码与笔记，不含官方数据集。
