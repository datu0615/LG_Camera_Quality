# LG_Camera_Quality
![20220524_130537](https://user-images.githubusercontent.com/84311270/169976120-beefd4cb-9c09-4d84-be0b-90474ddec364.png)
๐๋น ๋ฒ์ง์ผ๋ก ์ ํ๋ ๐ท์นด๋ฉ๋ผ ์ด๋ฏธ์ง ํ์ง์ ํฅ์์ํค๋ AI ๋ชจ๋ธ ๊ฐ๋ฐ

## Dataset
a. train.csv : ํ์ต ์ด๋ฏธ์ง ๋ฐ์ดํฐ ์ ๋ณด  
img_id : ๋ฐ์ดํฐ ๊ณ ์  id  
input_img : ์๋ ฅ ๋ฐ์ดํฐ ํ์ผ๋ช  
label_img : label ๋ฐ์ดํฐ ํ์ผ๋ช  

b. train_input_img.zip : ํ์ต ์๋ ฅ ๋ฐ์ดํฐ  
train_input_10000.png  
train_input_10001.png  
train_input_10002.png  
...  

c. train_label_img.zip : ํ์ต label ๋ฐ์ดํฐ  
train_label_10000.png  
train_label_10001.png  
train_label_10002.png  
...  

d. test.csv : ํ์คํธ ์ด๋ฏธ์ง ๋ฐ์ดํฐ ์ ๋ณด  
img_id : ๋ฐ์ดํฐ ๊ณ ์  id  
input_img : ํ์คํธ ์๋ ฅ ๋ฐ์ดํฐ ํ์ผ๋ช  
submission_name : ์ ์ถ ์ด๋ฏธ์ง ํ์ผ ์ด๋ฆ  

e. test_input_img.zip : ํ์คํธ ์๋ ฅ ๋ฐ์ดํฐ  
test_input_20000.png  
test_input_20001.png  
test_input_20002.png  
...  

f. sample_submission.zip : ์ ์ถ ์์  
test_20000.png  
test_20001.png  
test_20002.png  
...  

## Model
AutoEncoder ๋ชจ๋ธ๊ณผ Pix2Pix ๋ชจ๋ธ์ ์ฌ์ฉํ์ฌ ํ์ต์ ์งํ. ์ต์ข์ ์ผ๋ก ResNetV2 + UNet ๋ชจ๋ธ์ ์ฌ์ฉํ์ฌ ํ์ต.
