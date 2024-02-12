# food-detection
Week 1 update- 8-01-24 Finding good sources which actually depict indian food and will be helpful in real world

Week 2 update- 15-01-24 Found research papers as per sir's advice. One contains detection of indian food specifically(cornell) and the other one use deep learning to detect food. These are helpful and now we will try to extract data/code from these papers. Found a code of visual food recognition with paper, need to do research which one to use.

Update 15-02-2024 the IoU loss algorithm is used to calculate the box_loss, which measures the difference between predicted and ground truth bounding boxes. The cls_loss measures the classification error of predicted labels, and the dfl_loss measures the displacement between the predicted and ground truth feature locations in the convolutional feature maps. Each of these losses are computed separately and summed to create the final loss. Will need to adjust the above values with respect to the needs of dataset.
