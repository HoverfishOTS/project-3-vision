# Emotion Classification Using Pictures

A 10-week summer research project for high school students.

**Title:** Emotion Classification Using Pictures
**Research question:** Can image-based machine learning models classify human emotions from facial expressions?

## How to start

1. Open [`project_3_vision.ipynb`](project_3_vision.ipynb) -- or launch it directly in Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HoverfishOTS/project-3-vision/blob/main/project_3_vision.ipynb)
2. Switch the runtime to **GPU** (Runtime -> Change runtime type -> T4 GPU).
3. Fill in every `TODO` cell from top to bottom.

Ask your instructor if stuck.

## 10-Week Plan

| Week | Tasks |
|------|-------|
| 1 | Learn basics of computer vision and image-based emotion recognition |
| 2 | Select labeled image dataset (FER-2013). Load directories & Start literature review (1 or 2 references) |
| 3 | Explore image data: size, labels, class balance, examples |
| 4 | Preprocess images: resize, convert to grayscale, normalize pixels |
| 5 | Create baseline model using simple features or MLP |
| 6 | Train CNN or use transfer learning |
| 7 | Evaluate performance using accuracy, F1 score, confusion matrix |
| 8 | Improve model with data augmentation, dropout, tuning |
| 9 | Interpret results, discuss demographic bias and limitations |
| 10 | Prepare final poster/paper and presentation |

## Datasets

- **FER-2013 (Facial Expression Recognition)** -- Consists of 48x48 pixel grayscale images of faces automatically registered. [Kaggle Link](https://www.kaggle.com/datasets/msambare/fer2013)

## Key references

- TensorFlow/Keras CNN Tutorial: <https://www.tensorflow.org/tutorials/images/cnn>
- OpenCV Python Tutorials: <https://docs.opencv.org/master/d6/d00/tutorial_py_root.html>
