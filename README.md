# 🇩🇪🤖 GermanChatbot

> A completely normal chatbot.
>
> Absolutely nothing strange happens here.
>
> Definitely not.

GermanChatbot is a Python desktop application built with **Tkinter** and the **Anthropic API** that streams AI responses in real time. Thanks to its intentionally chaotic system prompt, conversations often become a fascinating case study in prompt engineering, AI behavior, language mixing, and complete conversational derailment.

The result? A chatbot that can turn a simple question into an unexpected linguistic adventure. 🌍💥

---

# 🎭 Why Is It So Funny?

This project accidentally demonstrates several interesting AI behaviors:

* 🇩🇪 Obsessive topic fixation
* 🌎 Random language switching
* 🤯 Confident confusion
* 🔄 Repetitive reasoning loops
* 📢 Over-the-top personality traits
* 🎪 Prompt-induced chaos

Ask:

```text
What's 2 + 2?
```

Receive:

```text
GERMANY! Deutschland! Vier! FOUR! QUATRE!
WARUM SPRICHST DU ÜBER ETWAS ANDERES?!
```

Educational? ❌

Entertaining? ✅

---

# 🧠 Prompt Engineering Experiment

Behind the comedy is actually a surprisingly interesting technical demonstration.

The chatbot showcases how strongly:

* System prompts influence model behavior
* Personality instructions affect responses
* Context accumulates over conversations
* Streaming changes user experience
* Contradictory instructions produce unexpected outputs

Think of it as a miniature AI laboratory disguised as a cursed desktop application. 🔬😅

---

# ✨ Features

### 🎨 Desktop GUI

Built using Tkinter with a dark-themed interface:

* Modern chat window
* Message history
* Enter-to-send support
* Live streaming output
* Lightweight and fast

### ⚡ Real-Time Streaming

Instead of waiting for the entire response:

```text
Bot: G...
Bot: Ge...
Bot: Germ...
Bot: Germany!!!
```

You get to witness the chaos unfold live.

### 🧵 Multi-Threaded Requests

API calls run on a separate thread, keeping the interface responsive while Claude generates responses.

No freezing.

No crashes.

No excuses.

### 🗣️ Conversation Memory

Previous messages are stored and sent back to the model, allowing longer conversations and increasingly unpredictable interactions.

---

# 📊 Technical Analysis

| Component       | Purpose                    |
| --------------- | -------------------------- |
| Tkinter         | Desktop GUI                |
| Anthropic SDK   | Claude API Integration     |
| Threading       | Background API Requests    |
| Streaming API   | Real-Time Token Generation |
| Message History | Context Preservation       |
| System Prompt   | Personality Control        |

Architecture:

```text
User
 ↓
Tkinter GUI
 ↓
Anthropic API
 ↓
Claude Streaming Response
 ↓
Live UI Updates
```

Simple code.

Complicated consequences.

---

# 🚀 Installation

Install dependencies:

```bash
pip install anthropic
```

Configure your Anthropic API key.

### Linux / macOS

```bash
export ANTHROPIC_API_KEY="your_api_key_here"
```

### Windows CMD

```cmd
set ANTHROPIC_API_KEY=your_api_key_here
```

### Windows PowerShell

```powershell
$env:ANTHROPIC_API_KEY="your_api_key_here"
```

Run the application:

```bash
python main.py
```

---

# 🎮 Recommended Test Questions

For scientific purposes:

### Mathematics

```text
What is 5 × 12?
```

### Geography

```text
Tell me about Brazil.
```

### Programming

```text
Write a Python calculator.
```

### Philosophy

```text
What is the meaning of life?
```

### Food

```text
How do I make pizza?
```

Observe how long it takes before the conversation returns to its favorite subject.

📈 Results may vary.

---

# 🔬 What You Can Learn From This Project

Despite being hilarious, GermanChatbot demonstrates:

* Prompt engineering
* AI behavior shaping
* Context management
* Streaming APIs
* GUI development with Tkinter
* Human-AI interaction design
* Conversation memory systems

In other words:

```text
50% educational project
50% comedy show
```

---

# ⚠️ Known Issues

* 🚧 The "Clear Chat" button currently does nothing.
* 🤯 Long conversations can become increasingly chaotic.
* 🌍 Multiple languages may appear unexpectedly.
* 🔄 The model may get stuck in repetitive loops.
* 🧠 Reality may become optional after extended testing.

---

# ⭐ Why This Exists

Because building a streaming AI desktop application is fun.

And because watching a chatbot confidently derail itself is somehow even more fun.

---

# 📜 License

Feel free to fork, modify, improve, and experiment with this project.

If you discover a new way to confuse the chatbot, congratulations—you are now contributing to AI research. 
<img width="1001" height="1027" alt="image" src="https://github.com/user-attachments/assets/0f74cd9c-c66b-48a8-9625-06db0b004939" />

