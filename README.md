# pytorch study

## BASE ENV
```shell
conda create -n pt python=3.10 -y

conda activate pt
```

## MAC
```shell
# 安装 pytorch v1.12版本已经正式支持了用于mac m1芯片gpu加速的mps后端
conda install pytorch::pytorch torchvision torchaudio -c pytorch -y

pip install -r requirements.txt
```

## MAC
```shell
# 安装 pytorch v1.12版本已经正式支持了用于mac m1芯片gpu加速的mps后端
conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia

pip install -r requirements.txt
```

## gpt4free
```
pip install -U g4f[all]
```