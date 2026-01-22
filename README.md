# Q-Learning on FrozenLake-v1 (4x4, No Slippery)

This project implements a Q-Learning agent trained on the FrozenLake-v1 environment as part of the Hugging Face Deep Reinforcement Learning course.

---

## 🎥 Agent in Action

![frozenlake_demo](https://github.com/user-attachments/assets/8e6d3c34-f40c-4d95-8254-71cfb5259728)


---

## 📌 Environment

- FrozenLake-v1
- 4x4 grid
- No slippery (deterministic)

---

## ⚙️ Algorithm

Tabular Q-Learning with ε-greedy exploration.

Q-update rule:

Q(s,a) = Q(s,a) + α (r + γ max Q(s',a') - Q(s,a))

---

## 📊 Results

The trained agent consistently reaches the goal in the deterministic FrozenLake environment.

---

## 🤗 Hugging Face Model

https://huggingface.co/BhushanGatty/q-FrozenLake-v1-4x4-noSlippery

---

## 👨‍💻 Author

Bhushan Gatty  
Robotics Engineering Student  
Deep Reinforcement Learning Enthusiast  
