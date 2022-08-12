## Pain Level Estimation from Body Sensor Data

Automatic chronic pain assessment and pain intensity estimation has been attracting growing attention due to its widespread applications. One of the prevalent issues in automatic pain analysis is inadequate balanced expert-labelled data for pain estimation. This work proposes an anomaly detection based network addressing one of the existing limitations of automatic pain assessment. The evaluation of the network is performed on pain intensity estimation and protective behaviour estimation tasks from body movements in the EmoPain Challenge dataset. The EmoPain dataset consists of body part based sensor data for both the tasks. The proposed network, PLAAN (Pain Level Assessment with Anomaly-detection based Network), is a lightweight LSTM-DNN network which considers features based on sensor data as the input and predicts intensity level of pain and presence or absence of protective behaviour in chronic low back pain patients. Joint training considering body movement patterns, such as exercise type, corresponding to pain exhibition as a label improves the performance of the network. However, contrary to perception, protective behaviour rather exists sporadically alongside pain in the EmoPain dataset. This induces yet another complication in accurate estimation of protective behaviour. This problem is resolved by incorporating anomaly detection in the network. A detailed comparison of different networks with varied features is outlined in the paper, presenting a significant improvement with the final proposed anomaly detection based network. 

* [PLAAN: Pain Level Assessment with Anomaly-detection based Network](https://link.springer.com/article/10.1007/s12193-020-00362-8)

![pipeline_plaan](/figs/emopain.png) 
Overview of the proposed PLAAN network. Here, data processing refers to the window based temporal segment selection process. For the estimation task, either pain intensity or protective behaviour is used

* [LSTM-DNN based Approach for Pain Intensity and Protective Behaviour Prediction](https://ieeexplore.ieee.org/abstract/document/9320192)
## Dataset
The dataset is the part of Emopain challenge FG 2020. [Website](https://github.com/Mvrjustid/EmoPainChallenge2020) 

## Pipeline 
![pipeline](/figs/) 

If you find the paper/code useful for your research, please consider citing our work:
```
@article{li2021plaan,
  title={PLAAN: Pain Level Assessment with Anomaly-detection based Network},
  author={Li, Yi and Ghosh, Shreya and Joshi, Jyoti},
  journal={Journal on Multimodal User Interfaces},
  volume={15},
  number={4},
  pages={359--372},
  year={2021},
  publisher={Springer}
}
```
```
@inproceedings{li2020lstm,
  title={Lstm-dnn based approach for pain intensity and protective behaviour prediction},
  author={Li, Yi and Ghosh, Shreya and Joshi, Jyoti and Oviatt, Sharon},
  booktitle={2020 15th IEEE International Conference on Automatic Face and Gesture Recognition (FG 2020)},
  pages={819--823},
  year={2020},
  organization={IEEE}
}
```
 
## Contact
- <a href="https://sites.google.com/view/shreyaghosh/home">Shreya Ghosh</a> and <a href="https://scholar.google.com/citations?hl=en&user=omcJ_bQAAAAJ&view_op=list_works&sortby=pubdate">Dr Tarique Anwar</a>.
