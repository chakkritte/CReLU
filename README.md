# CReLU (Concatenated Rectified Linear Units)  with Caffe
CReLU (Understanding and Improving Convolutional Neural Networks via Concatenated Rectified Linear Units)

By Wenling Shang, Kihyuk Sohn, Diogo Almeida, Honglak Lee


Paper : https://arxiv.org/pdf/1603.05201v2.pdf

If you use these models in your research, please cite:

    @article{shang2016understanding,
      title={Understanding and Improving Convolutional Neural Networks via Concatenated Rectified Linear Units},
      author={Shang, Wenling and Sohn, Kihyuk and Almeida, Diogo and Lee, Honglak},
      journal={arXiv preprint arXiv:1603.05201},
      year={2016}
    }

### Results

1-crop validation error on ImageNet (center 224x224 crop from resized image with shorter side=256):

	model|top-1|top-5
	:---:|:---:|:---:
	AlexNet|42.8%|19.7%  
	SqueezeNet|42.5%|19.7%
	CReLU (all) in paper|40.93%|19.39% 
	CReLU (conv1,4,7) in paper|40.45 %|18.58% 
	**CReLU (conv1–4) in paper**|**39.82**%|**18.28**%



### Donate

![Build Status](https://raw.githubusercontent.com/chakkritte/NU-InNet/master/images/pic.png)

 (Bitcoin Address) : 3DermWyouJQ5MwoNvEtv2SgnvFRMTDBudv
