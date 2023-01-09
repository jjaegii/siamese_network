# 샴네트워크 train inference 기능

## 설정 방법

train.py와 inference.py에서 dset.ImageFolder(root=)에서 root 부분을 train dataset 폴더의 경로로 설정



## 실행 방법

python3 app.py

1 -> 100에포크 학습

2  -> 추론할 이미지 경로 입력 -> 추론 (가장 거리값이 가까운 것으로 나옴)