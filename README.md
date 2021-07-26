Styletransform:-

1) implemented using torchvision
2) vgg19 pretrained model is used from torchvision models
3) initial 6 pretrained convolution layers are taken from vgg19 model to build our style transform model.
4) gram matix method is used to extract style information from style image.
