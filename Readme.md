HR：high resolution reference images, total 19.
LR: low resolution reference images, total 76. "x2, x3, x4, x8" refer to the down-sampling scale.
SR: super resolution images, total 720.  The name of the images follows“(SR_method)_x(upsample scale)_(HR_ref_name)x(downsample_scale)”（e.g., ATD_x2_0813x2）

train.xlsx: train dataset (576 images, 80%), "Image_name"-- SR image name; "LR_ref"-- LR reference name; "HR_ref"-- HR reference name; "P1/P2/.../P21"--individual quality score of each participant, there are total 21 participants; "MOS"--mean opinion score.
val.xlsx: val dataset (72 images, 10%)
test.xlsx: test dataset (72 images, 10%)

all xlsx include "sheet1" and "sheet2", where sheet 1 includes individual scores of each image, and sheet2 display only MOS for convience.