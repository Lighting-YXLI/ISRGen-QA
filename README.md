# ISRGen-QA
ISRGen-QA is a perceptual quality assessment dataset specifically designed for evaluating state-of-the-art super-resolution (SR) algorithms. 
HR：high resolution reference images, total 19.
LR: low resolution reference images, total 76. "x2, x3, x4, x8" refer to the down-sampling scale.
SR: super resolution images, total 720.  The name of the images follows“(SR_method)_x(upsample scale)_(HR_ref_name)x(downsample_scale)”（e.g., ATD_x2_0813x2）

# Data files
train.xlsx: train dataset (576 images, 80%), "Image_name"-- SR image name; "LR_ref"-- LR reference name; "HR_ref"-- HR reference name; "P1/P2/.../P21"--individual quality score of each participant, there are total 21 participants; "MOS"--mean opinion score.
val.xlsx: val dataset (72 images, 10%)
test.xlsx: test dataset (72 images, 10%)

Note: all xlsx include "sheet1" and "sheet2", where sheet 1 includes individual scores of each image, and sheet2 display only MOS for convience.

# Download link
通过网盘分享的文件：ISRGen-QA(1).zip
链接: https://pan.baidu.com/s/1uzWi-9RGi001d2c1jzDgBQ?pwd=2n4t 提取码: 2n4t 

# Reference

@article{li2025vquala,
  title={Vquala 2025 challenge on image super-resolution generated content quality assessment: Methods and results},
  author={Li, Yixiao and Li, Xin and Zhou, Chris Wei and Xing, Shuo and Amirpour, Hadi and Hao, Xiaoshuai and Yue, Guanghui and Zhao, Baoquan and Liu, Weide and Yang, Xiaoyuan and others},
  journal={arXiv preprint arXiv:2509.06413},
  year={2025}
}
