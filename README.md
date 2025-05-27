
# 🌟 BardNet: A Character-Level LSTM for Shakespearean Text Generation

## 📜 Overview

**BardNet** is a character-level text generation model powered by a Long Short-Term Memory (LSTM) network. Trained on the timeless works of **William Shakespeare**, this model captures the poetic rhythm, vocabulary, and structure of Elizabethan English to generate text in a similar style.

Whether you're a machine learning enthusiast or a literature lover, BardNet offers a fascinating blend of **deep learning** and **classic literature**.

---

## 📂 Repository Structure

```
LSTM_Text_Generation/
│
├── LSTM_Text_Generation_model.ipynb  # Main notebook for training & generation
├── text_gen_lstm.h5                  # Pre-trained LSTM model weights
├── shakespeare.txt                   # Training corpus (Shakespeare’s works)
```

---

## 🧠 Model Architecture

The model follows a simple yet effective architecture:

- **Character embedding layer** to vectorize characters.
- **LSTM layer** to learn temporal dependencies and context.
- **Dense output layer** with softmax to predict the next character.

The network is trained to predict the next character in a sequence based on the previous context.

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

```bash
pip install tensorflow numpy jupyter
```

### Clone the Repository

```bash
git clone https://github.com/niketbhatt2002/LSTM_Text_Generation.git
cd LSTM_Text_Generation
```

### Run the Notebook

```bash
jupyter notebook LSTM_Text_Generation_model.ipynb
```

In the notebook, you can:

- Load the Shakespeare dataset
- Train the model (or load the pre-trained weights)
- Generate text from scratch

---

## ✍️ Example Output

Generated example from a trained model:

```
To be, or not to be: that is the question:
Whether 'tis nobler in the mind to suffer...
```

> Note: Your outputs may vary depending on temperature, sequence length, and training epochs.

---

## 📈 Training Details

- **Data**: Entire works of William Shakespeare (`shakespeare.txt`)
- **Epochs**: 30+ (recommend experimentation)
- **Sequence Length**: 100 characters
- **Framework**: TensorFlow (Keras API)

---

## 🧪 Customization Tips

- Want to train on your own dataset? Replace `shakespeare.txt` with any `.txt` file and re-run the notebook.
- Tune hyperparameters like `sequence_length`, `embedding_dim`, and `LSTM units` for optimal performance.

---

## 🤝 Contributing

Feel free to fork this project, suggest enhancements, or train BardNet on other authors like Edgar Allan Poe, Jane Austen, or modern lyrics!

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 📬 Author

Developed with ❤️ by [niketbhatt2002](https://github.com/niketbhatt2002)
