# 环境配置

```bash
# 新建虚拟环境
conda create -n pytorch_env python=3.8

# 安装 cpu pytorch
conda install pytorch torchvision torchaudio cpuonly -c pytorch

# 设置 jupyter
conda install ipykernel
conda install -n pytorch_env ipykernel
python -m ipykernel install --user --n pytorch_env --display-name "pytorch_env"
conda install nb_conda

```

![image-20210819100519644](C:\Users\DELL\AppData\Roaming\Typora\typora-user-images\image-20210819100519644.png)





# 中文教程

https://pytorch.apachecn.org/docs/1.4/

[Welcome to PyTorch Tutorials — PyTorch Tutorials 1.9.0+cu102 documentation](https://pytorch.org/tutorials/)

