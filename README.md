# self-driving-only-use-cnn

前向传播直接：
python3 drive.py saved_models/track1/model.pb

然后将模拟器打开，选择对应的路


训练：
python3 train.py -d ./data -s saved_models/track2

ckpt====> pb

python3 freeze.py -m saved_models/track2
