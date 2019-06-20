# U-Net-MX
**This is an Gluon reimplementation of [U-Net](http://lmb.informatik.uni-freiburg.de/people/ronneber/u-net) and [DilatedUNet](https://github.com/lyakaap/Kaggle-Carvana-3rd-Place-Solution).**
See the following references for more information:
```
"U-Net: Convolutional Networks for Biomedical Image Segmentation."
Olaf Ronneberger, Philipp Fischer, and Thomas Brox
arXiv preprint arXiv:1505. 04597, 2015.
```
[https://arxiv.org/abs/1505.04597](https://arxiv.org/abs/1505.04597)


Download for example DRIVE dataset.
Right now code expects similar folder structure as below.


	├───dataset
	│   └───DRIVE
	│       ├───splits
	│       ├───test
	│       │   ├───image
	│       │   ├───label
	│       │   └───mask
	│       ├───train
	│       │   ├───image/##_training.tif.png
	│       │   ├───label/##_manual1.gif.png
	│       │   └───mask/##_mask.gif.png
	│       └───valid
	│           ├───image
	│           ├───label
	│           └───mask
