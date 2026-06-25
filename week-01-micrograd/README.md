# Week 01 — Micrograd: Backpropagation from Scratch

## 🎯 Goal
Build a tiny autograd engine that implements backpropagation over a dynamically built DAG.

## 📺 Resource
[The spelled-out intro to neural networks and backpropagation](https://www.youtube.com/watch?v=VMj-3S1tku0)

## 📝 What I'm Learning
- What is a derivative and why it matters in neural networks
- How to build a `Value` class that tracks gradients
- Forward pass and backward pass
- Chain rule in practice

## 📁 Files
- `micrograd.py` — the autograd engine
- `demo.ipynb` — experiments and notes

## ✅ Checklist
- [ ] Implement `Value` class with `+`, `*`, `tanh`
- [ ] Implement `.backward()` method
- [ ] Build a simple neural network using micrograd
- [ ] Understand every line of code
