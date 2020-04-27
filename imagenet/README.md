# imagenet

## 1. Download imagenet

  `http://image-net.org/download-images`

## 2. Prepare validation set

  ```sh
  $ mkdir -p img_val_extracted/val
  $ cd img_val_extracted/val
  $ tar -xvf ../../ILSVRC2012_img_val.tar
  $ # wget -qO- https://raw.githubusercontent.com/soumith/imagenetloader.torch/master/valprep.sh | bash
  $ bash ../../valprep.sh
  ```
