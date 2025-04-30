# Food-Recognition-and-Calorie-Estimation-using-Deep-Learning

This project uses deep learning to recognize food items from images and estimate their calorie content. It leverages the [Food-101 dataset](https://www.kaggle.com/datasets/dansbecker/food-101) and a pre-trained ResNet18 model to help users track dietary intake and make informed food choices.

---

## Features

- 🔍 Classifies food images into one of 101 food categories but used 10 food categories.
- 🔥 Estimates calorie content based on the predicted food item
- 🧠 Utilizes transfer learning with ResNet18
- ⚙️ Built using PyTorch and torchvision
- 💡 Calorie lookup for nutritional estimation

---

## Dataset

- **Source**: [Food-101 by Lukas Bossard](https://www.vision.ee.ethz.ch/datasets_extra/food-101/)
- **Contains**:
  - 101 food categories used 10 categories in this project.
  - 1000 images per category (750 for training, 250 for testing)
- **Used From**: Kaggle dataset [dansbecker/food-101](https://www.kaggle.com/datasets/dansbecker/food-101)
