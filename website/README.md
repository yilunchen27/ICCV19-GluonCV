ICCV 2019 Tutorial: Everything You Need to Know to Reproduce SOTA Deep Learning Models
======================================================================================

<h3>Time: Sunday, October 27, 2019<br/>Location: Same venue as the main conference, [COEX Convention Center](https://goo.gl/maps/VKDgLyYf8NDC1e4E6)</h3>

<span style="color:grey">Presenter: Zhi Zhang, Muhyun Kim, Jiyang Yang</span><br/>



<a href="https://aws.amazon.com/"><img src="_static/aws_logo.png" alt="AWS Icon" height="45"></a> &nbsp; <a href="https://aws.amazon.com/"><img src="_static/amazon_ai.png" alt="AmazonAI Icon" height="58"></a> &nbsp; <a href="https://aws.amazon.com/sagemaker/neo/"><img src="_static/neo.png" alt="Neo Icon" height="58"></a> &nbsp; <a href="https://beta.mxnet.io/"><img src="_static/apache_incubator_logo.png" alt="Apache Incubator Icon" height="39"></a> &nbsp; <a href="https://beta.mxnet.io/"><img src="_static/mxnet_logo_2.png" alt="MXNet Icon" height="39"></a> &nbsp; <a href="https://gluon-nlp.mxnet.io/"><img src="_static/gluon_logo_horizontal_small.png" alt="Gluon Icon" height="42"></a> &nbsp; <a href="http://tvm.ai"><img src="_static/tvm.png" alt="TVM Icon" height="32"></a>

Abstract
--------

Deep Learning has become the de facto standard algorithm in computer vision. There are a surge amount of approaches being proposed every year for different tasks. Reproducing the complete system in every single detail can be problematic and time-consuming, especially for the beginners. Existing open-source implementations are typically not well-maintained and the code can be easily broken by the rapid updates of the deep learning frameworks. In this tutorial, we will walk through the technical details of the state-of-the-art (SOTA) algorithms in major computer vision tasks, and we also provide the code implementations and hands-on tutorials to reproduce the large-scale training in this tutorial.

Agenda
------

| Time        | Title                                                                  | Slides    | Notebooks  |
|-------------|------------------------------------------------------------------------|-----------|------------|
| 8:00-8:15   | Welcome and AWS Setup                                                  | [link][0] | [link][01] |
| 8:15-8:30   | Deep Learning and Gluon Basics (NDArray, AutoGrad, Libraries)          |           | [link][11],[link][12] |
| 8:30-9:30   | Bags of Tricks for Image Classification (ResNet, MobileNet, Inception) | [link][2] | [link][21] |
| 9:30-10:30  | Understanding Object Detectors (SSD, Faster RCNN, YOLOV3)              | [link][3] | [link][31] |
| 10:30-11:30 | Semantic segmentation algorithms (FCN, PSPNet, DeepLabV3)              | [link][4] | [link][41] |
| 11:30-12:00 | Painless Deployment (C++, TVM)                                         |           | [link][51],[link][52] |
| 12:00-12:15 | Q&A and Closing                                                        |           |            |

Q&A
---

TODO

[0]: https://github.com/zhreshold/ICCV19-GluonCV/blob/master/slides/GluonCV.pptx
[2]: https://github.com/zhreshold/ICCV19-GluonCV/blob/master/slides/Classification.pptx
[3]: https://github.com/zhreshold/ICCV19-GluonCV/blob/master/slides/Detection.pptx
[4]: https://github.com/zhreshold/ICCV19-GluonCV/blob/master/slides/Segmentation.pptx

[01]: https://github.com/zhreshold/ICCV19-GluonCV/blob/master/00_setup/use_aws.ipynb
[11]: https://github.com/zhreshold/ICCV19-GluonCV/blob/master/01_basics/autograd.ipynb
[12]: https://github.com/zhreshold/ICCV19-GluonCV/blob/master/01_basics/ndarray.ipynb
[21]: https://github.com/zhreshold/ICCV19-GluonCV/blob/master/02_classification/ImageClassification.ipynb
[31]: https://github.com/zhreshold/ICCV19-GluonCV/blob/master/03_detection/ObjectDetection.ipynb
[41]: https://github.com/zhreshold/ICCV19-GluonCV/blob/master/04_segmentation/SemanticSegmentation.ipynb
[51]: https://github.com/zhreshold/ICCV19-GluonCV/blob/master/05_deployment/export_network.ipynb
[52]: https://github.com/zhreshold/ICCV19-GluonCV/blob/master/05_deployment/cpp_inference.ipynb