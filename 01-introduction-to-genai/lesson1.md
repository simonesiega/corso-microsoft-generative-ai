# Lesson 1 - Tokenization in Generative AI

Generative AI relies on large language models (LLMs) to understand and generate text. One of the fundamental processes that allows LLMs to process language is **tokenization**. Tokenization is the process of converting raw text into **tokens**, which are numerical representations that the model can process.

---

## What is a Token?

A token is a unit of text that can represent:

- A full word (e.g., "cat")
- A subword or word piece (e.g., "biol" + "ogy" for "biology")
- Individual characters in some cases
- Special symbols, punctuation, or whitespace

Tokens allow the model to handle **vocabulary efficiently** and to generalize over words it has never seen before.

---

## How Tokenization Works

1. Input text is broken down into tokens.
2. Each token is mapped to a unique **numeric ID**.
3. The sequence of token IDs is fed into the model for processing.
4. The model predicts the next token or generates outputs based on the tokenized input.

![Token division illustration](01-introduction-to-genai/images/Input-to-tokens.png)

```text
Example Text: "Many words map to one token, but some don't: indivisible."  
Token IDs: [12, 345, 678, ...] (corresponding to each token)
```

## Special Cases in Tokenization

- **Unicode characters and emojis** may be split into multiple tokens representing underlying bytes.  
  Example: 🤚🏾 → multiple tokens

- **Sequences of characters frequently appearing together** may be grouped as a single token.  
  Example: 1234567890 → one token

![Token IDs illustration](01-introduction-to-genai/images/Input-to-tokens-IDs.png)

---

## Why Tokenization Matters

- Enables LLMs to **process any text input**, including words not seen during training.
- Affects **sequence length** and computational resources.
- Directly influences model performance, output quality, and token efficiency.

---

## Technical Notes

- On average, in GPT-style models, **one token represents roughly 4 characters or 0.75 words**.
- Rare or novel words are often **split into subword tokens**, allowing the model to understand and generate them correctly.
- Tokenization is a **critical step for understanding how the model “reads” and “writes” language**.

---

## Summary

Tokenization bridges the gap between natural language and model-readable numerical sequences. It is essential for working with LLMs, optimizing input, and interpreting model behavior in applications ranging from chatbots to code generation.
