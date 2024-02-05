# 🚀 VOCDetection dataset

[Link to kaggle](https://www.kaggle.com/code/anastasiakorotkova/vocdetection)

## Metric : MeanAveragePrecision()

## Two-shot detection 

Two-step solution to the problem:
- Find “candidates” - rectangles where there is most likely something.
- Classify these rectangles.

In the detection task we will additionally train the following model: 
- FastRCNNPredictor
- 15 epochs

## Dataset: 
VOCDetection (20 classes)
