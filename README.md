# aiffel-exp-1
AIFFEL Exploration Node 1. 인공지능과 가위바위보 하기

## Over Fitting 줄이기
- ### 표준 Dataset 사용 (Quantity and Quality)
  - Rock Paper Scissors Dataset
    - https://www.tensorflow.org/datasets/catalog/rock_paper_scissors
- ### Train / Validation 데이터 70:30으로 배분
- ### BatchNormalization & DropOut
- ### Conv - DropOut - BatchNorm - Activation 순서로 구성
  - https://stackoverflow.com/questions/39691902/ordering-of-batch-normalization-and-dropout
- ### Regularization
- ### Early Stopping
- ### 동일 퍼포먼스에서 사이즈가 작은 모델 선택
  - 8 16 32 64 vs ~16 32 64 128~
- ### 1000 Epoch Visualization 이후 OverFitting 발생 지점 확인 
  - ![image](https://user-images.githubusercontent.com/31565895/148012497-69301db7-a458-4b00-9ccd-7495645d80a7.png)

## 결과
- ### 1회 시도
  - test_loss: 0.5142398476600647 <br/>
  - test_accuracy: 0.8467742204666138 <br/>
- ### 2회 시도
  - test_loss: 1.0630570650100708  <br/>
  - test_accuracy: 0.725806474685669 <br/>
- ### 3회 시도
  - test_loss: 0.6379392147064209 <br/>
  - test_accuracy: 0.8118279576301575 <br/>
