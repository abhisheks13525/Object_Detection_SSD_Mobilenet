# Object_Detection_SSD_Mobilenet
Object localization and identification are two different tasks that are put together to achieve this singular goal of object detection.
Here Detection of any single class from the classes provided by COCO dataset has been performed
The SSD architecture is a single convolution network that learns to predict bounding box locations and classify these locations in one pass.By using SSD, we only need to take one single shot to detect multiple objects within the image, while regional proposal network (RPN) based approaches such as R-CNN series that need two shots, one for generating region proposals, one for detecting the object of each proposal. Thus, SSD is much faster compared with two-shot RPN-based approaches.
