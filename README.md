# 📝 Next Word Prediction Using LSTM

This project demonstrates a **next word prediction** system using a Long Short-Term Memory (LSTM) network. The model predicts the next word in a sequence based on the text corpus of Plato's *Republic*.

---

## 🌟 Project Highlights

- **Data Preprocessing**: Cleaned, tokenized, and structured text for model training. 🧹
- **LSTM Network**: Built an LSTM model for sequential data prediction. 🤖
- **Text Generation**: Predicted coherent next words based on seed input. ✨
- **Model Saving**: Saved the trained model and tokenizer for future use. 💾

---

📊 **Data Overview**

- The dataset is the full text of Plato's Republic. The text is cleaned, tokenized, and converted into sequences for model training.

🤖 **Model Details**

Model Type: LSTM-based sequence model

Layers:

Embedding Layer

2 LSTM Layers

Fully Connected Dense Layer with ReLU activation

Output Layer with Softmax activation

Loss Function: Categorical Crossentropy

Optimizer: Adam

🧪 **Model Performance**

The model trains over 50 epochs with a batch size of 128, achieving satisfactory text predictions for sequential inputs.


