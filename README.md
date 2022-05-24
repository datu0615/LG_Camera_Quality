# LG_Camera_Quality
![20220524_130537](https://user-images.githubusercontent.com/84311270/169976120-beefd4cb-9c09-4d84-be0b-90474ddec364.png)
🌟빛 번짐으로 저하된 📷카메라 이미지 품질을 향상시키는 AI 모델 개발

## Dataset
a. train.csv : 학습 이미지 데이터 정보  
img_id : 데이터 고유 id  
input_img : 입력 데이터 파일명  
label_img : label 데이터 파일명  

b. train_input_img.zip : 학습 입력 데이터  
train_input_10000.png  
train_input_10001.png  
train_input_10002.png  
...  

c. train_label_img.zip : 학습 label 데이터  
train_label_10000.png  
train_label_10001.png  
train_label_10002.png  
...  

d. test.csv : 테스트 이미지 데이터 정보  
img_id : 데이터 고유 id  
input_img : 테스트 입력 데이터 파일명  
submission_name : 제출 이미지 파일 이름  

e. test_input_img.zip : 테스트 입력 데이터  
test_input_20000.png  
test_input_20001.png  
test_input_20002.png  
...  

f. sample_submission.zip : 제출 양식  
test_20000.png  
test_20001.png  
test_20002.png  
...  

## Model
AutoEncoder 모델과 Pix2Pix 모델을 사용하여 학습을 진행. 최종적으로 ResNetV2 + UNet 모델을 사용하여 학습.
