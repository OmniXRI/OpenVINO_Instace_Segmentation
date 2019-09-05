# OpenVINO_Instace_Segmentation

OpenVINO 2019 R2 版
安裝路徑 C:\Program Files (x86)\IntelSWTools\openvino_2019.2.242\

修正 \deployment_tools\inference_engine\demos\mask_rcnn_demo\main.cpp

增加顯示COCO 92類標籤、可信度及各段計算時間功能。

新增輸出範例：

[ INFO ] Image out0.png created!

[ INFO ] Command parse and load inference engine time = 0.147204 sec.

[ INFO ] Load network  (bin/xml) time = 0.0480998 sec.

[ INFO ] Prepare input blob time = 0.0174857 sec.

[ INFO ] Prepare output blob time = 0.0001567 sec.

[ INFO ] Load model to device time = 0.917589 sec.

[ INFO ] Create inference request time = 0.0014885 sec.

[ INFO ] Set input data time = 0.0121736 sec.

[ INFO ] Do inference time = 1.54085 sec.

[ INFO ] Postprocess output blob time = 0.0213765 sec.

[ INFO ] Total time = 2.70643 sec.

[ INFO ] Execution successful

![image](https://raw.githubusercontent.com/OmniXRI/OpenVINO_Instace_Segmentation/master/out_581061_g3r_FP32.png)

完整說明文章請參閱： <a href="http://omnixri.blogspot.com/2019/09/openvino.html" target="_blank">【OpenVINO™教學】土炮影像實例分割型智慧監控系統</a> 

[【OpenVINO™教學】土炮影像實例分割型智慧監控系統](http://omnixri.blogspot.com/2019/09/openvino.html "title" target="_blank")
