# 👋 Hi, I’m Deepjyoti Saha!

## 📌 Summary

- 🔭 Currently: Agents Ecosystem with [M365 Copilot](https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/ecosystem) & [Copilot Studio](https://learn.microsoft.com/en-us/microsoft-copilot-studio/fundamentals-what-is-copilot-studio) at Microsoft  
## 🌱 Skills
![Product Management](https://img.shields.io/badge/Product%20Management-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white)
![Ecosystems](https://img.shields.io/badge/Ecosystems-2ECC71?style=for-the-badge&logo=treehouse&logoColor=white)
![Growth & Adoption](https://img.shields.io/badge/Growth%20%26%20Adoption-F39C12?style=for-the-badge&logo=chartdotjs&logoColor=white)
![Enterprise Workflows](https://img.shields.io/badge/Enterprise%20Workflows-8E44AD?style=for-the-badge&logo=microsoft&logoColor=white)
![Agentic AI](https://img.shields.io/badge/Agentic%20AI-FF6F61?style=for-the-badge&logo=robotframework&logoColor=white)
![LLMs & Gen AI](https://img.shields.io/badge/LLMs%20%26%20Gen%20AI-00BFFF?style=for-the-badge&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF1493?style=for-the-badge&logo=graphql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Microsoft Copilot Studio](https://img.shields.io/badge/Microsoft%20Copilot%20Studio-5C2D91?style=for-the-badge&logo=microsoft&logoColor=white)

- 👯 Certifications: [EAG & EVA @ The School of AI](https://theschoolof.ai/#programs), Retention, Engagement & Growth @ Reforge

## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/deepjyotisaha/) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:deepjyoti.saha@gmail.com) 

## 🚀 Featured Projects
Each project includes a brief, demo video with screenshot, and the repository link.

---

### Agentic AI
---

### The Undetectable AI Overlay for Interviews & Meetings — Capstone (ShadowBot)
- Brief: Real‑time, transparent overlay that offers suggestions, smart notes, and instant help during interviews and meetings without breaking conversational flow. Built as the EAG‑V1 capstone project for The School of AI.
- Capstone: EAG‑V1 — The School of AI
- Team:
  - Saish Shetty
  - Himank Jain
  - Soma Korada
  - Deepjyoti Saha

🔗 Links  
- Demo: https://youtu.be/J-dY5hfeac4  
- Website: https://shettysaish20.github.io/ShadowBot/  
- Repository: https://github.com/deepjyotisaha/eag20/tree/master/ShadowBot-main

⚙️ Supported Platforms
- Windows, macOS

📚 Table of Contents (project doc)
- Project Overview  
- Application Features  
- Functionalities  
- Tech Stack  
- Installation & Setup  
- Runtime Flow (High Level)  
- Architecture & Directory Guide  
- Agents & Profiles  
- Prompts & Prompt Engineering  
- Extending the System  
- Roadmap (Potential Enhancements)  
- Contributing

🚀 Key Highlights
- Graph‑first execution engine (NetworkX) for explicit reasoning flow visualization & introspection.  
- Multi‑Agent role specialization (Planner / Retriever / Thinker / Coder / Distiller / Clarifier / QA / Scheduler / Formatter / Decision / Tooling) coordinated via AgentLoop4.  
- Multi‑MCP (Model Context Protocol) servers for tools, retrieval, and browser search.  
- Dynamic model configuration and runtime Gemini API key injection (no static secrets at cold start).  
- Unified context management with persistent session graph and extensible profiles to tune persona, tone, and domain behavior.  
- Designed for research and production‑grade extensibility: add tools, plug new LLM providers, extend agent roles or the execution graph.

📦 Tech Stack (examples)
- Orchestration: Python, NetworkX, AgentLoop4  
- Frontend / Overlay: Electron / native overlay + JS  
- Models / AI: Gemini API integration, local/remote LLM adapters  
- Integrations: MCP servers, OAuth, telemetry

---

### EAG18 — Agentic Query Assistant System 🧠
- Brief: A multi-agent AI system that processes complex user queries via a NetworkX-based execution graph and a coordinated pipeline of specialized agents, external tools, and MCP servers.

🏗️ System Architecture
- Core Components:
  - NetworkX Graph Engine — manages execution flow and dependencies  
  - Multi-Agent Pipeline — ~10 specialized agents coordinating tasks (planning, retrieval, codegen, analysis)  
  - MCP Servers — external tool integrations (e.g., Gmail, RAG, compute)  
  - Rich CLI — interactive command-line experience  
  - Web API — REST endpoints for integration

🔁 Execution Flow
User Query → File Upload → File Profiling → Planning → Multi-Agent Execution → Result Analysis → Output

🎥 Demo Video: [Watch demo](https://www.youtube.com/watch?v=A0kznksbOiU)  
![Demo screenshot](https://img.youtube.com/vi/A0kznksbOiU/0.jpg)

📝 Sample Prompts
- Research & Analysis:
  - "You are a stock researcher, prepare a very detailed and comprehensive report on Asian Paints."
  - "Conduct a basic market research on electric vehicle trends and create a detailed analysis report."
- Coding:
  - "Create a modern Tic Tac Toe game with HTML, CSS, and JavaScript."
- File Analysis:
  - "Analyze the sales data provided in the file and prepare a report."
- (Experiment with your own complex queries combining files, web research, and code generation.)

🔗 Repository: https://github.com/deepjyotisaha/eag18/tree/master/code

### Browser Use Agent — Automate complex browser workflows
- Brief: A browser automation agent that performs multi-step web tasks via a Chrome extension/front-end and backend orchestration. Useful for data extraction, automated form-filling, navigation, and scripted browsing workflows.
- Features:
  - Automates navigation, clicks, form entry and data scraping
  - Handles multi-step workflows and conditional logic
  - Captures screenshots and session traces for debugging
  - Integrates with backend services for RAG, analysis and reporting
  - Provides real-time progress updates to the user
- Demo Video: [Watch demo](https://www.youtube.com/watch?v=1jD2-7kZbGs)  
  ![Demo screenshot](https://img.youtube.com/vi/1jD2-7kZbGs/0.jpg)
- Repository: https://github.com/deepjyotisaha/eag15/tree/master/code

---

### 🤖 Computer Use Agent — Automates tasks on your desktop via natural language
- Brief: A sophisticated AI agent that interacts with desktop applications using computer vision and natural language commands to perform multi-step tasks reliably.
- Sample Prompt:
  > Open notepad, type "Hello World", open a new tab and type "I am Computer use agent!" and then exit
- Capabilities demonstrated:
  - Launch applications (e.g., Notepad)
  - Type text across multiple tabs/windows
  - Navigate application menus (File → New, Exit)
  - Click menu items and interact with UI controls
  - Orchestrate multi-step workflows and exit cleanly
- Features:
  - Computer vision + NLP for UI understanding
  - Action planning and deterministic UI interactions
  - Error handling and retries for robust automation
  - Extensible to new apps and workflows
- Demo Video: [Watch demo](https://www.youtube.com/watch?v=aYlVvutoub4)  
  ![Demo screenshot](https://img.youtube.com/vi/aYlVvutoub4/0.jpg)
- Repository: https://github.com/deepjyotisaha/eag14a/tree/master/computer_agent

---

### Multi‑channel Agent — Telegram + Gmail via MCP servers
- Brief: A multi-channel agent that interacts with users over Telegram (via an MCP SSE server) and delivers final reports to users via a Gmail MCP server. Designed for conversational workflows and automated report delivery.
- Features:
  - Two-way interaction over Telegram (real-time SSE)
  - MCP SSE server implementation for Telegram integration
  - Gmail MCP server to email final reports to users
  - Orchestrates multi-step agent workflows and delivers summaries/reports
  - Suitable for alerts, task execution, and automated summaries
- Demo Video: [Watch demo](https://www.youtube.com/watch?v=AViGOt94KQ4)  
  ![Demo screenshot](https://img.youtube.com/vi/AViGOt94KQ4/0.jpg)
- Repository: https://github.com/deepjyotisaha/eag8/tree/master/agent_e8

---

### 4. **Stock Research Assistant** — AI-powered stock research assistant
- Brief: An AI-powered assistant that combines a Chrome extension side panel with a backend for real-time stock analysis and insights, helping investors and analysts make informed decisions.
- Sample Queries:
  - "Show me key financial figures for Rainbow Hospitals"
  - "What are the growth drivers for healthcare industry"
  - "Summarize all the financial information you have obtained into a well formatted email ... send it to name@example.com"
  - "Compare the financial performance of Narayana Health and Rainbow Hospitals ... conclude who is a better investment bet"
- Features:
  - Chrome Extension Interface: convenient side panel for quick access
  - Interactive Queries: NLP-powered natural-language stock questions
  - Live Updates: real-time progress and status shown to the end user
  - Document Search: RAG (Retrieval-Augmented Generation) based retrieval for relevant stock information
  - Multi-Server Architecture: separate servers for RAG, math/analysis, and Gmail integration
  - Automated Workflows: generate, format, and optionally send result emails when analysis is final
- Demo Video: [Watch demo](https://www.youtube.com/watch?v=ZpvHxjgI3KE)  
  ![Demo screenshot](https://img.youtube.com/vi/ZpvHxjgI3KE/0.jpg)
- Repository: https://github.com/deepjyotisaha/eag7/tree/master/stock_research

---

### 3. **Gmail Newsletter Digest Extension** — Automated newsletter summarization & digest
- Brief: A Chrome extension with a Python backend that scans your Gmail inbox, identifies newsletters, summarizes their content using Gemini AI, and compiles a tidy markdown digest for easy reading and archiving.
- Features:
  - 🔍 Automatically identifies newsletters in your Gmail inbox
  - 📝 Generates concise summaries of newsletter content
  - 📋 Creates a well-formatted markdown digest
  - 🔒 Secure Gmail API integration (OAuth2)
  - 🤖 Powered by Google's Gemini AI for intelligent processing
  - 📊 Configurable number of emails to process
  - 🔄 Real-time processing and updates
- Demo Video: [Watch demo](https://www.youtube.com/watch?v=yuTBrcswA1M)  
  ![Demo screenshot](https://img.youtube.com/vi/yuTBrcswA1M/0.jpg)
- Repository: https://github.com/deepjyotisaha/eag3

---

### 2. **Email Triage Assistant** — Intelligent Gmail categorization using Gemini AI
- Brief: A Chrome extension that helps you manage your inbox by automatically categorizing unread emails using Gemini AI. It reduces inbox clutter by classifying messages into actionable buckets so you can focus on what matters.
- Features:
  - Automatically analyzes unread emails
  - Categorizes emails into:
    - Delete: Promotional and non-essential emails
    - Read: Notifications and updates
    - Important: Personal and urgent emails
  - Uses Gemini AI for intelligent email categorization
  - Customizable rules for email categorization
  - OAuth2 authentication with Gmail
- Demo Video: [Watch demo](https://www.youtube.com/watch?v=m1kAjD7gnrI)  
  ![Demo screenshot](https://img.youtube.com/vi/m1kAjD7gnrI/0.jpg)
- Repository: https://github.com/deepjyotisaha/eag2

---

### **Gmail Extension for Bulk Actions** — Manage unread Gmail efficiently
- Brief: A browser extension that helps you manage unread Gmail emails quickly and safely. Core features include viewing all unread emails, marking selected emails as important, marking selected emails as read, and deleting remaining unread emails.
- Demo Video: [Watch demo](https://www.youtube.com/watch?v=Qp4ok4VrMGU)  
  ![Demo screenshot](https://img.youtube.com/vi/Qp4ok4VrMGU/0.jpg)
- Repository: https://github.com/deepjyotisaha/eag1

---

## Computer Vision
---

### EVA4-15 — Mask & Depthmap Prediction 🖼️
- Submitted by: Deepjyoti Saha  
- Contact / Canvas ID: deepjyoti.saha@gmail.com

#### Overview
A deep neural network that predicts output images (foreground mask and depthmap) from two inputs: (1) an image with a foreground object over a background scene, and (2) the background-only image. The model learns to generate the object mask and a corresponding depthmap.

#### Usage
Download the final model file from the project assets (Predict Mask and Depthmap Model Download Link)

Python API:
```python
from utils import predict

# arguments:
# modelpath - absolute path to model file
# filepath  - absolute path to folder with test images
# bg        - filename for background image
# image     - filename for image with foreground

predict.predict_images(modelpath, filepath, bg, image)
```

Sample usage (example):
```python
from utils import predict

modelpath = "/abs/path/to/model.pth"
test_folder = "/abs/path/to/test_images"
bg_file = "background_01.jpg"
img_file = "scene_with_obj_01.jpg"

predict.predict_images(modelpath, test_folder, bg_file, img_file)
```

#### Results (sample)
| Epochs | Mask Dice Score | Depthmap Dice Score |
|--------:|----------------:|--------------------:|
| 28     | 0.91            | 0.43                |

The following predicted images were generated from unseen test inputs: Background (Input) → Image (Input) → Predicted Mask → Predicted Depthmap.

#### Solution & Approach
- Problem: Predict foreground object mask and per-pixel depthmap given (image+background) and (background-only) pairs.
- Model: ResNet-inspired encoder with dual heads (one head for mask, one for depthmap).
- Losses: Separate, task-appropriate loss functions for mask and depth outputs (e.g., Dice / BCE for mask, L1/L2 or custom loss for depth).
- Training: Joint training of shared encoder with two heads; augmentation and regularization applied to improve generalization.

#### Repository
https://github.com/deepjyotisaha85/eva4/tree/master/session15

### YoloV3 — Custom Object Detection (Jet Fighters, Dusty, Battle Tanks)
- Brief: Trained YoloV3 models on custom datasets to detect aircraft (fighter jets, Dusty), aircraft carriers, and battle tanks. Includes annotated results and demo videos showing detection on real videos.
- Assets:
  - Annotated image (OpenCV YoloV3): https://github.com/deepjyotisaha85/eva4/blob/master/session13/opencvyolov3/table_annotated.png
- Models / Training:
  - Trained one YoloV3 model to detect Jet Fighters, Dusty, and Aircraft Carrier (single dataset).
  - Trained a separate YoloV3 model for Battle Tank detection.
- Demo Videos:
  - Dusty & Fighter Jet Detection (Video 1): https://www.youtube.com/watch?v=eJLIq9bR88Q  
  - Dusty & Fighter Jet Detection (Video 2): https://www.youtube.com/watch?v=LbknBvu4I2g  
  - Battle Tank Detection (Republic Day Parade): https://www.youtube.com/watch?v=NiwNiGO4ud8
- Repository: https://github.com/deepjyotisaha85/eva4



---


---
Last updated: 22nd-Nov-2025