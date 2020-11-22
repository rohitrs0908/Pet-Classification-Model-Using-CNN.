# Pet-Classification-Model-Using-CNN.
Pet Classification Model Using CNN.
DESCRIPTION
Build a CNN model that classifies the given pet images correctly into dog and cat images. 
The project scope document specifies the requirements for the project “Pet Classification Model Using CNN.” Apart from specifying the functional and nonfunctional requirements for the project, it also serves as an input for project scoping. 
Project Description and Scope 
You are provided with the following resources that can be used as inputs for your model: 
1. A collection of images of pets, that is, cats and dogs. These images are of 
different sizes with varied lighting conditions. 2. Code template containing the following code blocks: 
a. Import modules (part 1) b. Set hyper parameters (part 2) c. Read image data set (part 3) d. Run TensorFlow model (part 4) 
You are expected to write the code for CNN image classification model (between Parts 3 and 4) using TensorFlow that trains on the data and calculates the accuracy score on the test data. 
Project Guidelines 
Begin by extracting ipynb file and the data in the same folder. The CNN model (cnn_model_fn) should have the following layers: 
● Input layer 
● Convolutional layer 1 with 32 filters of kernel size[5,5] 
● Pooling layer 1 with pool size[2,2] and stride 2 
● Convolutional layer 2 with 64 filters of kernel size[5,5] 
● Pooling layer 2 with pool size[2,2] and stride 2 
● Dense layer whose output size is fixed in the hyper parameter: fc_size=32 
● Dropout layer with dropout probability 0.4 
Predict the class by doing a softmax on the output of the dropout layers. 
This should be followed by training and evaluation: 
1 | Page ©Simplilearn. All rights reserved 
● For the training step, define the loss function and minimize it 
● For the evaluation step, calculate the accuracy 
Run the program for 100, 200, and 300 iterations, respectively. Follow this by a report on the final accuracy and loss on the evaluation data. 
