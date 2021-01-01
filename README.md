# Car_detection
You will learn about object detection using the very powerful YOLO model. <br/>
Many of the ideas in this notebook are described in the two YOLO papers: <br/>
[Redmon et al., 2016] (https://arxiv.org/abs/1506.02640) and [Redmon and Farhadi, 2016] (https://arxiv.org/abs/1612.08242).

# You will learn to:

* Use object detection on a car detection dataset
* Deal with bounding boxes
* Clarified "YOLO" instructions preceding the code.  
* Added details about anchor boxes.
* Added explanation of how score is calculated.
* `yolo_filter_boxes`: added additional hints.  Clarify syntax for argmax and max.
* `iou`: clarify instructions for finding the intersection.
* `iou`: give variable names for all 8 box vertices, for clarity.  Adds `width` and `height` variables for clarity.
* `iou`: add test cases to check handling of non-intersecting boxes, intersection at vertices, or intersection at edges.
* `yolo_non_max_suppression`: clarify syntax for tf.image.non_max_suppression and keras.gather.
* "convert output of the model to usable bounding box tensors": Provides a link to the definition of `yolo_head`.
* `predict`: hint on calling sess.run.
* Spelling, grammar, wording and formatting updates to improve clarity.



# Authors

Origanally this is a part of Deep_Learning_Specialization [Coursera](https://www.coursera.org/)

***Ahmed_Hekal***
