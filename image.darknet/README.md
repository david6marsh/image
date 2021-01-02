# image.darknet: Image classification and Object Detection based on darknet

I've forked this in order to adapt darknet with a very minor tweak that outputs the coordinates of the objects detected. I'm using the advice from [Brian O'Donnell on stack exchange](https://stackoverflow.com/questions/44544471/how-to-get-the-coordinates-of-the-bounding-box-in-yolo-object-detection).

The papers from YOLO suggest that the cost of its great speed is relatively 'loose' accuracy in placing rectangles around objects. You need to decide if this accuracy-speed trade-off suits your needs.

This R package provides the following functionality based on darknet https://github.com/pjreddie/darknet:

- Image classification with deep learning models AlexNet, Darknet, VGG-16, Extraction (GoogleNet) and Darknet19. 
- Object detection using the state-of-the art YOLO detection system. Background: https://arxiv.org/pdf/1506.02640.pdf

## Installation

See instructions at https://github.com/bnosac/image

## Support in machine learning, robotics or image recognition

Need support in machine learning, robotics or image recognition?
Contact BNOSAC: http://www.bnosac.be



    
