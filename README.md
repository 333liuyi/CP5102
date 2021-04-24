# CP5102
## Anomaly Detection In Industry Control System Using Deeper Learning Approach
Industry control system cyber attack detection

## Requirements
### python version
- python3.7 or higher

### python package
- wget
- tensorflow 2.3.0 (pip install tensorflow==2.3.0)
- keras
- matplotlib
- numpy
- jupyter

## Dataset
[SWaT.A6_Dec 2019](https://itrust.sutd.edu.sg/itrust-labs_datasets/dataset_info/)

## Procedure
First save .pcap file as .txt file

If do the protocol filter or modify the size the training set(the number of packets), please use the fliter in wireshark application.

using pcap_txt_to_image.py generate image with label, i.e. deep learning training set format .npy

reference [Tensorflow note Peking University MOOC](https://github.com/cj0012/AI-Practice-Tensorflow-Notes)

use p8.py generate image into .npy file

use p16.py for resume training at a breakpoint

use p19.py for parameter detail

use p23.py for acc and loss curve

use p28.py for app and visualization

use p27.py for CNN baseline

use <https://blog.csdn.net/weixin_43509263/article/details/101638713> & <https://www.yht7.com/news/94223> & <https://www.yisu.com/zixun/146799.html> & [keras manual/docs](https://keras.io/zh/metrics/) for other metrics

## Demo
please run jupyter for example/template
