# Traffic_signs_classification_pytorch
CNN model trained to classify traffic signs with 90% accuracy
Built in pytorch a 2 hidden-layer Convolutional Neural Networks (CNN) trainned to recognize different traffic signs type.

## import dataset
* Download the [traffic signs dataset](https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign/download)

## CNN model used 
Net(
  (conv1): Conv2d(3, 32, kernel_size=(3, 3), stride=(1, 1))
  
  activation:relu
  
  pool: max_pool
  
  (conv2): Conv2d(32, 64, kernel_size=(3, 3), stride=(1, 1))
  
  activation:relu
  
  pool: max_pool
  
  (fc1): Linear(in_features=1600, out_features=128, bias=True)
  
  (fc2): Linear(in_features=128, out_features=43, bias=True)
  
)
Accuracy achieves ~90% over 5 epochs

Accuracy/val_accuracy visualization during training progress:

[![accuracy plot](https://github.com/xuegoleta/Traffic_signs_classification_pytorch/blob/main/images/accuracy_plot.png)] 
