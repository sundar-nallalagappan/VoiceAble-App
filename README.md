# VoiceAble - Empowering people with vision-related challenges

🌟 **About VoiceAble**

VoiceAble is an AI-powered accessibility assistant designed to make digital interactions seamless for people with vision-related challenges. While our primary focus is to empower coders, students, and professionals with vision impairments, the tool is designed to support anyone with vision challenges who uses digital devices in school, college, or at work.

Unlike conventional screen readers, which struggle with embedded text, images, flowcharts, or complex documents, VoiceAble bridges that gap using advanced **multimodal AI**. It provides a frictionless, voice-first experience, ensuring accessibility and inclusivity for everyone.

---------------------------------------------------------------------------------------------------------------------------

🎯 **Our Vision & Mission**

**Vision:**
- To create an inclusive digital world where people with vision-related challenges can work, learn, and thrive without limitations.

**Mission:**
- To build the most intuitive, voice-enabled screen assistant that goes beyond traditional screen readers.
- To empower users by providing **multi-agent AI assistance** that understands intent, provides context-aware answers, and simplifies complex content.
- To continuously innovate accessibility solutions with human-first design.

---------------------------------------------------------------------------------------------------------------------------

🔑 **Key Features**
1) **Voice-Enabled Simplicity** – Only two hotkeys are needed to interact.
2) **Multi-Agent AI Backend** (hosted on AWS EC2): <br>
  a) **Supervisor Agent** → understands user intent. <br>
  b) **Screen Reader Agent** → reads out embedded text, images, diagrams. <br>
  c) **Summarizer Agent** → condenses lengthy content into clear summaries. <br>
  d) **Q&A Agent** → answers questions specific to the screen content <br>
  e) **Technical Debugger Agent** → helps developers troubleshoot. <br>
  f) **General Assistant Agent** → assists with everyday tasks. <br>
3) **Multi-Run Conversations** – Memory is captured for context across interactions.
4) **Reasoning Powered by Leading Models** – Google Gemini & OpenAI models drive the backend intelligence.
5) **Friendly & Low-Friction** – Designed with a vision-focused accessibility-first approach.

---------------------------------------------------------------------------------------------------------------------------

🚀 **Tech Stack**
- Frontend (Windows App): Python (Tkinter, Pygame, PyInstaller, PyStray, SpeechRecognition, Keyboard)
- Backend (AI Engine): FastAPI hosted on AWS EC2 (Docker based deployment)
- AI Framework - Langgraph to build the multi-agentic AI system
- AI Models: Google Gemini, OpenAI GPT Models
- Audio & TTS: Pyttsx3, Pygame Mixer, Custom TTS APIs
- System Integration: Hotkeys, System Tray, Screenshots Capture

---------------------------------------------------------------------------------------------------------------------------
🎬 Demo

**How it works**
Voiceable is a standalone Windows utility that runs quietly in the system tray. Simply press Ctrl + Alt + V, speak your query, and the app intelligently processes your voice command — whether it’s interpreting visuals, summarizing information, or performing quick tasks.

**Use Case 1 — Interpreting Visuals for Accessibility** <br>
Traditional screen readers struggle to describe charts or visual data. In this demo, Voiceable interprets a sales comparison plot, explaining the insights through natural speech for improved accessibility.

https://github.com/user-attachments/assets/1f3014b6-16ff-4f3b-9cf6-411894dc9902

<br>
**Use Case 2 — Interactive Q&A on Architecture Diagrams** <br>
In this demo, the user asks a question about the input sources shown in an architecture diagram. Voiceable understands the query, retrieves the relevant details, and responds through its Q&A agent, providing clear, contextual insights from the visual.

https://github.com/user-attachments/assets/42adde38-ab73-4941-bf4e-8bdc4f5cd52e



---------------------------------------------------------------------------------------------------------------------------

**📥 Download VoiceAble (Frontend Executable)**

👉 You can download the latest VoiceAble Windows Executable (.exe) from the **Releases Section** of this repository.
**Simply install and start using with just Ctrl + Alt + V (to ask a query) and Ctrl + Shift + X (to stop playback immediately).**

---------------------------------------------------------------------------------------------------------------------------

🔮 **Next Steps & Roadmap**

We are constantly innovating to make VoiceAble more powerful and user-friendly. Upcoming improvements include:
- **Mentor/Guide Mode** – An agent to teach and mentor users interactively.
- **Document Filling Assistant** – AI that probes users step-by-step to complete forms and documents.
- **Playback Controls** – Give users control over audio output (slow, fast, rewind, repeat).
- **Cross-Platform Support** – Extend beyond Windows to MacOS, Linux, and Mobile.

---------------------------------------------------------------------------------------------------------------------------

🤝 **Contribution & Community**

We welcome contributors, accessibility advocates, and researchers to join us in improving VoiceAble.
If you have ideas, feedback, or want to collaborate, feel free to open an issue or contribute via pull requests.

---------------------------------------------------------------------------------------------------------------------------

❤️ **Closing Note**

VoiceAble isn’t just an app — it’s a step toward inclusivity.
By combining voice-first interaction with multi-agent AI reasoning, we aim to make digital content truly accessible for everyone.

---------------------------------------------------------------------------------------------------------------------------
