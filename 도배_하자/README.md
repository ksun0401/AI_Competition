#### 데이터의 불균형과 클래스간의 모호한 이미지들이 존재하여, 일반화에 집중하였다.

Model: Swin Transformer_B 
Loss: Label smoothing Loss + Focal Loss
lr: 3e-5
epoch:50
Batch size: 16
Augmentation: VerticalFlip, RandomBrightness, CLAHE, Cutout, Cutmix
