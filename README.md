# CNN on CIFAR-10 

1. The model consist of 6 `Convolution` and 4 `Maxpool` layers
2. `Batchnormalization` is used with every convolution layer along with `Dropout` layers for regularization
3. The model uses `Adam` optimizer with a reduced learning rate (1e-4), which deals very well with overfitting
4. It was trained at 50 epochs at gave a validation accuracy of 87% without augmentation
