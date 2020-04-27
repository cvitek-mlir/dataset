# imagenet

## 1. Download coco

  `http://cocodataset.org/#download`

  Download

  - 2017 Val images [5K/1GB], `http://images.cocodataset.org/zips/val2017.zip`
  - 2017 Train/Val annotations [241MB], `http://images.cocodataset.org/annotations/annotations_trainval2017.zip`

## 2. Unzip

  ```sh
  $ unzip val2017.zip
  $ unzip annotations_trainval2017.zip
  ```

## 3. Install cocoAPI

  Can skip this step if using cvitek docker.

  ```sh
  # Following doesn't work if numpy version >= 1.1.8
  $ pip3 install pycocotools

  # build from source
  $ git clone https://github.com/cocodataset/cocoapi.git
  $ cd cocoapi/PythonAPI
  $ make -j8
  $ python setup.py install
  ```
