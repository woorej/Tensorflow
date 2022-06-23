# Tensorflow로 구현한 모델

3가지 종류

1. 직접 모델을 만드는 코드
2. 함수로 만든 모델
3. 클래스 상속을 통해 구현한 모델

---------

dataset : Mnist, Fashion Mnist  

## Mnist & Fashin Mnist :

input shape : 28x28   
class : 10   
loss function : sparse_categorical_crossEntropy  
optimizer = Adam  

## Model Summery :

input_shape -> 128 nodes -> Relu -> Dropout -> output(class)
