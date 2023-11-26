# k-ict(2023-10 ~ 2023-11)

### 이미지 분류(음식이미지) 프로젝트

# 1. 데이터(이미지) 전처리
### 1) 이미지들의 평균 RGB, 분산으로 정규화 진행
### 2) Geometric transformation, randaugment를 이용한 data augmentation
### 3) Mixup , Cutmix를 이용한 data augmentation


# 2. 추가 고도화 방법 및 설정
### 1) label smoothing
### 2) Lr Scheduler 보다 가중치를 저장하며 Lr 낮춰줌
### 3) optimizer : Adam , loss_func : CrossEntropyLoss
### 4) resnet 모델만 허용되었기 때문에 18~151 비교하며 최종선택 101

