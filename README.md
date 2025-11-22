# 👋 Hi, I’m Deepjyoti Saha!

## 📌 Summary
Short 1–2 sentence summary of who you are and what you build.

- 🔭 Currently: Agents Ecosystem at Microsoft  
- 🌱 Skills: <topics you're learning>  
- 👯 Certifications: <collaboration types>  

## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/deepjyotisaha/) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:deepjyoti.saha@gmail.com) 

## 🚀 Featured Projects
Each project includes a brief, demo video with screenshot, and the repository link.

---

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

## 📫 Contact
- Email: <your-email@example.com>  
- LinkedIn: https://www.linkedin.com/in/<your-linkedin>  
- Twitter: https://twitter.com/<your-handle>

## 📊 GitHub Stats
![GitHub stats](https://github-readme-stats.vercel.app/api?username=<your-github-username>&show_icons=true&theme=default)

## 📌 Pinned Repos
Pin repositories in your GitHub profile; mirror the same selection here with short notes.

## 🤝 Want to collaborate?
Open an issue on any repo or message me on LinkedIn.

---
_Last updated: YYYY-MM-DD_