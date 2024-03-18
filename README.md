# Lab HomeWork
## 環境版本
- Python 3.9.6
- MacOS
- 

## START

### 建立虛擬環境
```zsh
python -m venv tutorial-env
```
### 進入 venv 虛擬環境
```zsh
source myenv/bin/activate
```
### 離開虛擬環境
```zsh
deactivate
```

## 安裝 python 套件
```zsh
pip3 install torch numpy matplotlib pillow torchvision torchsummary torchaudio
```


## 第一次訓練
- batch_size = 32 (Batch Size)
- lr = 1e-4 (Learning Rate)
- epochs = 10 (epoch 次數)
- optim.Adam

![Alt text](fig/firstTrain.png)
![Alt text](fig/firstLoss.png)

## 第二次訓練
- batch_size = 32 (Batch Size)
- lr = 1e-5 (Learning Rate)
- epochs = 50 (epoch 次數)
- optim.Adam

![Alt text](fig/secondTrain.png)

## 第三次訓練
- batch_size = 32 (Batch Size)
- lr = 1e-4 (Learning Rate)
- epochs = 50 (epoch 次數)
- optim.SGD

![Alt text](fig/thirdTrain.png)