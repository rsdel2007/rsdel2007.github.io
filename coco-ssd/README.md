## Object Detection using TensorFlowJS

Here I have used TensorFlowJS's pretrained object detection model ([coco-ssd model](https://github.com/tensorflow/tfjs-models/tree/master/coco-ssd)) to obtain the predictions.
I have simply hosted the code on GitHub page so that it does not require Flask app.

User have to simply input the image and the detected objects will appear as button on the page. 
After pushing any appeared button bounding box coordinate and the cropped imageof that class will appear.

[Coco-ssd dataset](https://github.com/tensorflow/tfjs-models/blob/master/coco-ssd/src/classes.ts) have 90 classes,thus the button of the selected classes will appear.

Here is the [link](https://rsdel2007.github.io/coco-ssd) to the page.
PS:- Have to improve frontend.
