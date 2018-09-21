#从R-CNN到RFBNet,深度目标检测5年纵览，文章+代码让你从入门到精通
【导读】目标检测，是计算机视觉领域中，最基本的，也是最具挑战性的问题之一，它旨在从自然的图像中，识别预定义的类别的物体，并定位它们（给出边界框）。实际上，目标检测并不是一个很新的任务，但是随着近年来的深度学习技术的加持，目标检测领域历久旎新。几天前，Li Liu 等研究人员，向 IJCV 投稿了一篇30页的关于深度目标检测的调研文章，专知小编拜读后，在这里与各位分享。

文章名 | Deep Learning for Generic Object Detection: A Survey

文章地址 | https://arxiv.org/abs/1809.02165

作者 |  Li Liu, Wanli Ouyang, Xiaogang Wang etc.

整理报导 | huaiwen
# deep learning object detection
A paper list of object detection using deep learning. I worte with reference to [this survey paper](https://arxiv.org/pdf/1809.02165v1.pdf)  

*Last updated: 2018/9/20*

#### Update log
*2018/9/18* - update all of recent papers and make some diagram about history of object detection using deep learning. 
*2018/9/20* - update codes of papers. (official and unofficial)

## paper list from 2014 to now(2018)

<p align="center">
  <img width="1000" src="/assets/deep_learning_object_detection_history.PNG" "Example of anomaly detection.">
</p>

- [2014](#2014)
- [2015](#2015)
- [2016](#2016)
- [2017](#2017)
- [2018](#2018)

## 2014

- **[R-CNN]** Rich feature hierarchies for accurate object detection and semantic segmentation | Ross Girshick, Jeff Donahue, Trevor Darrell, Jitendra Malik | **[CVPR' 14]** |[`[pdf]`](https://arxiv.org/pdf/1311.2524.pdf) [`[official code - caffe]`](https://github.com/rbgirshick/rcnn) 

- **[OverFeat]** OverFeat: Integrated Recognition, Localization and Detection using Convolutional Networks | Pierre Sermanet, et al. | **[ICLR' 14]** |[`[pdf]`](https://arxiv.org/pdf/1312.6229.pdf) [`[official code - torch]`](https://github.com/sermanet/OverFeat) 

- **[MultiBox]** Scalable Object Detection using Deep Neural Networks | Dumitru Erhan, et al. | **[CVPR' 14]** |[`[pdf]`](https://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Erhan_Scalable_Object_Detection_2014_CVPR_paper.pdf)

- **[SPP-Net]** Spatial Pyramid Pooling in Deep Convolutional Networks for Visual Recognition | Kaiming He, et al. | **[ECCV' 14]** |[`[pdf]`](https://arxiv.org/pdf/1406.4729.pdf) [`[official code - caffe]`](https://github.com/ShaoqingRen/SPP_net) [`[unofficial code - keras]`](https://github.com/yhenon/keras-spp) [`[unofficial code - tensorflow]`](https://github.com/peace195/sppnet)

## 2015

- **[MR-CNN]** Object detection via a multi-region & semantic segmentation-aware CNN model | Spyros Gidaris, Nikos Komodakis | **[ICCV' 15]** |[`[pdf]`](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Gidaris_Object_Detection_via_ICCV_2015_paper.pdf) [`[official code - caffe]`](https://github.com/gidariss/mrcnn-object-detection)

- **[DeepBox]** DeepBox: Learning Objectness with Convolutional Networks | Weicheng Kuo, Bharath Hariharan, Jitendra Malik | **[ICCV' 15]** |[`[pdf]`](https://arxiv.org/pdf/1505.02146.pdf) [`[official code - caffe]`](https://github.com/weichengkuo/DeepBox)

- **[AttentionNet]** AttentionNet: Aggregating Weak Directions for Accurate Object Detection | Donggeun Yoo, et al. | **[ICCV' 15]** |[`[pdf]`](https://arxiv.org/pdf/1506.07704.pdf) 

- **[Fast R-CNN]** Fast R-CNN | Ross Girshick | **[ICCV' 15]** |[`[pdf]`](https://arxiv.org/pdf/1504.08083.pdf) [`[official code - caffe]`](https://github.com/rbgirshick/fast-rcnn) 

- **[DeepProposal]** DeepProposal: Hunting Objects by Cascading Deep Convolutional Layers | Amir Ghodrati, et al. | **[ICCV' 15]** |[`[pdf]`](https://arxiv.org/pdf/1510.04445.pdf)  [`[official code - matconvnet]`](https://github.com/aghodrati/deepproposal)

- **[Faster R-CNN, RPN]** Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks | Shaoqing Ren, et al. | **[NIPS' 15]** |[`[pdf]`](https://papers.nips.cc/paper/5638-faster-r-cnn-towards-real-time-object-detection-with-region-proposal-networks.pdf)  [`[official code - caffe]`](https://github.com/rbgirshick/py-faster-rcnn) [`[unofficial code - tensorflow]`](https://github.com/endernewton/tf-faster-rcnn)  [`[unofficial code - pytorch]`](https://github.com/jwyang/faster-rcnn.pytorch) 

## 2016

- **[YOLO v1]** You Only Look Once: Unified, Real-Time Object Detection | Joseph Redmon, et al. | **[CVPR' 16]** |[`[pdf]`](https://arxiv.org/pdf/1506.02640.pdf) [`[official code - c++]`](https://pjreddie.com/darknet/yolo/) 

- **[G-CNN]** G-CNN: an Iterative Grid Based Object Detector | Mahyar Najibi, et al. | **[CVPR' 16]** |[`[pdf]`](https://arxiv.org/pdf/1512.07729.pdf)

- **[AZNet]** Adaptive Object Detection Using Adjacency and Zoom Prediction | Yongxi Lu, Tara Javidi. | **[CVPR' 16]** |[`[pdf]`](https://arxiv.org/pdf/1512.07711.pdf)

- **[ION]** Inside-Outside Net: Detecting Objects in Context with Skip Pooling and Recurrent Neural Networks | Sean Bell, et al. | **[CVPR' 16]** |[`[pdf]`](https://arxiv.org/pdf/1512.04143.pdf)

- **[HyperNet]** HyperNet: Towards Accurate Region Proposal Generation and Joint Object Detection | Tao Kong, et al. | **[CVPR' 16]** |[`[pdf]`](https://arxiv.org/pdf/1604.00600.pdf)

- **[OHEM]** Training Region-based Object Detectors with Online Hard Example Mining | Abhinav Shrivastava, et al. | **[CVPR' 16]** |[`[pdf]`](https://arxiv.org/pdf/1604.03540.pdf) [`[official code - caffe]`](https://github.com/abhi2610/ohem) 

- **[CRAPF]** CRAFT Objects from Images | Bin Yang, et al. | **[CVPR' 16]** |[`[pdf]`](https://arxiv.org/pdf/1604.03239.pdf) [`[official code - caffe]`](https://github.com/byangderek/CRAFT) 

- **[MPN]** A MultiPath Network for Object Detection | Sergey Zagoruyko, et al. | **[BMVC' 16]** |[`[pdf]`](https://arxiv.org/pdf/1604.02135.pdf) [`[official code - torch]`](https://github.com/facebookresearch/multipathnet) 

- **[SSD]** SSD: Single Shot MultiBox Detector | Wei Liu, et al. | **[ECCV' 16]** |[`[pdf]`](https://arxiv.org/pdf/1512.02325.pdf) [`[official code - caffe]`](https://github.com/weiliu89/caffe/tree/ssd) [`[unofficial code - tensorflow]`](https://github.com/balancap/SSD-Tensorflow) [`[unofficial code - pytorch]`](https://github.com/amdegroot/ssd.pytorch) 

- **[GBDNet]** Crafting GBD-Net for Object Detection | Xingyu Zeng, et al. | **[ECCV' 16]** |[`[pdf]`](https://arxiv.org/pdf/1610.02579.pdf) [`[official code - caffe]`](https://github.com/craftGBD/craftGBD)

- **[CPF]** Contextual Priming and Feedback for Faster R-CNN | Abhinav Shrivastava and Abhinav Gupta | **[ECCV' 16]** |[`[pdf]`](https://pdfs.semanticscholar.org/40e7/4473cb82231559cbaeaa44989e9bbfe7ec3f.pdf)

- **[MS-CNN]** A Unified Multi-scale Deep Convolutional Neural Network for Fast Object Detection | Zhaowei Cai, et al. | **[ECCV' 16]** |[`[pdf]`](https://arxiv.org/pdf/1607.07155.pdf) [`[official code - caffe]`](https://github.com/zhaoweicai/mscnn)

- **[R-FCN]** R-FCN: Object Detection via Region-based Fully Convolutional Networks | Jifeng Dai, et al. | **[NIPS' 16]** |[`[pdf]`](https://arxiv.org/pdf/1605.06409.pdf) [`[official code - caffe]`](https://github.com/daijifeng001/R-FCN) [`[unofficial code - caffe]`](https://github.com/YuwenXiong/py-R-FCN)

- **[PVANET]** PVANET: Deep but Lightweight Neural Networks for Real-time Object Detection | Kye-Hyeon Kim, et al. | **[NIPSW' 16]** |[`[pdf]`](https://arxiv.org/pdf/1608.08021.pdf) [`[official code - caffe]`](https://github.com/sanghoon/pva-faster-rcnn)

- **[DeepID-Net]** DeepID-Net: Deformable Deep Convolutional Neural Networks for Object Detection | Wanli Ouyang, et al. | **[PAMI' 16]** |[`[pdf]`](https://arxiv.org/pdf/1412.5661.pdf)

- **[NoC]** Object Detection Networks on Convolutional Feature Maps | Shaoqing Ren, et al. | **[TPAMI' 16]** |[`[pdf]`](https://arxiv.org/pdf/1504.06066.pdf)

## 2017

- **[DSSD]** DSSD : Deconvolutional Single Shot Detector | Cheng-Yang Fu1, et al. | **[Arxiv' 17]** |[`[pdf]`](https://arxiv.org/pdf/1701.06659.pdf) [`[official code - caffe]`](https://github.com/chengyangfu/caffe/tree/dssd)

- **[TDM]** Beyond Skip Connections: Top-Down Modulation for Object Detection | Abhinav Shrivastava, et al. | **[CVPR' 17]** |[`[pdf]`](https://arxiv.org/pdf/1612.06851.pdf)

- **[FPN]** Feature Pyramid Networks for Object Detection | Tsung-Yi Lin, et al. | **[CVPR' 17]** |[`[pdf]`](http://openaccess.thecvf.com/content_cvpr_2017/papers/Lin_Feature_Pyramid_Networks_CVPR_2017_paper.pdf) [`[unofficial code - caffe]`](https://github.com/unsky/FPN)

- **[YOLO v2]** YOLO9000: Better, Faster, Stronger | Joseph Redmon, Ali Farhadi | **[CVPR' 17]** |[`[pdf]`](https://arxiv.org/pdf/1612.08242.pdf) [`[official code - c++]`](https://pjreddie.com/darknet/yolo/) [`[unofficial code - caffe]`](https://github.com/quhezheng/caffe_yolo_v2) [`[unofficial code - tensorflow]`](https://github.com/nilboy/tensorflow-yolo) [`[unofficial code - tensorflow]`](https://github.com/sualab/object-detection-yolov2) [`[unofficial code - pytorch]`](https://github.com/longcw/yolo2-pytorch) 

- **[RON]** RON: Reverse Connection with Objectness Prior Networks for Object Detection | Tao Kong, et al. | **[CVPR' 17]** |[`[pdf]`](https://arxiv.org/pdf/1707.01691.pdf) [`[official code - caffe]`](https://github.com/taokong/RON) [`[unofficial code - tensorflow]`](https://github.com/HiKapok/RON_Tensorflow)

- **[DCN]** Deformable Convolutional Networks | Jifeng Dai, et al. | **[ICCV' 17]** |[`[pdf]`](http://openaccess.thecvf.com/content_ICCV_2017/papers/Dai_Deformable_Convolutional_Networks_ICCV_2017_paper.pdf) [`[official code - mxnet]`](https://github.com/msracver/Deformable-ConvNets) [`[unofficial code - tensorflow]`](https://github.com/Zardinality/TF_Deformable_Net) [`[unofficial code - pytorch]`](https://github.com/oeway/pytorch-deform-conv)

- **[DeNet]** DeNet: Scalable Real-time Object Detection with Directed Sparse Sampling | Lachlan Tychsen-Smith, Lars Petersson | **[ICCV' 17]** |[`[pdf]`](https://arxiv.org/pdf/1703.10295.pdf) [`[official code - theano]`](https://github.com/lachlants/denet)

- **[CoupleNet]** CoupleNet: Coupling Global Structure with Local Parts for Object Detection | Yousong Zhu, et al. | **[ICCV' 17]** |[`[pdf]`](https://arxiv.org/pdf/1708.02863.pdf) [`[official code - caffe]`](https://github.com/tshizys/CoupleNet)

- **[RetinaNet]** Focal Loss for Dense Object Detection | Tsung-Yi Lin, et al. | **[ICCV' 17]** |[`[pdf]`](https://arxiv.org/pdf/1708.02002.pdf) [`[official code - keras]`](https://github.com/fizyr/keras-retinanet) [`[unofficial code - pytorch]`](https://github.com/kuangliu/pytorch-retinanet) [`[unofficial code - mxnet]`](https://github.com/unsky/RetinaNet) [`[unofficial code - tensorflow]`](https://github.com/tensorflow/tpu/tree/master/models/official/retinanet)


- **[Mask R-CNN]** Mask R-CNN | Kaiming He, et al. | **[ICCV' 17]** |[`[pdf]`](http://openaccess.thecvf.com/content_ICCV_2017/papers/He_Mask_R-CNN_ICCV_2017_paper.pdf) [`[official code - caffe2]`](https://github.com/facebookresearch/Detectron) [`[unofficial code - tensorflow]`](https://github.com/matterport/Mask_RCNN) [`[unofficial code - tensorflow]`](https://github.com/CharlesShang/FastMaskRCNN) [`[unofficial code - pytorch]`](https://github.com/multimodallearning/pytorch-mask-rcnn)

- **[DSOD]** DSOD: Learning Deeply Supervised Object Detectors from Scratch | Zhiqiang Shen, et al. | **[ICCV' 17]** |[`[pdf]`](https://arxiv.org/pdf/1708.01241.pdf) [`[official code - caffe]`](https://github.com/szq0214/DSOD) [`[unofficial code - pytorch]`](https://github.com/uoip/SSD-variants) 

- **[SMN]** Spatial Memory for Context Reasoning in Object Detection | Xinlei Chen, Abhinav Gupta | **[ICCV' 17]** |[`[pdf]`](http://openaccess.thecvf.com/content_ICCV_2017/papers/Chen_Spatial_Memory_for_ICCV_2017_paper.pdf)

## 2018

- **[YOLO v3]** YOLOv3: An Incremental Improvement | Joseph Redmon, Ali Farhadi | **[Arxiv' 18]** |[`[pdf]`](https://pjreddie.com/media/files/papers/YOLOv3.pdf) [`[official code - c++]`](https://pjreddie.com/darknet/yolo/) [`[unofficial code - pytorch]`](https://github.com/ayooshkathuria/pytorch-yolo-v3) [`[unofficial code - pytorch]`](https://github.com/eriklindernoren/PyTorch-YOLOv3) [`[unofficial code - keras]`](https://github.com/xiaochus/YOLOv3) [`[unofficial code - tensorflow]`](https://github.com/mystic123/tensorflow-yolo-v3)

- **[SIN]** Structure Inference Net: Object Detection Using Scene-Level Context and Instance-Level Relationships | Yong Liu, et al. | **[CVPR' 18]** |[`[pdf]`](http://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_Structure_Inference_Net_CVPR_2018_paper.pdf) [`[official code - tensorflow]`](https://github.com/choasup/SIN)

- **[STDN]** Scale-Transferrable Object Detection | Peng Zhou, et al. | **[CVPR' 18]** |[`[pdf]`](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhou_Scale-Transferrable_Object_Detection_CVPR_2018_paper.pdf)

- **[RefineDet]** Single-Shot Refinement Neural Network for Object Detection | Shifeng Zhang, et al. | **[CVPR' 18]** |[`[pdf]`](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_Single-Shot_Refinement_Neural_CVPR_2018_paper.pdf) [`[official code - caffe]`](https://github.com/sfzhang15/RefineDet) [`[unofficial code - chainer]`](https://github.com/fukatani/RefineDet_chainer)

- **[RFBNet]** Receptive Field Block Net for Accurate and Fast Object Detection | Songtao Liu, et al. | **[ECCV' 18]** |[`[pdf]`](https://arxiv.org/pdf/1711.07767.pdf) [`[official code - pytorch]`](https://github.com/ruinmessi/RFBNet)

## Contact & Feedback

If you have any suggenstions about papers, feel free to mail me :)

- [e-mail](mailto:lee.hoseong@sualab.com)
- [blog](https://hoya012.github.io/)
- [pull request](https://github.com/hoya012/awesome-anomaly-detection/pulls)
