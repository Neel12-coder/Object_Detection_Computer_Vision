# Object_Detection_Computer_Vision
Object Detection in Computer Vision - Algorithms Explored  are YOLO, SSD, RCNN, Faster RCNN

The project is implemented using Single Shot Detection(SSD) and You Look Only Once (YOLOv3) Algorithms. 
SSD object detection is made up of two components: 1. Extracting features maps 2.Convolution filters to detect objects. SSD uses VGG16 to extract features.
YOLOv3 is much faster than SSD while achieving very comparable accuracy. Lets see how YOLO detects the objects in a given image. First, it divides the image into a 13×13 grid of cells. The size of these 169 cells vary depending on the size of the input. For a 416×416 input size that we used in our experiment , the cell size was 32×32. Each cell is then responsible for predicting a number of  boxes in the image

