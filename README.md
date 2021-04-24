# CP5102
## Anomaly Detection In Industry Control System Using Deeper Learning Approach
Industry control system cyber attack detection

## requirements
### python version
- python3.7 or higher

### python package
- wget
- tensorflow 2.3.0 (pip install tensorflow==2.3.0)
- keras
- matplotlib
- numpy
- jupyter

## dataset
[SWaT.A6_Dec 2019](https://itrust.sutd.edu.sg/itrust-labs_datasets/dataset_info/)

## procedure
First save .pcap file as .txt file

If do the protocol filter or modify the size the training set(the number of packets), please use the fliter in wireshark application.

using pcap_txt_to_image.py generate image with label, i.e. deep learning training set format .npy

use p8.py generate image into .npy file


reference [Tensorflow note Peking University MOOC](https://github.com/cj0012/AI-Practice-Tensorflow-Notes)
