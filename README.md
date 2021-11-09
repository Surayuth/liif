# Create dataset
Each dataset can be created by using the line below where `source` is the directory containing images
which we want to train and validate. The optional argument `--recursive` will recursively search for 
all images in `source`. `scale` denotes the the values of factors used to downsample LR images. 
The interpolation method used to downsample images is bicubic, by default.
```
$ python make_dataset.py --src source --dst dest --scale 2 3 4 --val_r 0.1 --recursive
```
# Create config 

