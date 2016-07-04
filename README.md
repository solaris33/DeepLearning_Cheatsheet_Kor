# DeepLearning Cheatsheet Kor
한눈에 살펴보는 딥러닝 관련 용어들
# Vanishing Gradient Problem (경사 사라짐 문제)
Neural Netowkrs는 Backpropagation 알고리즘을 통해 최상단의 레이어(아웃풋 레이어)로부터 최하단의 레이어(인풋 레이어)까지 오류를 역전파하는 방식으로 데이터에 적절한 파라미터 값을 같도록 학습을 진행한다. 이때 히든 레이어를 여러층 쌓게 되면 아웃풋 레이어로부터 오류가 역전파되면서 오류의 정보를 갖고 있는 경사값이 중간 히든레이어에서 사라지고 최하단의 인풋레이어까지 이 정보값이 전달되지 않는 문제가 있었다. 이런 문제를 Vanishing Gradient Problem(경사 사라짐 문제)라고 한다. 이는 기존의 Neural Networks를 깊게(Deep) 쌓게 하지 못하는 근본적인 원인이었다. 이 문제를 해결하기 위해 Pre-training과 LSTM Networks등의 방법이 제안되었고 현재는 이 문제를 상당 부분 해결했기 때문에 딥 러닝(Deep Learning)이 좋은 퍼포먼스를 보여주고 있다. 


# Autoencoder

# Convolutional Neural Networks 

# ReLU

# Dropout
