# 🔥 Simple PyTorch Learning Model

This is a beginner-friendly PyTorch project that demonstrates how a simple neural network learns using linear layers, loss functions, and optimizers. It walks through the core concepts of machine learning from the ground up, using a hands-on example where a model learns to predict a value.

---

## 🧠 Why I Built This

I created this project as a personal learning exercise to understand the fundamentals of how machine learning works under the hood, especially in PyTorch. I focused on:
- Understanding how loss functions measure performance
- How optimizers adjust the model to reduce error
- How training across multiple epochs improves accuracy
- Writing and understanding a training loop

---

## ⚙️ How It Works

- A simple linear model is created using `torch.nn.Linear`
- Input and target values are defined
- The model makes predictions
- Mean Squared Error (`nn.MSELoss`) is used to calculate how wrong the predictions are
- An optimizer (`torch.optim.SGD`) updates the model based on the error
- A training loop repeats this process across multiple epochs

---

## 📦 Requirements

- Python 3.x
- PyTorch
- (Optional) matplotlib for visualizing loss

Install dependencies using:

```bash
pip install torch matplotlib
```

## 🚀 How to Run
Clone the repo and run the file:

python simple_pytorch_model.py


## Results 
Epoch 1, Loss: 11.3393
Epoch 2, Loss: 8.7214
Epoch 3, Loss: 6.7013
...
Epoch 10, Loss: 1.7020


📈 Concepts Covered

-Tensors in PyTorch
-Linear regression
-Loss functions (MSE)
-Optimizers (SGD)
-Gradient descent
-Backpropagation
-Epochs and model training

## 🌱 Future Improvements

- [ ] Add multiple training examples
- [ ] Support for batch training
- [ ] Visualize the loss with matplotlib
- [ ] Predict values in a time series (e.g., sine wave)
- [ ] Wrap code into classes for reusability

- [ ]  Turn model into full time series model with dataset













