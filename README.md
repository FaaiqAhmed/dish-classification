# 🍽️ Pakistani Dish Classification Project

## 📌 Overview

In This project we build a deep learning model to classify images of Pakistani and international dishes using **Transfer Learning** with **ResNet50**. The model was fine-tuned to achieve high classification accuracy across 17 food categories.

---

## 📊 Dataset

The dataset was created by combining two web-scraped food image datasets into a single dataset containing **17 classes** and **~10,000 images**.
You can find the original dataset [here](https://www.kaggle.com/datasets/useractivated/dataset)

### Example Classes

* Biryani
* Butter Chicken
* Samosa
* Paratha
* Haleem
* Chai
* Brownie
* French Fries
* *and more...*

---

## 🤖 Model

* **Architecture:** ResNet50 (Transfer Learning)
* **Stage 1:** Freeze base model and train classifier (**12% accuracy**)
* **Stage 2:** Fine-tune the last layers of ResNet50 (**89.5% accuracy**)

---

## 📈 Results

| Metric        |     Value |
| ------------- | --------: |
| Test Accuracy | **89.5%** |
| Test Loss     | **0.356** |

---

## 📌 Conclusion

Fine-tuning the pre-trained ResNet50 significantly improved performance, increasing accuracy from **12%** to **89.5%**. The project demonstrates the effectiveness of transfer learning for image classification with a relatively modest-sized custom dataset.
