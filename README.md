<h1 align="center">🧠 Makemore — Character-Level Language Model (From Scratch)</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-Python-blue?logo=python" />
  <img src="https://img.shields.io/badge/Built%20with-Jupyter%20Notebook-orange?logo=jupyter" />
  <img src="https://img.shields.io/badge/Framework-PyTorch-red?logo=pytorch" />
  <img src="https://img.shields.io/badge/Project-Type-From%20Scratch-success" />
  <img src="https://img.shields.io/badge/License-MIT-green" />
</p>

<p align="center">
  <img src="outputs/sample_generation_preview.png" alt="Sample Output Preview" width="600"/>
</p>

---

## 📘 Overview

Implementation of a **character-level language model** entirely from scratch in pure **Python + PyTorch**, following  
[Andrej Karpathy’s “Makemore”](https://www.youtube.com/watch?v=PaCmpygFfXo) from the *Neural Networks: Zero to Hero* series.

This project trains a small GPT-like model to learn and generate realistic-looking names one character at a time — the fundamental concept behind how **Large Language Models (LLMs)** predict text.

---

## 🧩 Project Structure
makemore/
├── makemore.ipynb # Main notebook: end-to-end implementation
├── names.txt # Dataset (list of training names)
├── outputs/
│ ├── loss_curve.png
│ └── sample_generation_preview.png
└── README.md

yaml
Copy code

---

## 🚀 How to Run
```bash
# 1. Clone repository
git clone https://github.com/Utka7784/Neural-Network.git
cd Neural-Network

# 2. Install dependencies
pip install torch matplotlib numpy jupyter

# 3. Launch notebook
jupyter notebook makemore.ipynb
Execute cells sequentially — every block builds up from tokenization to full text generation.

🧠 Key Concepts Implemented
Character-level tokenization

Feed-forward MLP architecture

Embeddings and activation functions

Cross-entropy loss and optimization

Sampling & temperature-based text generation

📊 Example Output
Prompt	Generated Names
ann	annika, annel, annabel
mic	michel, micka, michal

(Trained on names.txt dataset)

💡 Learnings
How neural nets perform next-character prediction

Relationship between N-gram models and Transformers

Fundamentals behind GPT-style next-token generation

Foundation for understanding and securing LLM architectures

🧭 Next Steps
 Expand to trigram context

 Add positional encodings

 Transition to attention mechanism

 Explore prompt-level adversarial robustness

👨‍💻 Author
Utkarsh Walchale
Cybersecurity & AI Engineer | LLM Security Researcher

Exploring how neural networks learn, fail, and can be secured — one character at a time.

<p align="center"> <a href="https://linkedin.com/in/utkarshwalchale"><img src="https://img.shields.io/badge/LinkedIn-Utkarsh Walchale-blue?logo=linkedin"></a> <a href="https://github.com/Utka7784"><img src="https://img.shields.io/badge/GitHub-Utka7784-black?logo=github"></a> </p>
⚖️ License
Released under the MIT License — free to use, modify, and learn from.

yaml
Copy code

---

## ✅ Steps to Add
1. Create or open `README.md` in your Makemore folder.  
2. Paste the above markdown exactly.  
3. (Optional) add a sample image named `sample_generation_preview.png` inside `outputs/` — it will display automatically.  
4. Push to GitHub:
```bash
git add README.md
git commit -m "Add Makemore project README with badges and preview"
git push -u origin main
