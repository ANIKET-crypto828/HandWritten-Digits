# 🧠 Build a Feedforward Neural Network from Scratch (Python) - MNIST Digit Classifier

This repository demonstrates how to build a **simple feedforward neural network** from scratch using **Python** (no deep learning libraries like TensorFlow or PyTorch) to classify handwritten digits from the **MNIST dataset**.

![MNIST Sample](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)

---

## 🚀 Features

- Fully-connected feedforward neural network (Multilayer Perceptron)
- No external machine learning libraries used (pure NumPy)
- Trained on the classic MNIST dataset
- Custom implementation of:
  - Forward propagation
  - Backpropagation
  - Gradient descent
- Accuracy evaluation

---

## 📁 Project Structure

main.py #for running the code


---

## 🧰 Requirements

- Python 3.x
- NumPy

Install dependencies:

```bash
pip install -r requirements.txt



📥 Getting the Data
The script will automatically download and parse the MNIST dataset from Yann LeCun's website (or you can provide the dataset manually).

Alternatively, load from a CSV file or pre-parsed pickle if you already have the data.

🧠 How It Works
The neural network consists of:

Input layer (784 nodes for 28x28 pixel images)

One or more hidden layers (e.g., 128 nodes with ReLU)

Output layer (10 nodes for digits 0–9 with softmax)

The model is trained using backpropagation and cross-entropy loss with stochastic gradient descent (SGD).

▶️ Usage
To train the model:

bash
Copy code
python mnist_nn.py
Modify network parameters like hidden layers, learning rate, epochs inside the script.

📊 Example Output
yaml
Copy code
Epoch 1/25
1500/1500 ━━━━━━━━━━━━━━━━━━━━ 9s 5ms/step - accuracy: 0.8399 - loss: 0.5251 - val_accuracy: 0.9500 - val_loss: 0.1750
Epoch 2/25
1500/1500 ━━━━━━━━━━━━━━━━━━━━ 9s 6ms/step - accuracy: 0.9618 - loss: 0.1335 - val_accuracy: 0.9641 - val_loss: 0.1163
Epoch 3/25
1500/1500 ━━━━━━━━━━━━━━━━━━━━ 6s 4ms/step - accuracy: 0.9745 - loss: 0.0855 - val_accuracy: 0.9693 - val_loss: 0.0987
Epoch 4/25
1500/1500 ━━━━━━━━━━━━━━━━━━━━ 11s 5ms/step - accuracy: 0.9818 - loss: 0.0615 - val_accuracy: 0.9723 - val_loss: 0.0916
Epoch 5/25
1500/1500 ━━━━━━━━━━━━━━━━━━━━ 10s 5ms/step - accuracy: 0.9844 - loss: 0.0487 - val_accuracy: 0.9703 - val_loss: 0.0999
...
Final Test Accuracy: 97.44%
📌 To-Do
 Add mini-batch gradient descent

 Add dropout regularization

 Visualize learning curves

 Implement Adam optimizer

📚 References
MNIST Database

Neural Networks and Deep Learning - Michael Nielsen

NumPy Documentation

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

❤️ Contributing
Feel free to open issues, submit pull requests, or fork this repo to enhance it!

yaml
Copy code



---

Let me know if you'd like me to generate the actual `.py` files for this repo as well.
