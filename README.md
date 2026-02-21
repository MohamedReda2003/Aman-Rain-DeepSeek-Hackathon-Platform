<div align="center">

# 🌧️ Aman Rain — DeepSeek Hackathon Platform

### AI-Powered Chatbot Assistant for Smart Urban Rainwater Management

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B?logo=streamlit&logoColor=white)](https://streamlit.io/)
[![DeepSeek](https://img.shields.io/badge/DeepSeek-API-6C63FF?logo=openai&logoColor=white)](https://api.deepseek.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> 🏆 **3rd Place** — Smart Cities Track · AI2SD x WayTech Hackathon 2025  
> Held under the High Patronage of **His Majesty King Mohammed VI** · Tangier, Morocco

</div>

---

## 📖 Overview

**Aman Rain** is an AI-driven solution designed to revolutionize **rainwater management in urban areas**. This repository contains the **interactive chatbot platform** built with Streamlit and powered by the DeepSeek API — developed during the **AI2SD 2025 Hackathon** as part of the Smart Cities track.

The platform serves as an intelligent assistant that answers questions, provides insights, and interacts with users around the Aman Rain solution: merging **IoT sensors**, **predictive analytics**, and **sustainable design** to turn floods into resources for greener, safer cities.

---

## 🌍 Why Aman Rain?

Morocco faces severe water scarcity, and urban flooding only makes the problem worse. Aman Rain addresses this by transforming wasted rainwater into a managed resource:

- ✅ **Captures** rooftop rainwater efficiently
- ✅ **Filters** it to safe, reusable quality
- ✅ **Distributes** it intelligently to green spaces and households

The AI chatbot component makes this solution accessible — providing an interactive interface for citizens, city planners, and stakeholders to engage with the system.

---

## ✨ Features

- 🤖 **DeepSeek-Powered Chatbot** — Conversational AI assistant via the DeepSeek API
- 🖥️ **Streamlit Interface** — Clean, modern, and browser-based web UI
- 💬 **Multi-turn Conversations** — Maintains context across the session
- ⚡ **Fast Responses** — Streamed output for a smooth user experience
- 🌱 **Smart Cities Focus** — Tailored context around urban sustainability and water management

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Frontend / UI** | [Streamlit](https://streamlit.io/) |
| **AI Model** | [DeepSeek](https://api.deepseek.com/) via REST API |
| **Language** | Python 3.10+ |
| **Dev Environment** | GitHub Codespaces (`.devcontainer`) |

---

## 📁 Project Structure

```
st-deepseek-int/
│
├── .devcontainer/             # GitHub Codespaces dev container config
├── st_hack_platform.py        # Main Streamlit application
├── requirements.txt           # Python dependencies
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- Python 3.10 or higher
- A **DeepSeek API key** — get one at [platform.deepseek.com](https://platform.deepseek.com/)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/MohamedReda2003/st-deepseek-int.git
   cd st-deepseek-int
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set your DeepSeek API key**

   Create a `.streamlit/secrets.toml` file:
   ```toml
   DEEPSEEK_API_KEY = "your_api_key_here"
   ```
   Or export it as an environment variable:
   ```bash
   export DEEPSEEK_API_KEY=your_api_key_here
   ```

4. **Run the app**
   ```bash
   streamlit run st_hack_platform.py
   ```

5. Open your browser at `http://localhost:8501` 🎉

### ☁️ Run in GitHub Codespaces

This repo includes a `.devcontainer` configuration. Simply click **"Open in Codespaces"** on GitHub and the environment will be set up automatically — no local setup needed.

---

## 🎮 Usage

Once the app is running, you'll be greeted with the Aman Rain chatbot interface. You can:

- Ask questions about **urban rainwater management**
- Explore the **Aman Rain solution** and its components
- Get **AI-generated insights** on smart city sustainability
- Have an open conversation powered by DeepSeek's language model

---

## 👥 Team — Aman Rain

| Name | Role |
|---|---|
| **Mohamed Reda Zhar** | Team Member |
| **Anas Boulben** | Team Member |
| **SARHANE Douae** | Team Member |
| **Nour Sarhden** | Team Member |

---

## 🏆 Hackathon Achievement

> 🥉 **3rd Place** — Smart Cities Track  
> **AI2SD x WayTech Hackathon 2025**  
> Under the High Patronage of His Majesty King Mohammed VI · Tangier, Morocco

Special thanks to the organizers, jury members, and all participants for creating an incredible platform to innovate alongside Morocco's brightest minds.

---

## 🤝 Contributing

Contributions and suggestions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create your branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push and open a Pull Request

---

<div align="center">

Made with 💙 by Team **Aman Rain** · AI2SD Hackathon 2025 · Morocco

</div>
