# Transfer-Learning-CNN-Using-VGG16

  Applying concepts learned in Transfer Learning.
  
  Dataset link : https://www.kaggle.com/datasets/brahma0545/aaic-assignment-tl?datasetId=836734&select=data_final
  

    Three models are built :
        1.  Use VGG-16 pretrained network without Fully Connected layers and initilize all the weights with Imagenet trained weights.After VGG-16 network without FC layers, add a new Conv block ( 1 Conv layer and 1 Maxpooling ), 2 FC layers and an output layer to classify 16 classes. You are free to choose any hyperparameters/parameters of conv block, FC layers, output layer. 
        2.  Use VGG-16 pretrained network without Fully Connected layers and initilize all the weights with Imagenet trained weights.After VGG-16 network without FC layers, don't use FC layers, use conv layers only as Fully connected layer.Any FC layer can be converted to a CONV layer. This conversion will reduce the No of Trainable parameters in FC layers.
        3.  Use same network as Model-2 'INPUT --> VGG-16 without Top layers(FC) --> 2 Conv Layers identical to FC --> Output Layer' and train only Last 6 Layers of VGG-16 network, 2 Conv layers identical to FC layers, 1 output layer.
        
    Summary of Three models:
        <img width="269" alt="image" src="https://user-images.githubusercontent.com/55178845/204604754-8df76fba-9d62-47e2-bcdd-498fcac40679.png">
