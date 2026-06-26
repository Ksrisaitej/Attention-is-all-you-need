# Transformer From Scratch

This project is my attempt to understand the Transformer architecture by implementing its core components from scratch instead of relying on deep learning frameworks.

The implementation focuses on learning the architecture described in the original "Attention Is All You Need" paper.

## Features

- Token Embeddings
- Positional Encoding
- Scaled Dot-Product Attention
- Multi-Head Attention
- Feed Forward Network
- Residual Connections
- Layer Normalization
- Encoder
- Decoder
- Custom Autograd (`Value` class inspired by micrograd)

## Tech Stack

- Python
- NumPy
- Custom Autograd Engine

## Project Structure

```
Attention is all you need.ipynb
micrograd.py
README.md
```

## Current Status

This is an educational implementation built to understand the Transformer architecture from first principles.

Implemented:
- Encoder
- Decoder
- Multi-Head Attention
- Feed Forward Network
- LayerNorm
- Residual Connections

Currently improving:
- Training pipeline
- Optimization
- Performance
- Code refactoring

## Learning Outcomes

Through this project I gained hands-on understanding of:

- Self-Attention
- Multi-Head Attention
- Positional Encoding
- Encoder-Decoder Architecture
- Forward Propagation
- Automatic Differentiation
- Neural Network Fundamentals

## References

- Attention Is All You Need (2017)
- Andrej Karpathy's micrograd
