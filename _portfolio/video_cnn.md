---
title: "Video Classificator CNN"
excerpt: "Lite version of the Oxford project: Large-scale Video Classification with Convolutional Neural Networks"
collection: portfolio
---

Lite version of the following Oxford project: [Large-scale Video Classification with Convolutional Neural Networks](https://cs.stanford.edu/people/karpathy/deepvideo/deepvideo_cvpr2014.pdf)

## Choosen Sport Labels
|Label ID           |Label Name|
|-------------------|----------|
|398|rugby|
|300|formula racing|
|361|beach volleyball|
|368|basketball|
|415|karate|
|277|motocross|
|111|kitesurfing|
|269|motorcycle racing|
|258|horse racing|
|200|bodybuilding|

# Results
* **Single Frame**![](images/singleframe.png)
* **Single Frame Context**![](images/singleframe_context.png)
* **Single Frame Fovea**![](images/singleframe_fovea.png)
* **Single Frame Multiresolution**![](images/singleframe_multiresolution.png)
* **Multi Frame Early Fusion**![](images/multiframe_earlyfusion.png)
* **Multi Frame Late Fusion**![](images/multiframe_latefusion.png)
* **Multi Frame Slow Fusion**![](images/multiframe_slowfusion.png)

## Summary
|Model Name                      |Test Loss|Test Accuracy Score|Testing Time in minutes|Training Time in hours|
|--------------------------------|---------|-------------------|-----------------------|----------------------|
|SingleResCNN-Stream_Type_None   |0.96767  |0.71325            |0.37903                |1.53495               |
|SingleResCNN-Stream_Type_fovea  |1.26127  |0.58379            |0.17914                |1.20548               |
|SingleResCNN-Stream_Type_context|1.17831  |0.65533            |0.16217                |1.16977               |
|MultiResCNN                     |1.12028  |0.63378            |0.13316                |1.52294               |
|LateFusionCNN                   |1.05671  |0.69669            |0.37975                |3.01682               |
|EarlyFusionCNN                  |1.08308  |0.67226            |0.67731                |3.79941               |
|SlowFusionCNN                   |1.27412  |0.6623             |1.42234                |7.80681               |
