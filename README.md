# captcha-breaking

### Model
AlexNet (https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf) implementation in Tensorflow. Train on Imagenet dataset.

### CAPTCHAs
This project will iterate through the Google reCaptcha dataset (https://www.cs.columbia.edu/~suphannee/captcha/datasets/recapt_offline.tar.gz) which contains 700 CAPTCHA challenges (7,000 images) collected from Google reCaptcha version 1.0 (early - mid 2015). One challenge contains 10 images i.e., one example image and nine candidate images, and instruction text for human. For each CAPTCHA, the model will return the indices of the matching candidate images.

![alt text] (https://github.com/ninkle/captcha-breaking/blob/master/ex_img_captcha_recapt.png)
