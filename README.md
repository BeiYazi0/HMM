# 隐马尔科夫模型

我们将根据观测序列构建一个 HMM（学习问题），并实现 viterbi 算法，从而能够使用模型根据观测序列求解隐藏状态的序列（解码问题）。

## 拉取仓库

```
git clone https://github.com/BeiYazi0/HMM
```

## 设置

创建并激活环境

```
conda create -n ai_env python=3.7
conda activate ai_env
```

安装依赖

```
cd HMM
pip install -r requirements.txt
```

## Jupyter

在`notebook.ipynb`中提供了进一步的说明。运行:

```
jupyter notebook
```
