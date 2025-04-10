<!-- # FineAction -->
The official codebase of FineAction dataset. We will update the data and code of our FineAction.

[[Arxiv version]](https://arxiv.org/abs/2105.11107)      [[TIP version]](https://ieeexplore.ieee.org/document/9934010?source=authoralert)

<!-- **ToDo**

- [ ] Update the VideoMAE feature on FineAction.
- [ ] Update the code of reproduce codabases(BMN, ActionFormer) on FineAction. -->


## 📰 News

* **[2025-04-10]**: Update the download links of our FineAction.
* **[2022-10-10]**: Our FineAction has been accepted by ***IEEE Transactions on Image Processing***.

* **[2022-04-30]**: We have published competitions for FineAction on [DeeperAction Workshop@ECCV2022 Track 1](https://codalab.lisn.upsaclay.fr/competitions/4386).

* **[2021-05-31]**: We have published competitions for FineAction on [DeeperAction Workshop@ICCV2021 Track 1](https://competitions.codalab.org/competitions/32363?secret_key=b1c97675-29b9-4231-b3e4-faed47501214).




## ⚡️Update Data Download
You can download the dataset from OpenDataLab https://openxlab.org.cn/datasets/OpenDataLab/FineAction

* **Raw videos**: https://openxlab.org.cn/datasets/OpenDataLab/FineAction/tree/main/raw/video

* **Annotations**:  https://openxlab.org.cn/datasets/OpenDataLab/FineAction/tree/main/raw/annotations_gt.json

* **I3d feature**:  https://openxlab.org.cn/datasets/OpenDataLab/FineAction/tree/main/raw/i3d_feature

* **I3d_100 feature**:  https://openxlab.org.cn/datasets/OpenDataLab/FineAction/tree/main/raw/i3d_feature_100

* **VideoMAE_h feature**: https://openxlab.org.cn/datasets/OpenDataLab/FineAction/tree/main/raw/mae_h_feature  
* **VideoMAE_g feature**: https://openxlab.org.cn/datasets/OpenDataLab/FineAction/tree/main/raw/mae_g_feature
* More details about videomae referring to https://github.com/OpenGVLab/VideoMAEv2/blob/master/docs/TAD.md



## 🚀 Research
We will update the SOTA methods on our FineAction.

### ✨ Temporal Action Localization
| Year | Venue |   Model<br/>(or Authors)   |  @0.5   |  @0.75  |  @0.95  |   AVG   |  code  |
|:----:|:-----:|:--------------------------:|:-------:|:-------:|:-------:|:-------:|:------:|
| 2019 | ICCV  | [BMN]() (Reprod.)  |  14.44   |  8.92   |  3.12   |  9.25   |[code](https://github.com/JJBOY/BMN-Boundary-Matching-Network)|
| 2020 | AAAI  | [DBG](https://arxiv.org/abs/1911.04127) (Reprod.)|  10.65   | 6.43  |  2.50   |  6.75   |[code](https://github.com/Tencent/ActionDetection-DBG)|
| 2020 | CVPR  | [G-TAD](https://arxiv.org/abs/1911.11462) (Reprod.)     |  13.74   |  8.83   |  3.06   |  9.06   |[code](https://github.com/frostinassiky/gtad)|
<!-- | 2022 | ECCV  | [FineAction] (Reprod.)  |  6.75   |  3.02   |  0.82   |  3.35   |[code](https://github.com/naraysa/D2-Net)| -->



### ✨ Weakly Supervised Temporal Action Localization
| Year | Venue |   Model<br/>(or Authors)   |  @0.5   |  @0.75  |  @0.95  |   AVG   |  code  |
|:----:|:-----:|:--------------------------:|:-------:|:-------:|:-------:|:-------:|:------:|
| 2018 | ECCV  | [W-TALC](https://arxiv.org/abs/1807.10418) (Reprod.)  |  6.18   |  3.15   |  0.83   |  3.45   |[code](https://github.com/sujoyp/wtalc-pytorch)|
| 2021 | AAAI  | [Lee et al.](https://arxiv.org/abs/2006.07006) (Reprod.)|  6.65   |  3.23   |  0.95   |  3.64   |[code](https://github.com/Pilhyeon/WTAL-Uncertainty-Modeling)|
| 2021 | CVPR  | [ASL](http://www.cs.toronto.edu/~mvolkovs/CVPR2021_asl.pdf) (Reprod.)     |  6.79   |  2.68   |  0.81   |  3.30   |[code](https://github.com/layer6ai-labs/ASL)|
| 2021 | ICCV  | [D2-Net](https://arxiv.org/abs/2012.06440) (Reprod.)  |  6.75   |  3.02   |  0.82   |  3.35   |[code](https://github.com/naraysa/D2-Net)|
| 2022 | ECCV  | [HAAN](https://arxiv.org/abs/2207.11805)             |**7.05** |**3.95** |**1.14** |**4.10** |[code](https://github.com/lizhi1104/HAAN)|


<!-- More information about HAAN, you can see in https://github.com/lizhi1104/HAAN. -->

## ☎️ Contact 

Any question about our FineAction, you can email me. (yi.liu1@siat.ac.cn)





## ✏️ Citation

If you think this project is helpful, please feel free to leave a star⭐️ and cite our paper:
```
@article{liu2022fineaction,
  title={Fineaction: A fine-grained video dataset for temporal action localization},
  author={Liu, Yi and Wang, Limin and Wang, Yali and Ma, Xiao and Qiao, Yu},
  journal={IEEE Transactions on Image Processing},
  year={2022},
  publisher={IEEE}
}
```
