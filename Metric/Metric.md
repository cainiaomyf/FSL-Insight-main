## [Met](#content)

1. 【ICML‘15】**Siamese neural networks for one-shot image recognition**
<br>*Koch G, Zemel R, Salakhutdinov R*
<br>[paper](https://www.cs.utoronto.ca/~rsalakhu/papers/oneshot1.pdf)
[code]()

|*Siamese Nets*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) | CIFAR100<br>(5w,1s) | CIFAR100<br>(5w,5s) |FC100<br>(5w,1s) | FC100<br>(5w,5s) | Omn<br>(5w,1s) | Omn<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|ResNet10|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|ResNet12|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|ResNet18|-|-|-|-|-|-|-|-|-|-|-|-|-|-|

2. 【NIPS‘16】**Matching networks for one shot learning**
<br>*Vinyals O, Blundell C, Lillicrap T, Wierstra D*
<br>[paper](https://proceedings.neurips.cc/paper_files/paper/2017/file/cb8da6767461f2812ae4290eac7cbc42-Paper.pdf)
[code]()

|*Matching Nets*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |CIFAR100<br>(5w,1s) | CIFAR100<br>(5w,5s) |FC100<br>(5w,1s) | FC100<br>(5w,5s) | Omn<br>(5w,1s) | Omn<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|43.56±0.84<br>[48.10±0.81]|55.31±0.73<br>[61.24±0.73]|-|-|-|-|51.45±0.22|75.46±0.18|-|-|-|-|-|-|
|ResNet10|54.49±0.81|68.82±0.65|-|-|-|-|51.45±0.22|75.46±0.18|-|-|-|-|-|-|
|ResNet12|63.08±0.80|75.99±0.60|68.50±0.92|80.60±0.71|-|-|71.87±0.85|85.08±0.57|43.88±0.75|57.05±0.71|-|-|-|-|
|ResNet18|-|-|-|-|-|-|73.49±0.89|84.45±0.58|-|-|-|-|-|-|


3. 【NIPS‘17】**Prototypical networks for few-shot learning**
<br>*Snell J, Swersky K, Zemel R*
<br>[paper](https://proceedings.neurips.cc/paper_files/paper/2017/file/cb8da6767461f2812ae4290eac7cbc42-Paper.pdf)
[code](https://github.com/jakesnell/prototypical-networks)

|*Prototypical Nets*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |CIFAR100<br>(5w,1s) | CIFAR100<br>(5w,5s) |FC100<br>(5w,1s) | FC100<br>(5w,5s) | Omn<br>(5w,1s) | Omn<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|49.42±0.78<br>[48.85±0.42]|68.20±0.66<br>[66.87±0.25]|53.31±0.89|72.69±0.74|55.50±0.70<br>[55.49±0.21]|72.00±0.60<br>[72.10±0.13]|56.64±0.23<br>[51.31±0.48]|73.66±0.17<br>[70.14±0.19]|-|-|35.30±0.60<br>[35.90±0.24]|48.60±0.60<br>[49.26±0.25]|98.8<br>[98.27±0.13]|99.7<br>[99.37±0.05]|
|ResNet10|51.98±0.84|72.64±0.64|-|-|-|-|-|-|-|-|-|-|-|-|
|ResNet12|60.37±0.83|78.02±0.57|65.65±0.92|83.40±0.65|72.20±0.70|83.50±0.50|66.09±0.92|82.50±0.58|41.54±0.76|57.08±0.76|-|-|-|-|
|ResNet18|-|-|-|-|-|-|72.99±0.88|86.64±0.51|-|-|-|-|-|-|

4. 【ICLR‘18】**Few-shot learning with graph neural networks**
<br>*Victor Garcia, Joan Bruna*
<br>[paper](https://arxiv.org/pdf/1711.04043)
[code](https://github.com/vgsatorras/few-shot-gnn)

|*GNN-FSL*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |CIFAR100<br>(5w,1s) | CIFAR100<br>(5w,5s) |FC100<br>(5w,1s) | FC100<br>(5w,5s) | Omn<br>(5w,1s) | Omn<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|50.33±0.36|66.41±0.63|54.97|70.92|-|-|-|-|-|-|-|-|-|-|
|ResNet10|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|ResNet12|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|ResNet18|-|-|-|-|-|-|-|-|-|-|-|-|-|-|


5. 【CVPR‘18】**Learning to compare: Relation network for few-shot learning**
<br>*Sung F, Yang Y, Zhang L, Xiang T, Torr P H, Hospedales T M*
<br>[paper](https://proceedings.neurips.cc/paper/2016/file/90e1357833654983612fb05e3ec9148c-Paper.pdf)
[code]()

|*Relation Nets*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |CIFAR100<br>(5w,1s) | CIFAR100<br>(5w,5s) |FC100<br>(5w,1s) | FC100<br>(5w,5s) | Omn<br>(5w,1s) | Omn<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|49.31±0.85<br>[50.18±0.46]|66.60±0.69<br>[65.34±0.41]|54.48±0.93|71.32±0.78|55.00±1.00<br>[55.84±0.37]|69.30±0.80<br>[69.57±0.30|58.81±0.24<br>[57.40±0.36]|75.23±0.18<br>[72.09±0.31]|-|-|[35.80±0.18]|[47.80±0.24]|[98.02±0.09]|[99.25±0.05]|
|ResNet10|52.19±0.83|70.20±0.66|-|-|-|-|-|-|-|-|-|-|-|-|
|ResNet12|52.19±0.83|70.20±0.66|64.42±0.36|81.74±0.61|-|-|70.47±0.99|83.70±0.55|42.41±0.21|57.23±0.62|-|-|-|-|
|ResNet18|-|-|-|-|-|-|68.58±0.94|84.05±0.56|-|-|-|-|-|-|


6. 【CVPR‘19】**Meta-Learning with Differentiable Convex Optimization**
<br>*Kwonjoon Lee, Subhransu Maji, Avinash Ravichandran, Stefano Soatto*
<br>[paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Lee_Meta-Learning_With_Differentiable_Convex_Optimization_CVPR_2019_paper.pdf)
[code](https://github.com/kjunelee/MetaOptNet)

|*MetaOptNet*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) |FC100<br>(5w,1s) | FC100<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|-|-|-|-|-|-|-|-|
|ResNet12|62.64 ± 0.61|78.63 ± 0.46|65.99 ± 0.72|81.56 ± 0.53|72.8 ± 0.7|85.0 ± 0.5|47.2 ± 0.6|62.5 ± 0.6|

7. 【CVPR‘20】**Few-Shot Learning via Embedding Adaptation with Set-to-Set Functions**
<br>*Han-Jia Ye, Hexiang Hu,De-Chuan Zhan, Fei Sha*
<br>[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Ye_Few-Shot_Learning_via_Embedding_Adaptation_With_Set-to-Set_Functions_CVPR_2020_paper.pdf)
[code](https://github.com/Sha-Lab/FEAT)

|*FEAT*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|55.15|71.61|-|-|68.87 ± 0.22|82.90 ± 0.15|
|ResNet12|66.78±0.20|82.05±0.14|70.80 ± 0.23|84.79 ± 0.16|-|-|


8. 【ICCV‘21】**Meta-baseline: Exploring simple meta-learning for few-shot learning**
<br>*Yinbo Chen, Zhuang Liu, Huijuan Xu, Trevor Darrell, Xiaolong Wang*
<br>[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Chen_Meta-Baseline_Exploring_Simple_Meta-Learning_for_Few-Shot_Learning_ICCV_2021_paper.pdf)
[code](https://github.com/yinboc/few-shot-meta-baseline)

|*Classifier-Baseline*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|-|-|-|-|
|ResNet12|58.91 ± 0.23|77.76 ± 0.17|68.07 ± 0.26|83.74 ± 0.18|
|*Meta-baseline*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|ConvNet4|-|-|-|-|
|ResNet12|63.17 ± 0.23|79.26 ± 0.17|68.62 ± 0.27| 83.74 ± 0.18|

9. 【neunet‘21】**Self-augmentation: Generalizing deep networks to unseen classes for few-shot learning**
<br>*Jin-Woo Seoa, Hong-Gyu Junga, Seong-Whan Lee*
<br>[paper](https://arxiv.org/pdf/2004.00251)
[code]()

|*ResNet12*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|*Self-Augmentation*|65.27 ± 0.45|81.84 ± 0.32|71.26 ± 0.50|85.55 ± 0.34|
|*SA + LRL*|65.37 ± 0.45|82.68 ± 0.30|71.31 ± 0.50|86.41 ± 0.33|


10. 【ICCV‘21】**Binocular Mutual Learning for Improving Few-shot Classification**
<br>*Ziqi Zhou, Xi Qiu,Jiangtao Xie,Jianan Wu, Chi Zhang1*
<br>[paper](https://arxiv.org/pdf/2004.00251)
[code](https://github.com/ZZQzzq/BML)

|*ResNet12*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|*Baseline-local*|58.96±0.45|77.07±0.34|64.46±0.51|82.21±0.36|67.60±0.49|84.78±0.34|66.79±0.49|86.55±0.28|
|*Baseline-global*|61.71±0.48|81.21±0.32|63.27±0.52|82.22±0.36|69.74±0.49|87.37±0.34|60.13±0.49|79.77±0.36|
|*BML*|67.04±0.63|83.63±0.29|68.99±0.50|85.49±0.34|73.45±0.47|88.04±0.33|76.21±0.63|90.45±0.36|

11. 【ICME‘21】**Multi-pretext attention network for few-shot learning with self-supervisio**
<br>*Hainan Li, Renshuai Tao, Jun Li, Haotong Qin, Yifu Ding, Shuo Wang, Xianglong Liu*
<br>[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Gao_Curvature_Generation_in_Curved_Spaces_for_Few-Shot_Learning_ICCV_2021_paper.pdf)
[code](https://ieeexplore.ieee.org/document/9428447)

|*MAN*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|51.30±0.45|68.21±0.37|-|-|
|ResNet12|61.70±0.47|78.42±0.34|65.99±0.51|81.97±0.37|
|WRN28|64.51±0.47|80.93±0.33|70.35±0.51|84.09±0.36|


12. 【ICCV‘21】**Curvature Generation in Curved Spaces for Few-Shot Learning**
<br>*Zhi Gao, Yuwei Wu, Yunde Jia, Mehrtash Harandi*
<br>[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Gao_Curvature_Generation_in_Curved_Spaces_for_Few-Shot_Learning_ICCV_2021_paper.pdf)
[code](https://github.com/ZhiGaomcislab/CurvatureGeneration_FSL)

|*In.CCG+HAN*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) |CUB<br>(5w,1s) | CUB<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|55.53±0.20|72.12±0.16|-|-|-|-|-|-|
|ResNet12|63.56±0.20|79.13±0.14|-|-|-|-|-|-|
|BigResNet-12|67.02±0.20|82.32±0.14|71.66±0.23|85.50±0.15|73.0±0.7|85.8±0.5|74.66±0.21|88.37±0.12|
|*Tran.CCG+HAN*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) |CUB<br>(5w,1s) | CUB<br>(5w,5s) |
|ConvNet4|55.53±0.20|72.12±0.16|-|-|-|-|-|-|
|ResNet12|66.73±0.22|80.57±0.14|-|-|-|-|-|-|
|BigResNet-12|71.79±0.23|83.00±0.17|77.19±0.24|86.18±0.15|76.8±0.7|86.4±0.5|76.69±0.21|89.30±0.12|


13. 【NIPS‘21】**Rectifying the shortcut learning of background for few-shot learning**
<br>*Sung F, Yang Y, Zhang L, Xiang T*
<br>[paper](https://proceedings.neurips.cc/paper/2021/file/6cfe0e6127fa25df2a0ef2ae1067d915-Paper.pdf)
[code](https://github.com/Frankluox/FewShotCodeBase)

|*COSOC*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|-|-|-|-|
|ResNet12|69.28 ± 0.49|81.24 ± 0.26|73.57 ± 0.43|87.57 ± 0.10|


14. 【ins‘22】**Multi-instance attention network for few-shot learning**
<br>*YXu Luo, Longhui Wei, Liangjian Wen, Jinrong Yang, Lingxi Xie, Zenglin Xu, Qi Tian*
<br>[paper](https://proceedings.neurips.cc/paper/2021/file/6cfe0e6127fa25df2a0ef2ae1067d915-Paper.pdf)
[code](https://github.com/rumorgin/MIAN)

|*MIAN*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|-|-|-|-|
|ResNet12|64.27 ± 0.35|85.16 ± 0.42|69.89 ± 0.36|86.05 ± 0.26|


15. 【tpami‘22】**Few-Shot Learning with a Strong Teacher**
<br>*Sung F, Yang Y, Zhang L, Xiang T*
<br>[paper](https://proceedings.neurips.cc/paper/2021/file/6cfe0e6127fa25df2a0ef2ae1067d915-Paper.pdf)
[code](https://github.com/Han-Jia/LastShot)

|*ResNet12*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CUB<br>(5w,1s) | CUB<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|*ProtoNet+LASTSHOT (NC)*|64.16 ± 0.20|81.23 ± 0.14|68.91 ± 0.23|85.15 ± 0.16|75.83 ± 0.21|89.83 ± 0.12|
|*ProtoNet+LASTSHOT (LR)*|64.80 ± 0.20|81.65 ± 0.14|69.37 ± 0.23|85.36 ± 0.16|75.80 ± 0.21|90.22 ± 0.12|
|*ProtoMAML+LASTSHOT (NC)*|63.07 ± 0.20|81.04 ± 0.14|68.42 ± 0.23|83.63 ± 0.16|74.57 ± 0.21|88.67 ± 0.12|
|*ProtoMAML+LASTSHOT (LR)*|63.05 ± 0.20|81.11 ± 0.14|68.80 ± 0.23|83.72 ± 0.16|74.18 ± 0.21|88.23 ± 0.12|
|*MetaOptNet+LASTSHOT (NC)*|65.07 ± 0.20|80.34 ± 0.14|68.23 ± 0.23|83.22 ± 0.16|78.54 ± 0.21|90.46 ± 0.12|
|*MetaOptNet+LASTSHOT (LR)*|65.08 ± 0.20|80.40 ± 0.14|68.29 ± 0.23|83.45 ± 0.16|78.79 ± 0.21|90.46 ± 0.12|
|*FEAT+LASTSHOT (NC)*|67.33 ± 0.20|82.39 ± 0.14|72.03 ± 0.23|85.66 ± 0.1|80.07 ± 0.21|91.43 ± 0.12|
|*FEAT+LASTSHOT (LR)*|67.35 ± 0.20|82.58 ± 0.14|72.43 ± 0.23|85.82 ± 0.16|80.20 ± 0.21|91.49 ± 0.12|


16. 【AAAI‘22】**Adaptive Poincare Point to Set Distance for Few-Shot Classification**
<br>*Rongkai Ma, Pengfei Fang, Tom Drummond, Mehrtash Harandi*
<br>[paper](https://ojs.aaai.org/index.php/AAAI/article/view/20087/19846)

|*APP2S*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) |CUB<br>(5w,1s) | CUB<br>(5w,5s) |CIFAR100<br>(5w,1s) | CIFAR100<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ResNet-12|66.25±0.20|83.42±0.15|72.00±0.22|86.23±0.15|73.12±0.22|85.69±0.16|-|-|47.64±0.21|63.56±0.22|
|ResNet-18|64.82±0.12|81.31±0.22|70.83±0.15|84.15±0.29|-|-|77.64±0.19|90.43±0.18|-|-|


17. 【ArXir‘21】**Multi-level metric learning for few-shot image recognition**
<br>*Haoxing Chen, Huaxiong Li, Yaohui Li, Chunlin Chen*
<br>[paper](https://arxiv.org/pdf/2103.11383)
[code](https://github.com/chenhaoxing/M2L)

|*PEAG*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s)|FC100<br>(5w,1s) | FC100<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ResNet-12|67.29±0.23|78.49±0.21|68.89±0.25|82.08±0.21|74.27±0.23|83.89±0.20|43.99±0.21|56.47±0.24|
|*MML*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s)|FC100<br>(5w,1s) | FC100<br>(5w,5s) |
|ResNet-12|67.58±0.23|81.41±0.20|71.38±0.25|84.65±0.20|75.28±0.23|85.95±0.19|44.43±0.21|59.56±0.25|


18. 【CVPR‘20】**Adaptive Subspaces for Few-Shot Learning**
<br>*Christian Simon, Piotr Koniusz, Richard Nock, Mehrtash Harandi*
<br>[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Simon_Adaptive_Subspaces_for_Few-Shot_Learning_CVPR_2020_paper.pdf)
[code](https://github.com/chrysts/dsn_fewshot)

|*DSN*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s)|CUB<br>(5w,1s) | CUB<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|51.78±0.96|68.99±0.69|51.52 ± 0.21|71.31 ± 0.18|-|-|54.49 ± 0.23|74.10 ± 0.17|
|ResNet12|62.64±0.66|78.83±0.45|66.22±0.75|82.79±0.48|72.3±0.8|85.1±0.6|-|-|
|*DSN-MR*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s)|FC100<br>(5w,1s) | FC100<br>(5w,5s) |
|ConvNet4|55.88±0.90|70.50±0.68|-|-|-|-|-|-|
|ResNet12|64.60±0.72|79.51±0.50|67.39±0.82|82.85±0.56|75.6±0.9|86.2±0.6|-|-|


18. 【ECCV‘22】**Unsupervised Few-Shot Image Classification by Learning Features into Clustering Space**
<br>*Shuo Li, Fang Liu, Zehua Hao, Kaibo Zhao, Licheng Jiao*
<br>[paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136910406.pdf)
[code](https://github.com/LiShuo1001/LF2CS)

|*LF2CS*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s)|
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|48.32±0.64|61.52±0.52|49.15±0.65|62.54±0.58|51.52±0.72|66.82±0.57|
|ResNet12|53.14±0.62|67.36±0.50|53.16±0.66|66.59±0.57|55.04±0.72|70.62±0.57|


19. 【ECCV‘22】**Rethinking few-shot image classification: a good embedding is all you need**
<br>*Yonglong Tian, Yue Wang1, Dilip Krishnan, Joshua B. Tenenbaum, Phillip Isola*
<br>[paper](https://arxiv.org/pdf/2003.11539)
[code](http://github.com/WangYueFt/rfs)

|*RFS*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s)|FC100<br>(5w,1s) | FC100<br>(5w,5s)|
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|55.25 ± 0.58|71.56 ± 0.52|56.18 ± 0.70|72.99 ± 0.55|62.7 ± 0.8|78.7 ± 0.5|39.6 ± 0.6|53.5 ± 0.5|
|ResNet12|62.02 ± 0.63|79.64 ± 0.44|69.74 ± 0.72|84.41 ± 0.55|71.5 ± 0.8|86.0 ± 0.5|42.6 ± 0.7|59.1 ± 0.6|
|SEResNet-12|62.29 ± 0.60|79.94 ± 0.46|70.31 ± 0.70|85.22 ± 0.50|72.0 ± 0.8|86.0 ± 0.6|43.4 ± 0.6|59.1 ± 0.6|
|*RFS-distill*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s)|FC100<br>(5w,1s) | FC100<br>(5w,5s)|
|ConvNet4|55.88 ± 0.59|71.65 ± 0.51|56.76 ± 0.68|73.21 ± 0.54|63.8 ± 0.8|79.5 ± 0.5|40.3 ± 0.6|54.1 ± 0.5|
|ResNet12|64.82 ± 0.60|82.14 ± 0.43|71.52 ± 0.69|86.03 ± 0.49|73.9 ± 0.8|86.9 ± 0.5|44.6 ± 0.7|60.9 ± 0.6|
|SEResNet-12|65.96 ± 0.63|82.05 ± 0.46|71.72 ± 0.69|86.54 ± 0.49|74.2 ± 0.8|87.2 ± 0.5|44.9 ± 0.6|61.4 ± 0.6|
|*RFS-simple*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s)|FC100<br>(5w,1s) | FC100<br>(5w,5s)|
|ConvNet4|56.32 ± 0.58|72.46 ± 0.52|56.53 ± 0.68|73.15 ± 0.58|63.5 ± 0.8|79.8 ± 0.5|43.2 ± 0.6|58.5 ± 0.5|
|ResNet12|63.59 ± 0.61|80.86 ± 0.47|71.12 ± 0.68|85.94 ± 0.46|73.1 ± 0.8|86.7 ± 0.5|49.5 ± 0.7|66.4 ± 0.6|
|SEResNet-12|64.07 ± 0.61|80.92 ± 0.43|71.76 ± 0.66|86.27 ± 0.45|73.3 ± 0.8|86.8 ± 0.5|49.9 ± 0.7|66.8 ± 0.6|
|*RFS-distill-trainval*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s)|FC100<br>(5w,1s) | FC100<br>(5w,5s)|
|ConvNet4|56.64 ± 0.58|72.85 ± 0.50|57.35 ± 0.70|73.98 ± 0.56|64.9 ± 0.8|80.3 ± 0.5|44.6 ± 0.6|59.2 ± 0.5|
|ResNet12|66.58 ± 0.65|83.22 ± 0.39|72.98 ± 0.71|87.46 ± 0.44|75.4 ± 0.8|88.2 ± 0.5|51.6 ± 0.7|68.4 ± 0.6|
|SEResNet-12|67.73 ± 0.63|83.35 ± 0.41|72.55 ± 0.69|86.72 ± 0.49|75.6 ± 0.8|88.2 ± 0.5|52.0 ± 0.7|68.8 ± 0.6|



20. 【ECCV‘22】**Mixture-based feature space learning for few-shot image classification**
<br>*Shuo Li, Fang Liu, Zehua Hao, Kaibo Zhao, Licheng Jiao*
<br>[paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136910406.pdf)
[code](https://github.com/ArmanAfrasiyabi/MixtFSL-fs)

|*MixtFSL*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |FC100<br>(5w,1s) | FC100<br>(5w,5s)|CUB<br>(5w,1s) | CUB<br>(5w,5s)|
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|52.82±0.63|70.67±0.57|-|-|-|-|-|-|
|Resnet12|63.98±0.79|82.04±0.49|70.97±1.03|86.16±0.67|44.89±0.63|60.70±0.67|-|-|
|Resnet18|60.11±0.73|77.76±0.58|68.61±0.91|84.08±0.55|41.50±0.67|58.39±0.62|73.94±1.1|86.01±0.5|
|WRN28|64.31±0.79|81.66±0.60|-|-|-|-|-|-|



21. 【ICLR‘19】**Learning to propagate labels: Transductive propagation network for few-shot learning**
<br>*Shuo Li, Fang Liu, Zehua Hao, Kaibo Zhao, Licheng Jiao*
<br>[paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136910406.pdf)
[code](https://github.com/csyanbin/TPN-pytorch)

|*TPN*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|53.75|69.43|57.53±0.96|72.85±0.74|


22. 【CVPR‘19】**Edge-Labeling Graph Neural Network for Few-shot Learning**
<br>*Jongmin Kim, Taesup Kim, Sungwoong Kim, Chang D.Yoo*
<br>[paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Kim_Edge-Labeling_Graph_Neural_Network_for_Few-Shot_Learning_CVPR_2019_paper.pdf)
[code](https://github.com/jmkim0309/fewshot-egnn)

|*EGNN+Tran.*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|-|76.34±0.48|-|80.15±0.30|
|*EGNN*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|ConvNet4|-|66.85|-|70.98|

23. 【CVPR‘20】**DPGN: distribution propagation graph network for few-shot learning**
<br>*Ling Yang, Liangliang Li, Zilun Zhang, Xinyu Zhou, Erjin Zhou, Yu Liu*
<br>[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_DPGN_Distribution_Propagation_Graph_Network_for_Few-Shot_Learning_CVPR_2020_paper.pdf)
[code](https://github.com/jmkim0309/fewshot-egnn)

|*DPGN*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|66.01±0.36|82.83±0.41|69.43±0.49|85.92±0.42|76.40±0.50|88.40±0.40|76.05±0.51|89.08±0.38|
|Resnet12|67.77±0.32|84.60±0.43|72.45±0.51|87.24±0.39|77.90±0.50|90.20±0.40|75.51±0.47|91.48±0.33|
|Resnet18|66.63±0.51|84.07±0.42|70.46±0.52|86.44±0.41|-|-|-|-|
|WRN28|67.24±0.51|83.72±0.44|-|-|-|-|-|-|

24. 【CVPR‘21】**ECKPN: Explicit Class Knowledge Propagation Network for Transductive Few-shot Learning**
<br>*Chaofan Chen, Xiaoshan Yang, Changsheng Xu, Xuhui Huang, Zhe Ma*
<br>[paper](https://arxiv.org/pdf/2106.08523v1)

|*ECKPN*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|68.89±0.34|83.59±0.44|70.45±0.48|86.74±0.42|77.5±0.4|89.1 ±0.5|77.20±0.36|89.72±0.31|
|Resnet12|70.48±0.38|85.42±0.46|73.59±0.45|88.13±0.28|79.2±0.4|91.0 ±0.5|77.43±0.54|92.21±0.41|

25. 【CVPR‘20】**Adaptive Cross-Modal Few-shot Learning**
<br>*Chen Xing, Negar Rostamzadeh, Boris N. Oreshkin, Pedro O. Pinheiro*
<br>[paper](https://arxiv.org/pdf/1902.07104v3)
[code](https://github.com/ServiceNow/am3)

|*AM3-ProtoNets++*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|ResNet12|65.21±0.30|75.20±0.27|58.47±0.64|78.41±0.41|
|*AM3-TADAM*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|ResNet12|65.30±0.49|78.10±0.36|69.08±0.47|82.58±0.31|
|*AM3-TRAML*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|ResNet12|67.10±0.52|79.54±0.60|-|-|


26. 【ECCV‘20】**Associative Alignment for Few-shot Image Classification**
<br>*Arman Afrasiyabi, Jean-Francois Lalonde, Christian Gagne*
<br>[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123500018.pdf)
[code](https://github.com/ArmanAfrasiyabi/associative-alignment-fs)

|*adversarial alignment*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |FC100<br>(5w,1s) | FC100<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|52.13±0.99|70.78±0.60|-|-|-|-|63.30±0.94|81.35±0.67|
|Resnet18|58.84±0.77|77.92±0.82|66.44±0.61|85.12±0.53|43.44±0.71|58.69±0.56|70.80±1.12|88.04±0.54|
|WRN28|64.79±0.93|82.02±0.88|73.87±0.76|84.95±0.59|-|-|-|-|
|*centroid alignment*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |FC100<br>(5w,1s) | FC100<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |
|ConvNet4|53.14±1.06|71.45±0.72|-|-|-|-|62.71±0.88|80.48±0.81|
|Resnet18|59.88±0.67|80.35±0.73|69.29±0.56|85.97±0.49|45.83±0.48|59.74±0.56|74.22±1.09|88.65±0.55|
|WRN28|65.92±0.60|82.85±0.55|74.40± 0.68|86.61±0.59|-|-|-|-|

27. 【CVPR‘21】**Prototype completion with primitive knowledge for few-shot learning**
<br>*Baoquan Zhang, Xutao Li, Yunming Ye, Zhichao Huang, Lisai Zhang*
<br>[paper](https://arxiv.org/pdf/2009.04960v6.pdf)
[code](https://github.com/zhangbq-research/Prototype_Completion_for_FSL)

|*prototype completion*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|Resnet12|73.13±0.85|82.06±0.54|81.04±0.89|87.42±0.57|93.20±0.45|94.90±0.31|


28. 【CVPR‘21】**SEGA: Semantic Guided Attention on Visual Prototype for Few-Shot Learning**
<br>*Fengyuan Yang, Ruiping Wang, Xilin Chen*
<br>[paper](https://arxiv.org/pdf/2111.04316v1.pdf)
[code](https://github.com/martayang/sega)

|*SEGA*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|Resnet12|69.04±0.26|79.03±0.18|72.18±0.30|84.28±0.21|78.45±0.24|86.00±0.20|84.57±0.22|90.85±0.16|



29. 【CVPR‘20】**Few-Shot Learning With Multi-Granularity Knowledge Fusion and Decision-Making**
<br>*Yuling Su, Hong Zhao, Yifeng Zheng, Yu Wang*
<br>[paper](https://ieeexplore.ieee.org/abstract/document/10382622/)
[code](https://github.com/fhqxa/MGKFD)

|*MGKFD*| Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) |FC100<br>(5w,1s) | FC100<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|72.78±0.31|85.86±0.22|44.86±0.26|61.10±0.25|72.96±0.30|86.21±0.21|



26. 【CVPR‘22】**Generating Representative Samples for Few-Shot Classification**
<br>*Jingyi Xu, Hieu Le*
<br>[paper](https://arxiv.org/pdf/2205.02918v1.pdf)
[code](https://github.com/cvlab-stonybrook/fsl-rsvae)

|*Resnet12*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|Meta-Baseline + SVAE|69.96±0.21|79.92±0.16|73.05±0.24|83.96±0.18|
|Meta-Baseline + R-SVAE|72.79±0.19|80.70±0.16|73.90±0.24|84.17±0.18|
|ProtoNet + SVAE|73.01±0.24|83.13±0.40|76.36±0.65|85.65±0.50|
|ProtoNet + R-SVAE|74.84±0.23|83.28±0.40|76.98±0.65|85.77±0.50|
|E3BM + SVAE|73.07±0.39|80.82±0.31|79.85±0.43|86.82±0.32|
|E3BM + R-SVAE|73.35±0.37|80.95±0.31|80.46±0.43|86.99±0.32|

26. 【CVPR‘23】**Semantic Prompt for Few-Shot Image Recognition**
<br>*Wentao Chen, Chenyang Si, Zhang Zhang, Liang Wang, Zilei Wang, Tieniu Tan*
<br>[paper](https://arxiv.org/pdf/2303.14123v1.pdf)
[code](https://github.com/WentaoChen0813/SemanticPrompt)

|*Visformer-T*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | FC100<br>(5w,1s) | FC100<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|Pre-train|65.16±0.44|81.22±0.32|72.38±0.50|86.74±0.34|71.99±0.47|85.98±0.34|43.77±0.39|59.48±0.39|
|SP-CLIP|72.31±0.40|83.42±0.30|78.03±0.46|88.55±0.32|82.18±0.40|88.24±0.32|48.53±0.38|61.55±0.41|
|SP-SBERT|70.70±0.42|83.55±0.30|73.31±0.50|88.56±0.32|81.32±0.40|88.31±0.32|47.03±0.40|61.03±0.40|
|SP-GloVe|70.81±0.42|83.31±0.30|74.68±0.50|88.64±0.31|81.62±0.41|88.32±0.32|46.69±0.41|61.18±0.41|


26. 【CVPR‘24】**Simple Semantic-Aided Few-Shot Learning**
<br>*Hai Zhang1, Junzhe Xu, Shanlin Jiang, Zhenan He*
<br>[paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_Simple_Semantic-Aided_Few-Shot_Learning_CVPR_2024_paper.pdf)
[code](https://github.com/zhangdoudou123/SemFew)

|*SemFew*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ResNet-12|77.63±0.63|83.04±0.48|78.96±0.80|85.88±0.62|83.65±0.70|87.66±0.60|54.36±0.71|62.79±0.74|
|*SemFew-Trans*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|Swin-T|78.94±0.66|86.49±0.50|82.37±0.77|89.89±0.52|84.34±0.67|89.11±0.54|54.27±0.77|65.02±0.72|
