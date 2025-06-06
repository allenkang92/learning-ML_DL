# Machine Learning & Deep Learning 학습 저장소

머신러닝과 딥러닝 학습 내용 정리

## 디렉터리 구조

```
/learning-ML_DL/
├── 01_machine_learning_concepts/  # 머신러닝 기본 개념
│   ├── 01_machine_learning.md     # 기본 용어 및 개념 정의
│   ├── 02_machine_learning.md     # 모델링 및 분석 개념
│   ├── 03_machine_learning.md     # 모델 선택 및 평가
│   ├── 04_modeling_and_selection.md # 모델링 및 선택
│   └── 05_advanced_modeling.md    # 표현 학습, 최적화, 모델 선택
├── 02_neural_networks/            # 신경망 관련 내용
│   ├── 01_perceptron_basics.md    # 퍼셉트론 기초
│   ├── 02_lightweight_models.md   # 최신 경량 딥러닝 모델 동향
│   ├── 03_numpy_neural_network.md # Numpy를 이용한 신경망 구현
│   ├── 04_deep_learning_fundamentals.md # 딥러닝/신경망 학습 기초
│   ├── 05_tensorflow_keras_basics.md # TensorFlow와 Keras 기초
│   ├── 06_convolutional_neural_networks.md # 컨볼루션 신경망(CNN)
│   ├── 07_transfer_learning.md    # 전이 학습과 사전 학습 모델 활용
│   ├── perceptron.py              # AND 게이트 구현 코드
│   ├── logistic_and_gate.py       # 로지스틱 회귀로 AND 게이트 구현
│   ├── softmax_and_gate.py        # 소프트맥스 회귀로 AND 게이트 구현
│   ├── multi_task_learning.py     # 다중 작업 학습 신경망 구현
│   └── mlp_xor_gate.py            # 다층 퍼셉트론으로 XOR 게이트 구현
└── code_examples/                 # 코드 예제
    ├── model_selection/
    │   └── knn_wine_selection.py  # KNN 모델 선택 예제
    ├── feature_selection/
    │   └── feature_selection_example.py # 특성 선택 기법 예제
    └── deep_learning/
        └── fashion_mnist_classification.py # Fashion MNIST 이미지 분류 예제
```

## 주요 내용

### 머신러닝 개념
- 머신러닝 기본 개념과 용어
- 모델링 접근 방식과 분석
- 모델 선택 및 평가
- 모델링 및 선택
- 표현 학습, 최적화, 고급 모델링 기법

### 신경망
- 퍼셉트론 기초와 구현
- 로지스틱 및 소프트맥스 회귀 구현
- 최신 경량 딥러닝 모델 동향
- Numpy를 이용한 신경망 구현 및 다중 작업 학습
- 다층 퍼셉트론(MLP)을 통한 XOR 문제 해결
- 딥러닝의 역사, 기초 개념 및 최적화 알고리즘
- TensorFlow와 Keras를 이용한 딥러닝 모델 구축 방법
- 컨볼루션 신경망(CNN)의 원리와 구조
- 전이 학습과 사전 학습 모델을 활용한 효율적인 모델링

### 코드 예제
- KNN을 이용한 와인 분류 및 모델 선택
- 다양한 특성 선택 기법 비교
- TensorFlow Keras를 이용한 Fashion MNIST 이미지 분류
