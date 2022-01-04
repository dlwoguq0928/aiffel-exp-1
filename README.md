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
  - 실험 결과 validation loss가 오히려 더 높게 나와서 제외함
- ### Early Stopping
- ### 동일 퍼포먼스에서 사이즈가 작은 모델 선택
  - 8 16 32 64 vs ~16 32 64 128~

## 결과
- ### 1회 시도
  - test_loss: ??? <br/>
  - test_accuracy: 0.33??? <br/>
- ### 2회 시도
  - test_loss: 0.5974062085151672 <br/>
  - test_accuracy: 0.8763440847396851 <br/>
- ### 3회 시도
  - test_loss: 0.3519209921360016 <br/>
  - test_accuracy: 0.9005376100540161 <br/>
