DeepHash-Papers
=======

Contributed by `Yue Cao <http://yue-cao.me/>`_.

We release `DeepHash <https://github.com/thulab/deephash>`_, an open source library for deep learning to hash. This repository provides a standard deep hash training and testing framework. Currently, the implemented models in DeepHash include DHN, DQN, DVSQ, and DCH.

Any changes are welcomed.

Single-Modal Deep Hashing Methods
-------------------

[AAAI 2014] Supervised Hashing via Image Representation Learning [`paper <http://ss.sysu.edu.cn/%7Epy/papers/AAAI-CNNH.pdf>`_] [`code <http://ss.sysu.edu.cn/%7Epy/CNNH/cnnh.html>`_]
    Rongkai Xia , Yan Pan, Hanjiang Lai, Cong Liu, Shuicheng Yan.
[CVPR 2015] Simultaneous Feature Learning and Hash Coding with Deep Neural Networks [`paper <http://arxiv.org/pdf/1504.03410v1.pdf>`_]
    Hanjiang Lai, Yan Pan, Ye Liu, Shuicheng Yan.
[TIP 2015] Bit-Scalable Deep Hashing With Regularized Similarity Learning for Image Retrieval and Person Re-Identification [`paper <http://arxiv.org/pdf/1508.04535v2.pdf>`_] [`code <https://github.com/ruixuejianfei/BitScalableDeepHash>`_]
    Ruimao Zhang, Liang Lin, Rui Zhang, Wangmeng Zuo, Lei Zhang.
[IJCAI 2015] Convolutional Neural Networks for Text Hashing [`paper <http://ijcai.org/papers15/Papers/IJCAI15-197.pdf>`_]
    Jiaming Xu, PengWang, Guanhua Tian, Bo Xu, Jun Zhao, Fangyuan Wang, Hongwei Hao.
[CVPR 2015] Deep Semantic Ranking Based Hashing for Multi-Label Image Retrieval [`paper <http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Zhao_Deep_Semantic_Ranking_2015_CVPR_paper.pdf>`_] [`code <https://github.com/zhaofang0627/cuda-convnet-for-hashing>`_]
    Fang Zhao, Yongzhen Huang, Liang Wang, Tieniu Tan.
[AAAI 2015] Deep Hashing for Compact Binary Codes Learning [`paper <http://ieeexplore.ieee.org/document/7298862/>`_]
    Venice Erin Liong, Jiwen Lu, Gang Wang, Pierre Moulin, Jie Zhou.
[CVPRW 2015] Deep Learning of Binary Hash Codes for Fast Image Retrieval [`paper <http://www.iis.sinica.edu.tw/%7Ekevinlin311.tw/cvprw15.pdf>`_] [`code <https://github.com/kevinlin311tw/caffe-cvprw15>`_]
    Kevin Lin, Huei-Fang Yang, Jen-Hao Hsiao, Chu-Song Chen.
[IJCAI 2016] Feature Learning based Deep Supervised Hashing with Pairwise Labels [`paper <http://cs.nju.edu.cn/lwj/paper/IJCAI16_DPSH.pdf>`_] [`code <http://cs.nju.edu.cn/lwj/code/DPSH.zip>`_]
    Wu-Jun Li, Sheng Wang, Wang-Cheng Kang.
[AAAI 2016] Deep Hashing Network for Efficient Similarity Retrieval [`paper <http://ise.thss.tsinghua.edu.cn/~mlong/doc/deep-hashing-network-aaai16.pdf>`_] [`code <https://github.com/thuml/hash-caffe>`_]
    Han Zhu, Mingsheng Long, Jiamin Wang, Yue Cao.
[AAAI 2016] Deep Quantization Network for Efficient Image Retrieval [`paper <http://yue-cao.me/doc/deep-quantization-networks-dqn-aaai16.pdf>`_] [`code <https://github.com/caoyue10/cvpr17-dvsq/tree/aaai16-dqn>`_]
    Yue Cao, Mingsheng Long, Jiamin Wang, Han Zhu, Qingfu Wen.
[CVPR 2016] Deep Supervised Hashing for Fast Image Retrieval [`paper <http://ieeexplore.ieee.org/document/7780596/>`_] [`code <https://github.com/lhmRyan/deep-supervised-hashing-DSH>`_]
    Haomiao Liu, Ruiping Wang, Shiguang Shan, Xilin Chen.
