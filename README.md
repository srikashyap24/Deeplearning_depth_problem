# Deeplearning_depth_problem

# 🧠 MNIST Deep Network Experiment

This project explores how increasing the number of hidden layers in a neural network affects its performance on the MNIST handwritten digit classification task.

We used a simple feedforward neural network built with TensorFlow and Keras, and trained multiple models with varying depths (1, 10, 20, 30, and 50 hidden layers). Each model was evaluated on the MNIST test set, and we plotted how accuracy changes with increasing depth.

## 📊 Key Observation

> **Adding more layers doesn't always mean better accuracy!**

As our professor explained during the lecture, deep networks can suffer from:

- **Overfitting** – the model memorizes the training data but doesn't generalize well to new data.
- **Vanishing gradients** – gradients get smaller as they are backpropagated, making it harder to train deeper layers.
- **Inefficient training** – deeper networks can be harder to optimize and may require more epochs or careful initialization.

Without techniques like **Dropout**, **Batch Normalization**, or **Residual Connections**, simply stacking more layers might hurt performance rather than help.

## 📦 Technologies Used

- Python
- TensorFlow / Keras
- Matplotlib

## 📁 Project Structure

- `Demonstration_ANN_DEEP_PROBLEM.ipynb` – Core script to build and train models with varying depths.
- `README.md` – You're reading it!

## 🖼️ Sample Output

The plot below shows how test accuracy changes with increasing hidden layers:

*(insert your accuracy plot here)*

## ✅ Conclusion

This experiment demonstrates the importance of thoughtful model design. Simply increasing the depth doesn't guarantee better results – model architecture, regularization, and training strategy play a crucial role in performance.

## 📚 Credits

Special thanks to our **Dr. Huseyin Kusetogullari** for explaining the limitations of deep networks and guiding us through this experiment.
