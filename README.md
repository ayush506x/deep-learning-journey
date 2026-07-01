# 🧠 Deep Learning Journey — Neural Networks: Zero to Hero

<div align="center">

![Status](https://img.shields.io/badge/Status-Active-00c8ff?style=for-the-badge)
![Started](https://img.shields.io/badge/Started-June%202026-7c4dff?style=for-the-badge)
![Pace](https://img.shields.io/badge/Pace-30--60%20min%2Fday-28ca41?style=for-the-badge)
![Goal](https://img.shields.io/badge/Goal-Offline%20AI%20Assistant-ff9500?style=for-the-badge)

</div>

---

## 👋 Who Am I & Why This Repo Exists

Hi, I'm **Ayush Mishra** — a Computer Science Engineering student specializing in AI & ML at Lovely Professional University, Lucknow, India.

Most people learn AI by using libraries and calling APIs. I wanted to understand how it **actually works** — from the mathematics of a derivative all the way up to building a GPT transformer.

So I started this journey.

This repository documents my **self-directed 16-week deep learning curriculum**, where I study neural networks from absolute first principles, write every line of code myself, and build toward a capstone goal of creating a **fully offline personal AI assistant**.

Every commit here is a real study session. Every folder is a week of work.

---

## 🎯 The Goal

> **Build a fully offline personal AI assistant** — no API calls, no cloud dependency, runs entirely on local hardware.

To get there, I need to understand:
- How neural networks learn (backpropagation)
- How language models work (bigram → MLP → transformer)
- How to build a GPT from scratch
- How to fine-tune and run models locally

That's exactly what this curriculum covers.

---

## 🗺️ The Roadmap

I am following **Andrej Karpathy's Neural Networks: Zero to Hero** series — widely considered the best resource for understanding deep learning from first principles.

### 📅 Full Progress Tracker

| Phase | Week | Topic | Video | Status |
|-------|------|-------|-------|--------|
| 0 | Pre | 3Blue1Brown — Neural Networks (4 episodes) | [Watch](https://www.youtube.com/watch?v=aircAruvnKk) | 🔄 In Progress |
| 0 | Pre | 3Blue1Brown — Essence of Calculus (Ep 1–3) | [Watch](https://www.youtube.com/watch?v=WUvTyaaNkzM) | ⏳ Upcoming |
| 1 | 01–02 | Micrograd — Backpropagation from scratch | [Watch](https://www.youtube.com/watch?v=VMj-3S1tku0) | ⏳ Upcoming |
| 2 | 03–04 | Makemore Part 1 — Bigram language model | [Watch](https://www.youtube.com/watch?v=PaCmpygFfXo) | ⏳ Upcoming |
| 2 | 05–06 | Makemore Part 2 — MLP | [Watch](https://www.youtube.com/watch?v=TCH_1BHY58I) | ⏳ Upcoming |
| 2 | 07–08 | Makemore Part 3 — Activations & BatchNorm | [Watch](https://www.youtube.com/watch?v=P6sfmUTpUmc) | ⏳ Upcoming |
| 2 | 08 | Makemore Part 4 — Backprop Ninja | [Watch](https://www.youtube.com/watch?v=q8SA3rM6ckI) | ⏳ Upcoming |
| 2 | 09 | Makemore Part 5 — WaveNet | [Watch](https://www.youtube.com/watch?v=t3YJ5hKiMQ0) | ⏳ Upcoming |
| 3 | 10–12 | GPT from Scratch — Part 1 | [Watch](https://www.youtube.com/watch?v=kCc8FmEb1nY) | ⏳ Upcoming |
| 3 | 13–14 | GPT Tokenizer — BPE from scratch | [Watch](https://www.youtube.com/watch?v=zduSFxRajkE) | ⏳ Upcoming |
| 4 | 15–16 | Capstone — Offline Personal AI Assistant | — | ⏳ Upcoming |

**Legend:** ✅ Done &nbsp;·&nbsp; 🔄 In Progress &nbsp;·&nbsp; ⏳ Upcoming

---

## 📁 Repository Structure

```
deep-learning-journey/
│
├── 📁 week-01-micrograd/
│   ├── README.md              ← What I learned this week
│   ├── micrograd.py           ← Backprop engine from scratch
│   └── demo.ipynb             ← Experiments & visualizations
│
├── 📁 week-02-makemore-bigram/
│   ├── README.md
│   └── bigram.ipynb
│
├── 📁 week-03-makemore-mlp/
│   ├── README.md
│   └── mlp.ipynb
│
├── 📁 week-04-makemore-rnn/
│   ├── README.md
│   └── batchnorm.ipynb
│
├── 📁 week-05-makemore-wavenet/
│   ├── README.md
│   └── wavenet.ipynb
│
├── 📁 week-06-gpt-from-scratch/
│   ├── README.md
│   └── gpt.ipynb
│
├── 📁 week-07-gpt-from-scratch-2/
│   ├── README.md
│   └── tokenizer.ipynb
│
├── 📁 notes/
│   ├── README.md
│   ├── day-01.md              ← Daily study logs
│   └── ...
│
└── 📁 resources/
    └── links.md               ← All useful links & papers
```

---

## 🧭 How I Study Every Day

My daily routine is simple and consistent:

```
Step 1 — Watch (20–40 min)
         Watch a portion of the Karpathy video
         Pause every 10–15 mins to understand before continuing

Step 2 — Code (10–15 min)
         Type every line myself — no copy-pasting
         Run it, break it, fix it, understand it

Step 3 — Push & Note (5–10 min)
         Push code to the right week folder
         Write 5 lines in notes/ about what I learned today
```

> **Rule:** Push something every single day — even if it's just a notes file.
> The streak matters more than perfection.

---

## 📖 My Daily Note Format

Every day I push a file to `notes/day-XX.md` with this structure:

```markdown
# Day XX — [Topic]

## What I Studied
[Video name + timestamp range]

## Key Concepts I Understood
- Point 1
- Point 2

## Code I Wrote
[Brief description of what I coded]

## What Confused Me
[Honest questions I still have]

## Tomorrow's Plan
[What I'll study next]
```

---

## 🛠️ My Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.x | Primary language |
| PyTorch | Deep learning framework |
| NumPy | Numerical computing |
| Jupyter Notebook | Interactive coding (like Karpathy) |
| VS Code | Editor for scripts |
| Git & GitHub | Version control & daily commits |

---

## 📚 Core Resources

### Primary Curriculum
| Resource | Link |
|----------|------|
| 🎥 Karpathy — Zero to Hero (full playlist) | [YouTube](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) |
| 🎥 3Blue1Brown — Neural Networks | [YouTube](https://www.youtube.com/watch?v=aircAruvnKk) |
| 🎥 3Blue1Brown — Essence of Calculus | [YouTube](https://www.youtube.com/watch?v=WUvTyaaNkzM) |
| 🤗 Hugging Face LLM Course | [huggingface.co/learn](https://huggingface.co/learn/llm-course) |

### Papers to Read (in order)
| Paper | Why |
|-------|-----|
| [A Neural Probabilistic Language Model — Bengio 2003](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf) | Foundation of neural language models |
| [Attention Is All You Need — Vaswani 2017](https://arxiv.org/abs/1706.03762) | The transformer paper — read after GPT week |
| [GPT-2 Paper — Radford 2019](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) | How GPT actually works |

---

## 🏆 Capstone Project

**Goal:** A fully offline personal AI assistant

```
What it will do:
├── Answer questions without internet
├── Run entirely on local hardware
├── No API calls to OpenAI or any cloud service
├── Fine-tuned on my own data
└── Built using everything learned in this curriculum
```

This will be the centrepiece of my GitHub and the proof that I don't just use AI — I understand and build it.

---

## 📊 Stats

- 📅 **Started:** June 2026
- 🔥 **Current Streak:** 5 day
- ✅ **Weeks Completed:** 0 / 16
- 💻 **Total Commits:** updating daily

---

## 🔗 Connect With Me

I'm always open to connecting with people serious about AI research and deep learning.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ayush5606-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ayush5606)
[![GitHub](https://img.shields.io/badge/GitHub-ayush506x-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ayush506x)
[![Gmail](https://img.shields.io/badge/Gmail-ayush7984k@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ayush7984k@gmail.com)

---

<div align="center">

*"The best way to understand intelligence is to build it."*

⭐ Star this repo if you find it useful or inspiring!

</div>
