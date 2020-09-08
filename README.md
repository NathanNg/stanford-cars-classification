# Stanford Cars Image Classification

Image classification of the stanford-cars dataset leveraging the fastai v1. The goal is to get 90%+ accuracy, starting with a basic fastai image classification workflow and RESNET34, RESNET50, and RESNET152 models. 

The notebook was run on Google Cloud on P100 Telsa with 16GB of memory.

## Top Score

| # Run|Fastai|Architecture|Epoch  |Learning Rate| Transform 	| Accuracy 	| Image Size|
|------|------|------------|-------|-------------|-----------	|----------	|---------	|
|   1  |      |ResNet34    |  10   |  1e-4       |  default   |  83.4%   	| 299x299   |
|   2  |      |ResNet34    |  10   |  1e-4       |  Squish    |  89.01%  	| 299x299   |
|   3  |      |ResNet34    |  10   |  1e-4       |  mixup   	|  89.18%  	| 299X299   |
|   4  |      |ResNet50    |  10   |  1e-4       |  default   |  90.85%   | 299x299   |
|   5  |      |ResNet50    |  10   |  1e-4       |  Squish    |  90.92% 	| 299x299   |
|   6  |      |ResNet50    |  10   |  1e-4       |  mixup   	|  90.72%  	| 299X299   |
|   7  |      |ResNet152   |  10   |  1e-4       |  default   |           | 299x299   |
|   8  |      |ResNet152   |  10   |  1e-4       |  Squish    |          	| 299x299   |
|   9  |      |ResNet152   |  10   |  1e-4       |  mixup   	|          	| 299X299   |
