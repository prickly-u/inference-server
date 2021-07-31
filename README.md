# TensorRT inference server
Capstone project on the course <a href="https://otus.ru/lessons/cpp-professional/">"C++ Developer. Professional"</a>. <br/>
Asynchronous multithreading server that loads pre-trained face detection model <a href="https://github.com/onnx/models/tree/master/vision/body_analysis/ultraface">UltraFace Onnx</a> into TensorRT inference engine (<a href="https://github.com/NVIDIA/TensorRT">TensorRT samples</a> used as base) and streams frames with detections using <a href="https://en.m.wikipedia.org/wiki/Motion_JPEG">Motion Jpeg</a> over HTTP. The resulting video can be viewed using usual browser; multiple simultaneous requests are supported. <br>
A screencast with demo can be found <a href="https://drive.google.com/file/d/1M-T19DS_6x8Jjloes2lSGkNRFI8nZ74h/view?usp=drivesdk">here</a>. <br/>
The project presentation (rus) can be found <a href="https://docs.google.com/presentation/d/1RKYa--bnTxGL7xGpVLgkUt1JAZztmGTdLoF2ylyT9wU/edit?usp=drivesdk">here</a>. 
