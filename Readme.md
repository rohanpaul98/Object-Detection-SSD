<h1 style = "color:blue"> Object Detection Using TensorFlow API</h1>
<h2>Introduction</h2>
<p> This projects aims at object detection with a very high accuracy using pre-trained light weight SSD-MobileNet V3 architecture. 
My project describes how object detection models can be trined very easily and accurately using the TEnsorFlow API.
Here we have also used OpenCV in order to draw the rectangles around the objects and also to load the pre-trained frozen TensorFlow models.
<h4>Challenges  :</h4>
The main challenge faced by me was getting the config file which I finally found at https://github.com/opencv/opencv/wiki/TensorFlow-Object-Detection-API which is the wiki page of TensorFlow API . 
<h4>Technologies Used  :</h4>OpenCV 
</p>
<h2>Installations</h2>

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install opencv and matplotlib .
```bash
pip install opencv-python
```
```bash
pip install matplotlib
```
<h2>BrainStorming</h2>
<h4>Image Classification/Recognition</h4>
<p>It is the process of classifying the images to the categories they belong to based on their salient features.</p>
 Deep learning Algorithms for Image Classification:
-AlexNet</br>
-GoogleNet</br>
-MobileNet</br>
-VGGNet</br>

<h4>Object Detection</h4>
<p>Object Detection specifies the location of multiple objects in a image</p>
-Classification</br>
-Localization
</br>
<p>Famous Algorithms</p>
-SSD-MobileNetv2,SSD-MobileNetv3</br>
-YOLO v1,v2</br>

<p>Famous Dataset</p>
- COCO-> 80 classes

<h2>Run network in OpenCV</h2>
<p>OpenCV needs an extra configuration file to import object detection models from TensorFlow. It's based on a text version of the same serialized graph in protocol buffers format (protobuf).</p>
Use existing config file for your model:
MobileNet-SSD v3 (Version:2020_01_14) 

[Config](https://gist.github.com/dkurt/54a8e8b51beb3bd3f770b79e56927bd7)

<h2>Contributions:</h2>
<p>
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
Please make sure to update tests as appropriate.
</p>