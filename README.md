# CNN model for CIFAR-10 

1. The model consist of 6 `Convolution` and 4 `AveragePooling` layers
2. `Batchnormalization` is used with every convolution layer along with `Dropout` layers for regularization
3. The model uses `Adam` optimizer with reducing learning rate 
4. It was trained at 30 epochs and gave an `val_loss` of 0.3556 and `val_accuracy` of 88.39% 

# Confusion Matrix

![image](https://user-images.githubusercontent.com/77575222/155411856-85f88a18-c27e-42be-9508-06aca30ac508.png)

