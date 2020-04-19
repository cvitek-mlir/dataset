# imagenet

1. Download imagenet

  `http://image-net.org/download-images`

2. prepare validation set

  ```sh
  mkdir img_val_extracted/
  cd img_val_extracted/
  tar -xvf ../ILSVRC2012_img_val.tar
  wget -qO- https://raw.githubusercontent.com/soumith/imagenetloader.torch/master/valprep.sh | bash
  ```
