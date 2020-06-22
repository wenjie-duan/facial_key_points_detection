#  Key Points Detection

## Team Member: 
Wenjie Duan, Peng Liu


## Kaggle Competition
- https://www.kaggle.com/c/facial-keypoints-detection/data

## Methods 
- Implemented key points detection with Pytorch. 
- Implemented data augmentation(rotation, flip-over etc.) to have better results. 
- Handle missing keypoints:
  - 2 subsets: [Check this notebook.](./pytorch.ipynb) and [this.](./kaggle_keypoints_detection-aug_2sets-res34-dl2020.ipynb)
  - Implemented mask vector to handle missing values. [Check this notebook.](./kaggle_keypoints_detection-albuaug_mask-res34-dl2020.ipynb)
- Tried fast.ai API. [Check this notebook.](./fastai_augmentation.ipynb)
## Results 
- Achived test RMSE=1.68 on private leaderboard. [Check this notebook.](./kaggle_keypoints_detection-aug_2sets-res34-dl2020.ipynb)
