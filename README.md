# Algorithm_03
Repository for algorithm class project
### Open Source SW Project(Deep Learning)
### student id : 20186628


>This is an open source SW project which makes use of open source libraries to address simple hand-written digit classification problem.
>In this README.md, source code, classification result(accuracies) and success/failure cases(images) will be included.

### contents
+ About CNN model
+ For each of Model 1, Model 2 and Model 3, contents below are included.
  + Model Definition
  + Training Step
  + Test Step
  + Predict Success Case
  + Predict Failure Case
+ Graph of result  
  

## About CNN model

Advantages of Convolutional Neural Network Compared to previous Fully Connected Neural Network
Maintain dimensions. Do not flatten images.
Good for graphical analysis and better recognize features of adjacent parts as images.

The key to learning is convolutional kernel (filter).
As learning takes place, the filter changes to a role similar to the weight.
The convolutional layer is the role of finding the characteristics of the image.

Maxpool is a type of pooling layer.
Reduce the matrix size resulting from the convolution.
For Max pooling, the largest value is taken as the representative value.
There is also an average pooling.
The pooling layer strengthens the characteristics of the image

Convoultion Layer + Pooling Layer : Extracting image features

The Flatten Layer transforms data in the form of images into one dimension.
It transforms the Convolutional Neural Network type into a Fully Connected Neural Network type.

Dense Layer is Fully Connected Layer.
The Dense Layer maps flattened data to values between 0 and 9.
And the result of Dense Layer comes out as a representative value through softmax function.


Models 1,2,3 have 3, 5, and 7 layers respectively.
The details are as shown in the table below, and the code is also attached as a later image.
|Model 1|Model 2|Model 3|
|---|---|---|
|Convoultion|Convoultion|Convoultion|
|Maxpool|Maxpool|Maxpool|
|Flatten and Dense|Convolution|Convolution|
||Maxpool|Convolution|
||Flatten and Dense|Maxpool|
|||Convolution|
|||Flatten and Dense|




## Model 1
  1. Model Definition
<img width="534" alt="model1" src="https://user-images.githubusercontent.com/65612292/82408934-977d2b00-9aa7-11ea-9c40-b6594ba27437.png">
  2. Training Step
<img width="501" alt="train1" src="https://user-images.githubusercontent.com/65612292/82409437-b4fec480-9aa8-11ea-9893-5b4bcaa1d0c4.png">
  3. Test Step
<img width="396" alt="test1" src="https://user-images.githubusercontent.com/65612292/82409436-b4662e00-9aa8-11ea-851b-c745b45f416c.png">
  4. Predict Success Case
<img width="463" alt="success1" src="https://user-images.githubusercontent.com/65612292/82409434-b3350100-9aa8-11ea-8091-ad579a0b6eec.png">
  5. Predict Failure Case
<img width="660" alt="failure1" src="https://user-images.githubusercontent.com/65612292/82409439-b4fec480-9aa8-11ea-9e21-0592dd820f2b.png">


## Model 2
  1. Model Definition
<img width="535" alt="model2" src="https://user-images.githubusercontent.com/65612292/82408931-96e49480-9aa7-11ea-8794-7c08ce6694fa.png">
  2. Training Step
<img width="497" alt="train2" src="https://user-images.githubusercontent.com/65612292/82410260-78cc6380-9aaa-11ea-98fc-d3cd29569209.png">
  3. Test Step
<img width="392" alt="test2" src="https://user-images.githubusercontent.com/65612292/82410259-78cc6380-9aaa-11ea-8f6e-a98b3eaade16.png">
  4. Predict Success Case
<img width="463" alt="success2" src="https://user-images.githubusercontent.com/65612292/82410254-7702a000-9aaa-11ea-8fe2-91d0992b6a6e.png">
  5. Predict Failure Case
<img width="661" alt="failure2" src="https://user-images.githubusercontent.com/65612292/82410257-7833cd00-9aaa-11ea-91c8-ca5f859b25be.png">


## Model 3
  1. Model Definition
<img width="537" alt="model3" src="https://user-images.githubusercontent.com/65612292/82408929-95b36780-9aa7-11ea-9463-560794839130.png">
  2. Training Step
<img width="487" alt="train3" src="https://user-images.githubusercontent.com/65612292/82411841-81726900-9aad-11ea-83c5-d59275c93456.png">
  3. Test Step
<img width="388" alt="test3" src="https://user-images.githubusercontent.com/65612292/82411856-8800e080-9aad-11ea-9964-9c8f90be39bb.png">
  4. Predict Success Case
<img width="462" alt="success3" src="https://user-images.githubusercontent.com/65612292/82411864-8cc59480-9aad-11ea-9674-6eafdc7fb997.png">
  5. Predict Failure Case
<img width="662" alt="failure3" src="https://user-images.githubusercontent.com/65612292/82411881-9222df00-9aad-11ea-9535-0caa6aa54fbf.png">


When training with 3,5,7 layers of models
The result is that the accuracy is getting higher and the loss is getting lower.

The graph showing the results of loss and accuracy is shown below.

  
