# MNIST-multi-label-classification-withPytorch
MNIST-multi-label-classification-with Pytorch DeepLearning

### Download the Dataset
### torchvision.datasets.MNIST
- torchvision.datasets 에 다양한 datasets 이 있음
- MNIST dataset (숫자 필기체)
  - 60,000 training 이미지, 10,000 test 이미지 (28 pixels X 28 pixels)
  - torchvision.datasets.MNIST(root='저장할폴더위치', train=True, download=True, transform=transforms.ToTensor())
    - train 이 True 이면 train 데이터, False 이면, test 데이터
    - download 가 True 이면, root 의 지정한 폴더에 데이터가 없으면, 다운로드 받음
    - transform=transforms.ToTensor() - 데이터 타입을 Tensor 형태로 변경m
    
- 참고: https://pytorch.org/vision/stable/generated/torchvision.datasets.MNIST.html#torchvision.datasets.MNIST

# Result
Average Test Loss: 0.0006
Accuracy: 9808/10000 (98.08%)
