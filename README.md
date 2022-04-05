# -
使用VGG16网络模型训练数据和微调ResNet50训练数据进行图像识别
pip install tensorflow==2.6.0
pip install requirements.txt
train-VGG16:
      python main.py
train-ResNet50:
      python mainResNet50.py
predict:
      cd Flask
      python Flask.py
