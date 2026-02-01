# 🧥 Fashion-MNIST-Image-Classification

📓 **Google Colab Link: (https://colab.research.google.com/drive/1UzEBHm910_0trYfUNRuhEHFa7XB-_zY7?usp=sharing)**

---

## 1. What is the Fashion MNIST dataset?

Fashion MNIST is a popular machine learning dataset used for image classification, created as a modern replacement for the classic MNIST handwritten digits dataset. Each image is **28×28 pixels** and represents different clothing items such as:

- Shirts, CoatS and Dresses
- Shoes and Sandals
- Trousers
- Bags

-----

## 2. Why do we normalize image pixel values before training?

Normalization makes training faster, more stable, and more accurate.

-----

## 3. Layers used in the neural network and their functions.

| **Layer** | **Function** |
|-----------|--------------|
| **Input** | Receives the image data. Each image is **28 × 28 pixels**. |
| **Flatten** |Converts 2D image data into a 1D array. |
| **Dense (Fully Connected)** | Learns patterns and relationships in the data. Commonly uses ReLU activation. |
| **Convolutional** | Extracts local features (edges, textures). Learns spatial patterns in images. |
| **Max Pooling** | Reduces image size while keeping important features. Improves efficiency and reduces overfitting |

The neural network consists of input, flatten, dense, and output layers, with optional convolution, pooling, and dropout layers to improve feature extraction and prevent overfitting.

-----

## 4. What does an epoch mean in model training?

An **epoch** refers to one complete pass of the entire training dataset through the model. 

Based on my observation, The model sees all training samples once. Data is usually split into **batches**

For each batch:
- Predictions are made
- Loss is calculated
- Weights are updated using backpropagation

By observing the changes in accuracy per epoch, I was able to see how the model learned over time.

-----

## 5. Compare the predicted label and actual label for the first test image.

Based on my results, the **predicted label** for the first test image matched the **actual label** provided in the dataset.

This indicates that:
- The model was able to correctly classify the image.
- The model learned useful patterns from the training data.

-----

## 6. What could be done to improve the model’s accuracy?

Improving a model’s accuracy usually comes down to better data, better features, and better training choices.

| **Area** | **Improvement** |
|----------|-----------------|
| **Data** | Clean & add data |
| **Model** | Tune & test models |
| **Training** | Reduce overfitting |
| **Metrics** | Use right metric |





