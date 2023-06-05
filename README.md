# cifar10_hw
cifar10 experiments

ex1 ~ ex5_ensemble 실험 진행 결과
ex1의 결과가 제일 좋았어서 최종적으로 ex1 결과로 제출합니다.

ex1 : Loss : CrossEntropyLoss , optimizer : SGD , scheduler : StepLR \
ex2 : Loss : FocalLoss, optimzier : Adam, StepLR \
ex3 : Loss : CrossEntropyLoss , optimzier : Adam , scheduler : StepLR \
ex4 : Loss : FocalLoss , optimizer : SGD , scheduler : StepLR \
ex5_ensemble : ex1-> 2 , ex2 -> 1, ex3 -> 2, ex4 -> 2 / 총 6개 모델 ensemble \
