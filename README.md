# Image-Classification-Model Using Mnist Dataset
🚀 Project using TensorFlow and Keras 🚀

🔧 Hyperparameters Used:
Convolutional Layers: 1
Filters: 32
Kernel Size: (3, 3)
Pooling: MaxPooling with pool size (2, 2)
Dense Layers: 1 with 128 neurons and ReLU activation
Output Layer: Softmax activation with 10 neurons for 10 classes

📊 Model Performance:
Training Accuracy: ~99%
Validation Accuracy: ~98%
Test Accuracy: ~98% (on unseen data)

📈 Loss Function and Optimization:
Loss Function: Categorical Cross-Entropy
Optimizer: Adam
🔍 Model Evaluation:
Trained for 10 epochs with a batch size of 128
Used 20% of the training set as the validation set

🖼️ Visualizing the Results:
I visualized the training and validation loss over epochs using Matplotlib. Additionally, I randomly selected 20 images from the training set, and I plotted them along with their true labels and the model's predictions. Correct predictions are color-coded in green, and incorrect predictions are color-coded in red.
