#### 데이터의 불균형과 클래스간 모호한 이미지들이 존재하여, 
#### focal Loss와 일반화를 위한 Augmentation, Label Smoothing을 적용하였다.


##### private: 0.66704 (54/1025) 
###### Model: Swin Transformer_B 
###### Loss: Label Smoothing Loss + Focal Loss
###### lr: 3e-5
###### epoch:50
###### Batch size: 16
###### Augmentation: VerticalFlip, RandomBrightness, CLAHE, Cutmix, Cutout
