# CReLU (Concatenated Rectified Linear Units)
CReLU (Understanding and Improving Convolutional Neural Networks via Concatenated Rectified Linear Units) with Caffe
Paper : https://arxiv.org/pdf/1603.05201v2.pdf

### Results

1-crop validation error on ImageNet (center 224x224 crop from resized image with shorter side=256):

	model|top-1|top-5
	:---:|:---:|:---:
	AlexNet|42.6%|19.6%  
	CReLU (all)|40.93%|19.39% 
	CReLU (conv1,4,7)|40.45 %|18.58% 
	**CReLU (conv1–4)**|**39.82**%|**18.28**% 


### Donate

![Build Status](https://raw.githubusercontent.com/chakkritte/NU-InNet/master/images/pic.png)

 (Bitcoin Address) : 3DermWyouJQ5MwoNvEtv2SgnvFRMTDBudv
