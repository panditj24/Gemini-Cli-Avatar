# 🤖 GemCli-Avatar: The All-in-One Gemini CLI Persona Manager

> **One Executable. Zero Configuration. Unlimited AI Personas.**

---

### ⚡ Quick Start Guide (TL;DR)
1. **Download:** Acquire the `GemCli-Avatar.exe`.
2. **Initialize:** Execute the file on any Windows 10/11 environment.
3. **Automated Setup:** Confirm with **`Y`** when prompted to install Node.js and Gemini CLI. 
4. **Deploy:** Select your desired persona and begin your session instantly.

---

**GemCli-Avatar** is a high-performance, professional wrapper for the Google Gemini CLI. It is engineered to transform a standard Windows environment into a sophisticated AI workstation in seconds. Designed for seamless portability, this tool automates environment orchestration, dependency management, and multi-agent lifecycle operations.

---

## 🌟 Core Value Proposition

Traditional CLI environments often require manual dependency management and complex command-line syntax to pivot between different AI roles. **GemCli-Avatar** simplifies this complexity into a single, intelligent interface.

*   **⚡ Rapid Deployment:** Transition from a clean OS to a functional AI environment in under 2 minutes.
*   **🧠 Intelligent Persona Orchestration:** Switch between specialized agents (such as a Researcher or a Vibe-Coder) with a single keystroke.
*   **🛠️ Environment Autopilot:** Silently manages Winget, Node.js, and System Path variables to ensure persistent stability.
*   **📂 Portable Architecture:** Ideal for professionals who require a mobile, consistent AI workspace across multiple machines.

---

## 🚀 1. Deployment on a Clean Environment

If you are operating on a fresh Windows installation, the tool is designed to autonomously configure its own runtime environment.

1.  **Placement:** Move `GemCli-Avatar.exe` to your preferred workspace (e.g., `C:\AI_Projects`).
2.  **Execution:** Launch the executable. A professional, color-coded terminal interface will initialize.
3.  **Dependency Discovery:**
    *   **Node.js Detection:** If the Node.js engine is missing, the application will offer to install it via Winget. Select **`Y`**.
    *   **Permission Sync:** A standard Windows UAC prompt will appear; select **Yes** to allow the system-level installation.
4.  **Gemini CLI Integration:** Once the engine is ready, the tool will offer to perform a global installation of the Gemini CLI via npm. Confirm with **`Y`**.
5.  **Finalization:** The persona menu will appear, indicating your environment is fully optimized and ready for use.

---

## 💾 2. Custom Path Configuration (Advanced Users)

For users who prefer to maintain their toolsets on external drives or non-standard directories (e.g., `D:\Tools`), **GemCli-Avatar** provides a streamlined integration process.

1.  **Path Specification:** When prompted about custom installations, select **`Y`**.
2.  **Target Directory:** Provide the full path to the folder containing your `gemini.cmd` executable.
3.  **Automated Environment Sync:** The tool will instantly add this directory to your current session and **permanently update your Windows User Environment Variables**, ensuring future launches are instantaneous.

---

## 🎭 3. Orchestrating AI Personas

A **Persona** is a sophisticated set of instructions that defines the behavior and expertise of the AI. These are stored as modular `.prompt.txt` files within your application directory.

### 🖥️ CLI-Based Persona Generation
For rapid prototyping, you can generate persona files directly from your terminal.

*   **PowerShell Strategy:**
    `Set-Content -Path "MyAgent.prompt.txt" -Value "You are a senior software architect..."`
*   **CMD Strategy:**
    `echo You are a senior software architect... > MyAgent.prompt.txt`

### ⚠️ Technical Constraints: Terminal Input Buffers
***While CLI generation is efficient for short instructions, Windows terminals (PowerShell/CMD) possess a hardware-level character limit (typically 2,048 to 8,192 characters). Exceeding this limit during a single command may cause data truncation, leading to a "broken" or incomplete AI persona.***

### 📏 Strategic Blueprinting: Optimal Content Architecture
To achieve the highest quality of reasoning and consistency, consider these length guidelines:
*   **Concise (Under 500 characters):** Suitable for basic utility tasks but may lack deep situational nuance.
*   **Professional Standard (2,000 – 6,000 characters):** ***The Industry Benchmark. Provides sufficient depth for complex reasoning, specialized domain knowledge, and a consistent professional tone without exceeding terminal or model context windows.***
*   **Exhaustive (Over 15,000 characters):** May lead to "instructional drift," where the AI may prioritize later instructions over earlier foundational rules.

### ⭐ THE GOLDEN RULE & BEST PRACTICE
***For professional-grade personas that are complex or multi-layered, the most reliable workflow is manual file creation. This bypasses terminal input limitations entirely:***

1.  ***INITIALIZE:** In your folder, create a new Text Document.***
2.  ***FORMAT:** Rename the file extension to `.prompt.txt` (e.g., `Architect.prompt.txt`).***
3.  ***CONTENT:** Open the file in a standard text editor (Notepad/VS Code), paste your full strategic instructions, and save.***
4.  ***DEPLOY:** Launch `GemCli-Avatar.exe` and select your persona from the menu.***

### 📂 Recommended Folder Structure
To maintain an organized and professional workspace, please adhere to the following directory architecture:

```text
C:\GeminiWorkspace\
├── GemCli-Avatar.exe           <-- The "Brain" (Primary Execution Engine)
├── GEMINI.md                   <-- (Optional) Global instructions for all agents
├── Vibe-Coding-Agent.prompt.txt <-- Specialized Vibe-Coding Agent Persona
└── PM-Assistant.prompt.txt      <-- Specialized Project Management Assistant Persona
```

---

## 💻 4. Operating System & Security Standards

***CRITICAL: To maintain a high-integrity, "Zero-Config" experience, your environment MUST adhere to these specifications:***

*   ***Operating System: Windows 10 (Build 1809+) or Windows 11.***
*   ***Shell Environment: Compatible with PowerShell 5.1, PowerShell 7, and Windows Terminal.***
*   ***Permissions: Administrative rights are required ONLY for the initial dependency installation. Daily operations run securely under standard user privileges.***

### 🛡️ Security & Trust (False Positives)

***IMPORTANT: Because GemCli-Avatar is a high-level script encapsulated in an .exe (via PS2EXE), certain heuristic scanners may flag it as "Unrecognized." This is a known false positive caused by the automation and encapsulation process.***

1.  ***Bypass Strategy: Click "More Info" and "Run Anyway" if prompted by Windows SmartScreen.***
2.  ***AV Exceptions: If your security suite blocks execution, add a folder exclusion for your workspace.***
3.  ***Integrity Verification: As an open-source project, the underlying GemCli-Avatar.ps1 logic is available for full security audits at any time.***

---

## 📜 Technical Philosophy
This project was realized through the **"Vibe-Coding"** methodology—prioritizing high-level strategic intent and rapid architectural iteration to deliver tools that are both functionally robust and aesthetically professional.

*Developed by: panditj*