[SIGIR 2017] Deep Semantic Hashing with Generative Adversarial Networks [`paper <http://zhaofanqiu.deepfun.club/papers/SIGIR17HASH.pdf>`_]
    Zhaofan Qiu, Yingwei Pan, Ting Yao, Tao Mei.
[CVPR 2017] Deep Visual-Semantic Quantization for Efficient Image Retrieval [`paper <http://yue-cao.me/doc/deep-visual-semantic-quantization-cvpr17.pdf>`_] [`code <https://github.com/caoyue10/cvpr17-dvsq>`_]
    Yue Cao, Mingsheng Long, Jianmin Wang, Shichen Liu.
[ICCV 2017] HashNet: Deep Learning to Hash by Continuation [`paper <http://ise.thss.tsinghua.edu.cn/~mlong/doc/hashnet-iccv17.pdf>`_] [`code <https://github.com/thuml/HashNet>`_]
    Zhangjie Cao, Mingsheng Long, Jianmin Wang, Philip S. Yu.
[CVPR 2018] HashGAN: Deep Learning to Hash with Pair Conditional Wasserstein GAN [`paper <http://ise.thss.tsinghua.edu.cn/~mlong/doc/hashgan-cvpr18.pdf>`_]
    Yue Cao, Mingsheng Long, Bin Liu, Jiamin Wang.
[CVPR 2018] Deep Cauchy Hashing for Hamming Space Retrieval [`paper <http://ise.thss.tsinghua.edu.cn/~mlong/doc/deep-cauchy-hashing-cvpr18.pdf>`_] [`code <https://github.com/thulab/DeepHash>`_]
    Yue Cao, Mingsheng Long, Bin Liu, Jianmin Wang.
[CVPR 2018] Hashing as Tie-Aware Learning to Rank [`paper <http://openaccess.thecvf.com/content_cvpr_2018/html/He_Hashing_as_Tie-Aware_CVPR_2018_paper.html>`_] [`code <https://github.com/kunhe/TALR>`_]
    Kun He, Fatih Cakir, Sarah Adel Bargal, Stan Sclaroff. 
[ECCV 2018] Hashing with Binary Matrix Pursuit [`paper <https://arxiv.org/abs/1808.01990>`_] [`code <https://github.com/fcakir/hbmp>`_]
    Fatih Cakir, Kun He, Stan Sclaroff. 
[TPAMI 2019] Hashing with Mutual Information [`paper <http://arxiv.org/abs/1803.00974>`_] [`code <https://github.com/fcakir/deep-mihash/>`_]
    Fatih Cakir*, Kun He*, Sarah Adel Bargal, Stan Sclaroff (equal contrib.). 

Cross-Modal Deep Hashing Methods
-------------------
[KDD 2016] Deep Visual-Semantic Hashing for Cross-Modal Retrieval [`paper <http://www.kdd.org/kdd2016/papers/files/rpp0086-caoA.pdf>`_]
    Yue Cao, Mingsheng Long, Jianmin Wang, Qiang Yang, Philip S. Yu.
[ICMR 2016] Correlation Autoencoder Hashing for Supervised Cross-Modal Search [`paper <http://yue-cao.me/doc/correlation-autoencoder-hashing-cah-icmr16.pdf>`_]
    Yue Cao, Mingsheng Long, Jianmin Wang, Han Zhu.
[AAAI 2017] Collective Deep Quantization for Efficient Cross-Modal Retrieval [`paper <http://yue-cao.me/doc/collective-deep-quantization-aaai17.pdf>`_] [`code <https://github.com/caoyue10/aaai17-cdq>`_]
    Yue Cao, Mingsheng Long, Jianmin Wang, Shichen Liu.
[CVPR 2017] Deep Cross-Modal Hashing [`paper <https://cs.nju.edu.cn/lwj/paper/CVPR17_DCMH.pdf>`_] [`code <https://cs.nju.edu.cn/lwj/code/DCMH_tensorflow.zip>`_]
    Qing-Yuan Jiang, Wu-Jun Li.
[BMVC 2017] Correlation Hashing Network for Efficient Cross-Modal Retrieval [`paper <https://arxiv.org/abs/1602.06697>`_]
    Yue Cao, Mingsheng Long, Jianmin Wang.
