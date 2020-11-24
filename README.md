# Object-Detection-Paper:zap:
读过的目标检测相关论文
## Table of Content
   * [Summary](https://github.com/aliciashen0118/Object-Detection-Paper#Summary)
   * [CNN](https://github.com/aliciashen0118/Object-Detection-Paper#CNN)
   * [Anchor_Base](https://github.com/aliciashen0118/Object-Detection-Paper#Anchor_Base)
   * [Anchor_Free](https://github.com/aliciashen0118/Object-Detection-Paper#Anchor_Free)
   * [DETR](https://github.com/aliciashen0118/Object-Detection-Paper#DETR)
   * [2020](https://github.com/aliciashen0118/Object-Detection-Paper#2020)
## Summary
   * **Deep Learning for Generic Object Detection A Surve**  
     *Li Liu,Wanli Ouyang,Xiaogang Wang,Paul Fieguth,Jie Chen,Xinwang Liu,Matti Pietik¨ainen*  
     arXiv 2018,[[PDF]](https://arxiv.org/pdf/1809.02165v1.pdf)  
## CNN
   * **【AlexNet】Scalable Object Detection using Deep Neural Networks**  
   *Alex Krizhevsky,Ilya Sutskever,Geoffrey E. Hinton*  
   ILSVRC 2012,[[PDF]](papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf)
   * **【VGG】very Deep Convolutional Networks for Large-Scale Image Recognition**  
     *Karen Simonyan, Andrew Zisserman*  
     ILSVRC 2014,[[PDF]](https://arxiv.org/pdf/1409.1556.pdf)  
   * **【ResNet】Deep Residual Learning for Image Recognition**  
     *Kaiming He,Xiangyu Zhang,Shaoqing Ren,Jian Sun*  
     ILSVRC 2015,[[PDF]](https://arxiv.org/pdf/1512.03385.pdf)  
## Anchor_Base
   * **【MultiBox】Scalable Object Detection using Deep Neural Networks**  
     *Dumitru Erhan, Christian Szegedy, Alexander Toshev, Dragomir Anguelov*  
     CVPR 2014,[[PDF]](https://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Erhan_Scalable_Object_Detection_2014_CVPR_paper.pdf)  
   * **【OverFeat】OverFeat:Integrated Recognition, Localization and Detection using Convolutional Networks**  
     *Pierre Sermanet,David Eigen,Xiang Zhang,Michael Mathieu,Rob Fergus,Yann LeCun*  
     ICLR 2014,[[PDF]](https://arxiv.org/pdf/1312.6229.pdf),[[code]](https://github.com/sermanet/OverFeat)
   * **【R-CNN】Rich feature hierarchies for accurate object detection and semantic segmentation Tech report (v5)**  
     *Ross Girshick,Jeff Donahue,Trevor Darrell,Jitendra Malik*  
     CVPR 2014,[[PDF]](https://arxiv.org/pdf/1311.2524.pdf),[[code]](https://github.com/rbgirshick/rcnn)
   * **【SPP】Spatial Pyramid Pooling in Deep Convolutional Networks for Visual Recognition**  
     *Kaiming He,Xiangyu Zhang,Shaoqing Ren,and Jian Sun*  
     ECCV 2014,[[PDF]](https://arxiv.org/pdf/1406.4729.pdf),[[code]](https://github.com/ShaoqingRen/SPP_net)
   * **【Fast R-CNN】Fast R-CNN**  
     *Ross Girshick*  
     ICCV 2015,[[PDF]](https://arxiv.org/pdf/1504.08083.pdf),[[code]](https://github.com/rbgirshick/fast-rcnn)
   * **【Faster R-CNN】Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks**  
     *Shaoqing Ren,Kaiming He,Ross Girshick,Jian Sun*  
     NIPS 2015,[[PDF]](https://papers.nips.cc/paper/5638-faster-r-cnn-towards-real-time-object-detection-with-region-proposal-networks.pdf),[[code]](https://github.com/rbgirshick/py-faster-rcnn)
   * **【OHEM】Training Region-based Object Detectors with Online Hard Example Mining**  
     *Abhinav Shrivastava,Abhinav Gupta,Ross Girshick*    
     CVPR 2016,[[PDF]](https://arxiv.org/pdf/1604.03540.pdf),[[code]](https://github.com/abhi2610/ohem)
   * **【Yolo v1】You Only Look Once:Unified, Real-Time Object Detection**  
     *Joseph Redmon,Santosh Divvala,Ross Girshic,Ali Farhadi*  
     CVPR 2016,[[PDF]](https://arxiv.org/pdf/1506.02640.pdf),[[code]](https://pjreddie.com/darknet/yolo/)
   * **【SSD】SSD: Single Shot MultiBox Detector**  
     *Wei Liu,Dragomir Anguelov,Dumitru Erhan,Christian Szegedy,Scott Reed,Cheng-Yang Fu,Alexander C. Berg*  
     ECCV 2016,[[PDF]](https://arxiv.org/pdf/1512.02325.pdf),[[code]](https://github.com/weiliu89/caffe/tree/ssd)
   * **【R-FCN】R-FCN: Object Detection via Region-based Fully Convolutional Networks**  
     *Jifeng Dai,Yi Li,Tsinghua University,Kaiming He*  
     NIPS 2016,[[PDF]](https://arxiv.org/pdf/1605.06409.pdf),[[code]](https://github.com/daijifeng001/R-FCN)
   * **【Yolo v2】YOLO9000:Better, Faster, Stronger**  
     *Joseph Redmon,Ali Farhadi*  
     CVPR 2017,[[PDF]](https://arxiv.org/pdf/1612.08242.pdf),[[code]](https://pjreddie.com/darknet/yolo/)
   * **【FPN】Feature Pyramid Networks for Object Detection**  
     *Tsung-Yi Lin1,2, Piotr Doll´ar,Ross Girshick,Kaiming He,Bharath Hariharan,Serge Belongie*  
     CVPR 2017,[[PDF]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Lin_Feature_Pyramid_Networks_CVPR_2017_paper.pdf)
   * **【RetinaNet】Focal Loss for Dense Object Detection**  
     *Tsung-Yi,Lin Priya,Goyal Ross,Girshick,Kaiming He,Piotr Doll´ar*  
     ICCV 2017,[[PDF]](https://arxiv.org/pdf/1708.02002.pdf),[[code]](https://github.com/fizyr/keras-retinanet)
   * **【Mask R-CNN】Mask R-CNN**  
     *Kaiming He,Georgia Gkioxari,Piotr Doll´ar,Ross Girshick*  
     ICCV 2017,[[PDF]](http://openaccess.thecvf.com/content_ICCV_2017/papers/He_Mask_R-CNN_ICCV_2017_paper.pdf),[[code]](https://github.com/facebookresearch/Detectron)
   * **【YOLOv3】YOLOv3: An Incremental Improvement**  
     *Joseph Redmon,Ali Farhadi*  
     arXiv 2018,[[PDF]](https://pjreddie.com/media/files/papers/YOLOv3.pdf),[[code]](https://pjreddie.com/darknet/yolo/)
   * **【RefineDet】Single-Shot Refinement Neural Network for Object Detection**  
     *Shifeng Zhang,Longyin Wen,Xiao Bian,Zhen Lei,Stan Z. Li*  
     CVPR 2018,[[PDF]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_Single-Shot_Refinement_Neural_CVPR_2018_paper.pdf),[[code]](https://github.com/sfzhang15/RefineDet)
   * **【Cascade R-CNN】Cascade R-CNN: Delving into High Quality Object Detection**  
     *Zhaowei Cai,Nuno Vasconcelos*  
     CVPR 2018,[[PDF]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Cai_Cascade_R-CNN_Delving_CVPR_2018_paper.pdf),[[code]](https://github.com/zhaoweicai/cascade-rcnn)
## Anchor_Free
   * **【CenterNet】Objects as Points**  
     *Xingyi Zhou,Dequan Wang,Philipp Kr¨ahenb¨uhl*  
     arXiv 2019,[[PDF]](https://arxiv.org/pdf/1904.07850.pdf),[[code]](https://github.com/xingyizhou/CenterNet)
## DETR

## 2020
   * **Few-Shot Object Detection with Attention-RPN and Multi-Relation Detector**  
     *Qi Fan,Wei Zhuo,Chi-Keung Tang,Yu-Wing Tai*  
     CVPR 2020,[[PDF]](https://arxiv.org/pdf/1908.01998.pdf)
   * **【Context R-CNN】Context R-CNN: Long Term Temporal Context for Per-Camera Object Detection**  
     *Sara Beery,Guanhang Wu,Vivek Rathod,Ronny Votel,Jonathan Huang*  
     CVPR 2020,[[PDF]](https://arxiv.org/pdf/1912.03538.pdf)  
   * **【D2Det】D2Det: Towards High Quality Object Detection and Instance Segmentation**  
     *Jiale Cao,Hisham Cholakkal,Rao Muhammad Anwer,Fahad Shahbaz Khan,Yanwei Pang,Ling Shao*  
     CVPR 2020,[[PDF]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cao_D2Det_Towards_High_Quality_Object_Detection_and_Instance_Segmentation_CVPR_2020_paper.pdf),[[code]](https://github.com/JialeCao001/D2Det)  
   * **【AugFPN】AugFPN: Improving Multi-scale Feature Learning for Object Detection**  
     *Chaoxu Guo,Bin Fan,Qian Zhang,Shiming Xiang,Chunhong Pan*  
     CVPR 2020,[[PDF]](https://arxiv.org/pdf/1912.05384.pdf),[[code]](https://github.com/Gus-Guo/AugFPN)
