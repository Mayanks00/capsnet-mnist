# 🧠 Capsule Network (CapsNet) on MNIST using PyTorch

This project implements a **Capsule Neural Network** (CapsNet) using **PyTorch** to classify handwritten digits from the **MNIST dataset**. It achieves **state-of-the-art performance** with high accuracy and dynamic routing between capsules.

---

## 📌 Project Highlights

- ✅ Implemented a fully functional **CapsNet** architecture.
- 🧠 Achieved **99.27% test accuracy** in just **10 epochs**.
- 📊 Uses the standard **MNIST** dataset.
- 🛠 Built using **PyTorch** with custom training and loss functions.
- 🔍 Includes logging of training loss and accuracy per epoch.

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `Copy_of_Capsnet.ipynb` | Jupyter Notebook with full code and outputs |
| `README.md` | Project documentation |
| `requirements.txt` | List of required Python libraries |

---

## 🚀 How to Run This Project

### 1. Clone the Repo

```bash
git clone https://github.com/your-username/capsnet-mnist.git
cd capsnet-mnist
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Open and Run the Notebook

Use Jupyter or Google Colab:

- **Jupyter Notebook**
```bash
jupyter notebook Copy_of_Capsnet.ipynb
```

- **Google Colab**
> Upload the `.ipynb` file to https://colab.research.google.com and run all cells.

---

## 💾 (Optional) Save the Model

At the end of the notebook, add the following code to save the model:

```python
torch.save(model.state_dict(), 'capsule_model.pth')
```

To load it later:

```python
model.load_state_dict(torch.load('capsule_model.pth'))
model.eval()
```

---

## 🧠 Dataset Used

- [MNIST Digits Dataset](http://yann.lecun.com/exdb/mnist/)
- Automatically downloaded via `torchvision.datasets`

---

## 📚 Requirements

- Python 3.7+
- PyTorch
- torchvision
- matplotlib
- numpy

(See `requirements.txt` for full list)

---

## 🙌 Credits

Developed by **Mayank Pratap Singh** as part of a deep learning project to explore Capsule Networks using PyTorch.

---

## ⭐ Star the repo if you found it helpful!
