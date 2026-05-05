\# hw07 - 胸部 X 光肺炎影像二分类
\## 文件结构
hw07/
├── train.ipynb # 完整代码
├── report.md # 实验报告
├── README.md # 本文件
└── figures/
├── training\_curves.png # 训练/验证 Loss 与 Accuracy 曲线
└── confusion\_matrix.png # 测试集混淆矩阵
\## 运行环境
\- \*\*平台\*\*：Kaggle Notebook
\- \*\*Python 版本\*\*：3.14
\- \*\*主要依赖\*\*：TensorFlow, Keras, scikit-learn, Matplotlib, Seaborn, Pandas, NumPy, kagglehub
\## 一键运行方式
1\. 打开 Kaggle，创建新 Notebook
2\. 运行以下代码自动下载数据集：
&#x20;  ```python
&#x20;  import kagglehub
&#x20;  kagglehub.dataset\_download("paultimothymooney/chest-xray-pneumonia")
