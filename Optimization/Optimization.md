## [Opt](#content)

1. 【ICML‘17】**Model-agnostic meta-learning for fast adaptation of deep networks**
<br>*Finn C, Abbeel P, Levine S*
<br>[paper](http://proceedings.mlr.press/v70/finn17a/finn17a.pdf)
[code](http://github.com/cbfinn/maml)

|*MAML*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |CIFAR100<br>(5w,1s) | CIFAR100<br>(5w,5s) |FC100<br>(5w,1s) | FC100<br>(5w,5s) | Omn<br>(5w,1s) | Omn<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|48.70±1.84<br>[49.81±1.78]|63.11±0.92<br>[64.21±1.33]|51.67±1.81<br>[49.00±3.26]|70.30±0.08<br>[67.56±1.80]|58.90±1.90<br>[57.06±3.83]|71.50±1.00<br>[72.24±1.71]|47.85±0.22<br>[53.31±1.77]|64.77±0.20<br>[69.88±1.47]|-|-|37.63±2.23]|[49.14±1.58]|98.70±0.40<br>[97.13±1.25]|99.90±0.10<br>[99.23±0.40]|
|ResNet12|50.96±0.50|68.35±0.47|-|-|-|-|-|-|-|-|-|-|-|-|
|ResNet10|51.98±0.84|66.62±0.83|-|-|-|-|-|-|-|-|-|-|-|-|


2. 【ICLR‘19】**HOW TO TRAIN YOUR MAML**
<br>*Antreas Antoniou, Harrison Edwards, Amos Storkey*
<br>[paper](https://openreview.net/pdf?id=HJGven05Y7)
[code](https://github.com/AntreasAntoniou/HowToTrainYourMAMLPytorch)

|*MAML++*| Mini<br>(5w,1s) | Mini<br>(5w,5s) |
|:------:|:------:|:------:|
|ConvNet4|52.15±0.26|68.32±0.44|

3. 【CVPR’19】**Task Agnostic Meta-Learning for Few-Shot Learning**
<br>*Muhammad Abdullah Jama, Guo-Jun Qi*
<br>[paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Jamal_Task_Agnostic_Meta-Learning_for_Few-Shot_Learning_CVPR_2019_paper.pdf)

|*TAML*| Mini<br>(5w,1s) | Mini<br>(5w,5s) |Omn<br>(5w,1s) | Omn<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|ConvNet-4|51.73±1.88|66.05±0.85|99.23 ± 0.35|99.71 ± 0.1|


4. 【ICLR‘19】**Meta-learning with latent embedding optimization**
<br>*Andrei A. Rusu, Dushyant Rao, Jakub Sygnowski, Oriol Vinyals*
<br>[paper](https://arxiv.org/pdf/1807.05960)
[code](https://github.com/deepmind/leo)

|*LEO*| Mini<br>(5w,1s) | Mini<br>(5w,5s) |Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|WRN28|61.76 ± 0.08|77.59 ± 0.12|66.33 ± 0.05|81.44 ± 0.09|


5. 【ICLR‘19】**Meta-Learning with Implicit Gradients**
<br>*Aravind Rajeswaran, , Jakub Sygnowski, Sham M. Kakade, Sergey Levine*
<br>[paper](https://proceedings.neurips.cc/paper_files/paper/2019/file/072b030ba126b2f4b2374f342be9ed44-Paper.pdf)
[code](https://github.com/aravindr93/imaml_dev)

|*iMAML*| Mini<br>(5w,1s) | Mini<br>(5w,5s) |Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |FC100<br>(5w,1s) | FC100<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet-4|49.30±1.88|59.77±0.73|38.54±1.37|60.24±0.76|38.4 ± 1.7|49.4 ± 0.8|

6. 【ArXir‘18】**Recasting gradient-based meta-learning as hierarchical bayes**
<br>*Erin Grant, Chelsea Finn, Sergey Levine, Trevor Darrell, Thomas Griffiths*
<br>[paper](https://arxiv.org/pdf/1801.08930)

|*LMAML*| Mini<br>(5w,1s) | Mini<br>(5w,5s) |Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|ConvNet-4|49.40±1.83|-|-|-|


7. 【ICML’18】**Gradient-based meta-learning with learned layerwise metric and subspace**
<br>*Yoonho Lee, Seungjin Choi*
<br>[paper](http://proceedings.mlr.press/v80/lee18a/lee18a.pdf)
[code](https://github.com/yoonholee/MT-net)

|*MT-net*| Mini<br>(5w,1s) | Mini<br>(5w,5s) |Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|ConvNet-4|51.70±1.84|-|-|-|

8. 【tcsvt’22】**Improving the generalization of MAML in few-shot classification via bi-level constraint**
<br>*Yuanjie Shao, Wenxiao Wu, Xinge You*(CROSS-DOMAIN)
<br>[paper](http://proceedings.mlr.press/v80/lee18a/lee18a.pdf)

|*BLC-MAML*| Mini<br>(5w,1s) | Mini<br>(5w,5s) |CUB<br>(5w,1s) | CUB<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|ResNet-12|66.26±0.32|82.92±0.30|82.21±0.42|90.99±0.23|


9. 【ICLR’19】**Learning to learn with conditional class dependencies**
<br>*Xiang Jiang, Mohammad Havaei, Farshid Varno, Gabriel Chartrand*
<br>[paper](https://openreview.net/pdf?id=BJfOXnActQ)

|*TAML*| Mini<br>(5w,1s) | Mini<br>(5w,5s) |
|:------:|:------:|:------:|
|ConvNet-4|59.23±0.99|72.35±0.71|


10. 【angappai’23】**Few-shot classification via efficient meta-learning with hybrid optimization**
<br>*Jinfang Jia, Xiang Feng, Huiqun Yu*
<br>[paper](https://www.sciencedirect.com/science/article/abs/pii/S095219762301480X)

|*Mix-MAML*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|ConvNet-4|52.84±0.49|69.43±0.46|60.23±0.48|75.58±0.42|
|ResNet-12|58.95±0.49|75.15±0.43|67.64±0.46|82.05±0.38|


11. 【ICCV’21】**Meta-Learning with Task-Adaptive Loss Function for Few-Shot Learning**
<br>*Sungyong Baik,Janghoon Choi, Heewon Kim, Dohee Cho,Jaesik Min, Kyoung Mu Lee*
<br>[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Baik_Meta-Learning_With_Task-Adaptive_Loss_Function_for_Few-Shot_Learning_ICCV_2021_paper.pdf)
[code](https://github.com/baiksung/MeTAL)

|*MeTAL*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|ConvNet-4|52.63 ± 0.37|70.52 ± 0.29|54.34 ± 0.31|70.40 ± 0.21|
|ResNet-12|59.64 ± 0.38|76.20 ± 0.19|63.89 ± 0.43|80.14 ± 0.40|
|*MAML++ + MeTAL*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|ConvNet-4|57.18 ± 0.42|72.89 ± 0.44|59.93 ± 0.36|75.39 ± 0.29-|
|ResNet-12|-|-|-|-|
|*ALFA + MeTAL*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|ConvNet-4|57.75 ± 0.38|74.10 ± 0.43|60.29 ± 0.37|75.88 ± 0.29|
|ResNet-12|66.61 ± 0.28|81.43 ± 0.25|70.29 ± 0.40|86.17 ± 0.35|

12. 【AAAI’24】**Metadiff: Meta-learning with conditional diffusion for few-shot learning**
<br>*Baoquan Zhang, Chuyao Luo, Demin Yu, Xutao Li, Huiwei Lin, Yunming Ye, Bowen Zhang*
<br>[paper](https://ojs.aaai.org/index.php/AAAI/article/view/29608/31028)
[code](https://github.com/zhangbq-research/MetaDiff)

|*MetaDiff*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|ConvNet-4|55.06 ± 0.81|73.18 ± 0.64|57.77 ± 0.90|75.46 ± 0.69|
|ResNet-12|64.99 ± 0.77|81.21 ± 0.56|72.33 ± 0.92|86.31 ± 0.62|


13. 【jvcir’22】**Meta-transfer-adjustment learning for few-shot learning**
<br>*Yadang Chen, Hui Yan, Zhi-Xin Yang, Enhua Wu*
<br>[paper](https://www.sciencedirect.com/science/article/pii/S1047320322001985)
[code](https://github.com/mpatacchiola/contextual-squeeze-and-excitation)

|*MTA*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | FC100<br>(5w,1s) | FC100<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|ConvNet-4|50.13 ± 1.2|67.21 ± 0.8|-|-|
|ResNet-12|66.9 ± 0.68|80.7 ± 0.79|45.8 ± 1.2|57.9 ± 0.9|
|ResNet-18|67.9 ± 0.89|81.8 ± 0.18|-|-|


14. 【patcog’21】**Unsupervised meta-learning for few-shot learning**
<br>*Hui Xu, Jiaxing Wang, Hao Li, Deqiang Ouyang, Jie Shao*
<br>[paper](https://drive.google.com/file/d/1Wjl-h2Ew6OxD5UYFlMPb1LwZzrRhIKU-/view)
[code](https://github.com/hanlu-nju/revisiting-UML)

|*HMS*| Mini<br>(5w,1s) | Mini<br>(5w,5s) |  Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | FC100<br>(5w,1s) | FC100<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet-4|48.12|65.33|-|-|-|-|-|-|
|ResNet-12|58.20|75.77|58.42|75.85|52.20|72.23|37.88|53.68|
|*TSP-Head*| Mini<br>(5w,1s) | Mini<br>(5w,5s) |  Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | FC100<br>(5w,1s) | FC100<br>(5w,5s) |
|ConvNet-4|47.35|65.10|-|-|-|-|-|-|
|ResNet-12|56.99|75.89|56.46|74.85|54.65|73.70|36.83|51.78|


15. 【CVPR’21】**Learning dynamic alignment via meta-filter for few-shot learning**
<br>*Chengming Xu, Yanwei Fu, Chen Liu*
<br>[paper](http://openaccess.thecvf.com/content/CVPR2021/papers/Xu_Learning_Dynamic_Alignment_via_Meta-Filter_for_Few-Shot_Learning_CVPR_2021_paper.pdf)
[code](https://github.com/chmxu/Dynamic-Meta-filter)

|*Meta-filter*| Mini<br>(5w,1s) | Mini<br>(5w,5s) |  Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|ResNet-12|67.76±0.46|82.71±0.31|71.89±0.52|85.96±0.35|


16. 【Arxiv'22】**Revisiting Unsupervised Meta-Learning via the Characteristics of Few-Shot Tasks**  
<br>*Han-Jia Ye, Lu Han, De-Chuan Zhan*  
<br>[paper](https://arxiv.org/abs/2011.14663) 
[code](https://github.com/hanlu-nju/revisiting-UML)

| *HMS*       | Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) | CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | FC100<br>(5w,1s) | FC100<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
| ConvNet-4 | 48.12 | 65.33 | - | - | - | - | - | - |
| ResNet-12 | 58.20 | 75.77 | 58.42 | 75.85 | 52.20 | 72.23 | 37.88 | 53.68 |
| *TSP-Head* | Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) | CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | FC100<br>(5w,1s) | FC100<br>(5w,5s) |
| ConvNet-4 | 47.35 | 65.10 | - | - | - | - | - | - |
| ResNet-12 | 56.99 | 75.89 | 56.46 | 74.85 | 54.65 | 73.70 | 36.83 | 51.78 |
| *Baseline (SES + SNS)* | Mini<br>(5w,1s) | Mini<br>(5w,5s) | CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | FC100<br>(5w,1s) | FC100<br>(5w,5s) |
| ConvNet-4 | 43.01 | 57.94 | - | - | 46.73 | 62.93 | 32.81 | 42.17 |
| ResNet-12 | 48.12 | 65.33 | - | - | 50.48 | 67.83 | 33.00 | 47.41 |


17. 【Arxiv'18】**Deep Meta-Learning: Learning to Learn in the Concept Space**  
*Fengwei Zhou, Bin Wu, Zhenguo Li*  
[paper](https://arxiv.org/abs/1802.03596)  
[code](https://github.com/huawei-noah/deep-meta-learning)

| *ResNet-50*   | Mini<br>(5w,1s) | Mini<br>(5w,5s) | CIFAR-100<br>(5w,1s) | CIFAR-100<br>(5w,5s) | CUB-200<br>(5w,1s) | CUB-200<br>(5w,5s) |
|:-------------:|:---------------:|:---------------:|:--------------------:|:--------------------:|:------------------:|:------------------:|
| DEML + Matching Nets | 55.84 ± 0.94    | 59.88 ± 0.73    | 58.18 ± 1.09          | 63.12 ± 0.85          | 63.47 ± 1.10        | 64.86 ± 0.87  |
| DEML + MAML*  | 53.71 ± 0.89    | 68.13 ± 0.77    | 56.65 ± 1.09          | 68.66 ± 0.85          | 64.63 ± 1.08        | 66.75 ± 0.89        |
| DEML + Meta-SGD | 58.49 ± 0.91    | 71.28 ± 0.69    | 61.62 ± 1.01          | 77.94 ± 0.74          | 66.95 ± 1.06        | 77.11 ± 0.78       |



18. 【mta'23】**Explore Pretraining for Few-Shot Learning**  
*Yan Li, Jinjie Huang*
[paper](https://doi.org/10.1007/s11042-023-15223-1)

| **EP**   | Mini<br>(5w,1s) | Mini<br>(5w,5s) | FC100<br>(5w,1s) | FC100<br>(5w,5s) |
|:-------------:|:---------------:|:---------------:|:--------------------:|:--------------------:|
| **ResNet-12** | **67.12 ± 0.43**    | **86.02 ± 0.27**    | **64.84 ± 0.43**          | **83.84 ± 0.27**          |



19. 【ICCV'23】**Generalized and Incremental Few-Shot Learning by Explicit Learning and Calibration without Forgetting**  
*Anna Kukleva, Hilde Kuehne, Bernt Schiele*  
[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Kukleva_Generalized_and_Incremental_Few-Shot_Learning_by_Explicit_Learning_and_Calibration_ICCV_2021_paper.pdf)  
[code](https://github.com/annusha/lcwof)

| **ResNet-12**   | Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:---------------:|:--------------------:|:--------------------:|:----------------------:|:----------------------:|
| LCwoF (Limited) | 58.32 ± 0.50    | 72.75 ± 0.40    | 57.13 ± 0.30          | 69.05 ± 0.30          |
| LCwoF (Unlimited)  | 61.15 ± 0.52    | 80.10 ± 0.45    | 59.79 ± 0.35          | 70.20 ± 0.35          |



20. 【WACV'22】**Calibrating CNNs for Few-Shot Meta Learning**  
*Peng Yang, Shaogang Ren, Yang Zhao, Ping Li*
[paper](https://openaccess.thecvf.com/content/WACV2022/papers/Yang_Calibrating_CNNs_for_Few-Shot_Meta_Learning_WACV_2022_paper.pdf)  
[code](https://github.com/annusha/LCwoF)

| **FBM + MAML**   | Mini<br>(5w,1s) | Mini<br>(5w,5s) | Omn<br>(5w,1s) | Omn<br>(5w,5s) | FC100<br>(5w,1s) | FC100<br>(5w,5s) |
|:---------------:|:--------------------:|:--------------------:|:----------------------:|:----------------------:|:----------------------:|:----------------------:|
| ConvNet-4 | 50.62 ± 1.79    | 64.78 ± 0.35    | 99.76 ± 0.25  | 99.93 ± 0.05 | -          | -         |
| **FBM + MTL**   | Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
| ResNet-12 | 561.41 ± 1.87   | 76.11 ± 0.92  | -          | -         |44.8 ± 1.9| 57.0 ± 1.0 |


21. 【ICCV'21】**Shallow Bayesian Meta Learning for Real-World Few-Shot Recognition**  
*Xueting Zhang, Debin Meng, Henry Gouk, Timothy Hospedales*
[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhang_Shallow_Bayesian_Meta_Learning_for_Real-World_Few-Shot_Recognition_ICCV_2021_paper.pdf)  
[code](https://github.com/Open-Debin/Bayesian_MQDA)

| **MetaQDA** | Mini<br>(5w,1s) | Mini<br>(5w,5s) | CIFAR-FS<br>(5w,1s) | CIFAR-FS<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:-----------:|:---------------:|:---------------:|:--------------------:|:--------------------:|:-----------------:|:-----------------:|
| ConvNet-4   | 56.41 ± 0.80    | 72.64 ± 0.62    | 60.52 ± 0.88         | 77.33 ± 0.73         | 58.11 ± 0.48      | 74.28 ± 0.73      |
| ResNet-18   | 65.12 ± 0.66    | 80.98 ± 0.75    | 69.97 ± 0.52         | 85.51 ± 0.58         | 63.08 ± 0.15      | 80.26 ± 0.12      |
| WRN-28         | 67.83 ± 0.64    | 84.28 ± 0.69    | 75.83 ± 0.88         | 88.79 ± 0.75         | 74.33 ± 0.65      | 89.56 ± 0.79      |


22. 【ICML'21】**Parameterless Transductive Feature Re-representation for Few-Shot Learning**  
*Wentao Cui, Yuhong Guo*  
[paper](https://proceedings.mlr.press/v139/cui21a.html)

| **SimpleShot + RR (ours)**   | Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |
|:--------------------:|:---------------:|:---------------:|:-----------------:|:-----------------:|:-------------------:|:-------------------:|
| ResNet-18 | 70.25 | 81.92 | 77.11 | 86.30 | 79.60 | 88.38 |
| WRN28-10  | 70.23 | 81.90 | 78.30 | 87.13 | 84.33 | 91.43 |
| **LaplacianShot + RR (ours)**   | Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |
| ResNet-18 | 75.04 | 82.71 | 81.43 | 86.73 | 83.55 | 89.00 |
| WRN28-10  | 77.63 | 84.07 | 82.95 | 87.94 | 84.94 | 91.71 |
| **TIM + RR (ours)**   | Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |
| ResNet-18 | 76.54 | 85.20 | 82.58 | 88.68 | 85.36 | 90.99 |
| WRN28-10  | 80.04 | 87.64 | 84.30 | 90.01 | 89.78 | 93.93 |



23. 【CVPR'21】**Learning Dynamic Alignment via Meta-filter for Few-shot Learning**  
*Chengming Xu, Yanwei Fu, Chen Liu, Chengjie Wang, Jilin Li, Feiyue Huang, Li Zhang, Xiangyang Xue*  
[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Xu_Learning_Dynamic_Alignment_via_Meta-Filter_for_Few-Shot_Learning_CVPR_2021_paper.pdf)
[code](https://github.com/chmxu/Dynamic-Meta-filter)

| **Meta-filter**   | Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:--------------------:|:---------------:|:---------------:|:-----------------:|:-----------------:|
| ResNet-12 | 67.76 ± 0.46 | 82.71 ± 0.31 | 71.89 ± 0.52 | 85.96 ± 0.35 |



24. 【tpami'21】**Learning to Learn Task-Adaptive Hyperparameters for Few-Shot Learning**  
*Sungyong Baik, Myungsub Choi, Janghoon Choi, Heewon Kim, Kyoung Mu Lee*  
[paper](https://ieeexplore.ieee.org/document/10080995/)
[code](https://github.com/baiksung/ALFA)

| **ALFA + Random Init**   | Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) | FC100<br>(5w,1s) | FC100<br>(5w,5s) | CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) |
|:------------:|:-------------------------:|:-------------------------:|:---------------------------:|:---------------------------:|:----------------:|:----------------:|:--------------------:|:--------------------:|
| ConvNet-4    |51.61 ± 0.50 | 70.00 ± 0.46 | 53.32 ± 0.50 | 71.97 ± 0.44 | 38.20 ± 0.49 | 52.98 ± 0.50 | 60.56 ± 0.49 | 75.43 ± 0.43 |
| ResNet-12   | 56.86 ± 0.50 | 72.90 ± 0.44 | 62.00 ± 0.47 | 79.81 ± 0.40 | 40.57 ± 0.49 | 53.19 ± 0.50 | 64.14 ± 0.48 | 78.11 ± 0.41 |
| **ALFA + MAML**   | Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) | FC100<br>(5w,1s) | FC100<br>(5w,5s) | CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) |
| ConvNet-4    |50.58 ± 0.51 | 69.12 ± 0.47 | 53.16 ± 0.49 | 70.54 ± 0.46 | 37.99 ± 0.48 | 53.01 ± 0.49 | 59.96 ± 0.49 | 76.79 ± 0.42 |
| ResNet-12          | 59.74 ± 0.49 | 77.96 ± 0.41 | 64.62 ± 0.49 | 82.48 ± 0.38 | 41.46 ± 0.49 | 55.82 ± 0.50 | 66.79 ± 0.47 | 83.62 ± 0.37 |
| **ALFA + MAML + L2F**   | Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) | FC100<br>(5w,1s) | FC100<br>(5w,5s) | CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) |
| ConvNet-4    |52.76 ± 0.52 | 71.44 ± 0.45 | 55.06 ± 0.50 | 73.94 ± 0.43 | 38.50 ± 0.47 | 53.20 ± 0.50 | 60.36 ± 0.50 | 76.60 ± 0.42 |
| ResNet-12    | 60.05 ± 0.49 | 77.42 ± 0.42 | 64.43 ± 0.49 | 81.77 ± 0.39 | 42.37 ± 0.50 | 55.23 ± 0.50 | 68.25 ± 0.47 | 82.98 ± 0.38 |




25. 【tpami'21】**Learning to Learn Task-Adaptive Hyperparameters for Few-Shot Learning**  
*Sungyong Baik, Myungsub Choi, Janghoon Choi, Heewon Kim, Kyoung Mu Lee*  
[paper](https://ieeexplore.ieee.org/document/10080995/)
[code](https://github.com/baiksung/ALFA)

| **ALFA + Random Init**   | Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) | FC100<br>(5w,1s) | FC100<br>(5w,5s) | CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) |
|:------------:|:-------------------------:|:-------------------------:|:---------------------------:|:---------------------------:|:----------------:|:----------------:|:--------------------:|:--------------------:|
| ConvNet-4    |51.61 ± 0.50 | 70.00 ± 0.46 | 53.32 ± 0.50 | 71.97 ± 0.44 | 38.20 ± 0.49 | 52.98 ± 0.50 | 60.56 ± 0.49 | 75.43 ± 0.43 |
| ResNet-12   | 56.86 ± 0.50 | 72.90 ± 0.44 | 62.00 ± 0.47 | 79.81 ± 0.40 | 40.57 ± 0.49 | 53.19 ± 0.50 | 64.14 ± 0.48 | 78.11 ± 0.41 |
| **ALFA + MAML**   | Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) | FC100<br>(5w,1s) | FC100<br>(5w,5s) | CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) |
| ConvNet-4    |50.58 ± 0.51 | 69.12 ± 0.47 | 53.16 ± 0.49 | 70.54 ± 0.46 | 37.99 ± 0.48 | 53.01 ± 0.49 | 59.96 ± 0.49 | 76.79 ± 0.42 |
| ResNet-12          | 59.74 ± 0.49 | 77.96 ± 0.41 | 64.62 ± 0.49 | 82.48 ± 0.38 | 41.46 ± 0.49 | 55.82 ± 0.50 | 66.79 ± 0.47 | 83.62 ± 0.37 |
| **ALFA + MAML + L2F**   | Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) | FC100<br>(5w,1s) | FC100<br>(5w,5s) | CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) |
| ConvNet-4    |52.76 ± 0.52 | 71.44 ± 0.45 | 55.06 ± 0.50 | 73.94 ± 0.43 | 38.50 ± 0.47 | 53.20 ± 0.50 | 60.36 ± 0.50 | 76.60 ± 0.42 |
| ResNet-12    | 60.05 ± 0.49 | 77.42 ± 0.42 | 64.43 ± 0.49 | 81.77 ± 0.39 | 42.37 ± 0.50 | 55.23 ± 0.50 | 68.25 ± 0.47 | 82.98 ± 0.38 |
