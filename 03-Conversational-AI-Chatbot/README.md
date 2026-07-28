# 💬 Experiment 03 - Conversational AI Chatbot

## 🎯 Aim

To develop a conversational AI chatbot using a transformer-based
language model that can understand user input and generate meaningful
responses.

## 📖 Description

Conversational AI enables computers to interact with users through
natural language.

In this experiment, a pre-trained transformer-based language model is
used to build a simple chatbot. The chatbot accepts text input from the
user and generates an appropriate response using Natural Language
Processing (NLP) and transformer models.

## 🛠️ Technologies Used

- Python
- Hugging Face Transformers
- PyTorch
- Transformer-based Language Models
- Natural Language Processing (NLP)

## 🧠 How It Works

The basic workflow of the chatbot is:

```text
User Input
    ↓
Tokenizer
    ↓
Transformer Language Model
    ↓
Response Generation
    ↓
Chatbot Response
```

### 1. User Input

The user enters a message or question.

### 2. Tokenization

The input text is converted into tokens that can be understood by
the transformer model.

### 3. Transformer Model

The pre-trained language model processes the tokens and predicts an
appropriate response.

### 4. Response Generation

The generated tokens are converted back into human-readable text.

### 5. Conversation

The chatbot displays the generated response to the user.

## 💬 Example Conversation

**User:**

> Hello! What is Generative AI?

**Chatbot:**

> Generative AI is a type of artificial intelligence that can create
> new content such as text, images, audio, and code based on patterns
> learned from existing data.

## 💻 Implementation

The chatbot is implemented in Python using a pre-trained
transformer-based language model.

The program continuously accepts user input and generates responses
until the user chooses to exit the conversation.

## 📸 Output

The following screenshot shows a sample conversation with the
AI chatbot.

![Conversational AI Chatbot Output](output.png)

## ▶️ How to Run

### 1. Install the required libraries

```bash
pip install transformers torch
```

### 2. Run the chatbot

```bash
python chatbot.py
```

### 3. Start chatting

Enter a message when prompted by the program.

To stop the chatbot, enter:

```text
exit
```

## ✅ Result

A conversational AI chatbot using a transformer-based language model
was successfully developed.

The chatbot accepts natural-language user input and generates
contextually relevant responses using a pre-trained transformer model.

---

## 📚 Experiment Information

**Experiment No:** 03  
**Topic:** Conversational AI Chatbot using Transformer-based Language Models  
**Course Outcome:** CO2
