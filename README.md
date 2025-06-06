# Vocational Training Task

## 🎯 Project Title:
**OpenAgent-Lite: A Goal-Driven Desktop Automation Assistant**

## 🧾 Objective:
Create an open-source agentic AI assistant in Python that can automate desktop tasks using natural language input. The assistant should understand goals, break them into subtasks, and perform actions autonomously—serving as an open alternative to traditional Robotic Process Automation (RPA) tools.

---

## Technologies & Tools:
- Language: Python 3.10+
- Automation Libraries: `pyautogui`, `selenium` or `playwright`, `schedule`
- LLM Tools: `ollama`, `transformers`, or lightweight local models
- Optional Enhancements: `speechrecognition`, `pyttsx3` for voice interaction

---

## Key Features to Implement:
### 1. User Interface
- Develop a **Command Line Interface (CLI)** for initial interaction.
- Optionally, build a **basic Web UI** using frameworks like:
  - [Flask](https://flask.palletsprojects.com/)
  - [Streamlit](https://streamlit.io/)
- Users should input tasks or goals in **plain English**, such as:
  > "Open YouTube in browser and search for AI tutorials."

---

### 2. Intelligent Task Breakdown
- Integrate with a **small local LLM** (via Ollama) to:
  - Interpret the user's goal.
  - Decompose it into logical, actionable subtasks.
  - Extract necessary parameters (URLs, file paths, time, etc.).
- Example:
  > Goal: “Email me a summary of files in the Documents folder every Monday at 9 AM”
  >
  > Subtasks:
  > - Get list of files in the Documents folder.
  > - Format the list as a summary.
  > - Compose and send the email.
  > - Schedule the task for Mondays at 9 AM.

---

### 3. Core Desktop Automation
Use automation libraries to execute tasks:

#### Features:
- **Application Control**: Open and close desktop apps.
- **Mouse & Keyboard Simulation**: Click buttons, type text using `pyautogui`.
- **File & Folder Operations**:
  - Rename, move, delete, list directory contents using Python's `os` and `shutil`.
- **Web Automation**:
  - Use `selenium` or `playwright` to:
    - Navigate to websites.
    - Fill out forms.
    - Download files.
    - Scrape content if required.

---

### 4. Scheduled Task Support
Enable the agent to perform tasks at specific times or on a recurring basis:
- Use scheduling libraries such as `schedule` or `APScheduler`.
- Example scheduled tasks:
  - “Clean up Downloads folder every Friday.”
  - “Send system status report daily at 8 PM.”

---

### 5. Execution Logging
- **Execution Logs**:
  - Log timestamp, action taken, success/failure status, and any error messages.
  - Store logs in a text or JSON file for later review.

---

### 6. Documentation
- Prepare clear, complete project documentation:
  -  Create a separate git branch with your name to update code.
  - `README.md` with setup instructions and usage examples.
  - Inline comments in source code for clarity.
  - Folder structure documentation (e.g., `/src`, `/logs`, `/docs`).

---

## Example Use Cases:
- “Open browser and download all PDF files from a website.”
- “Rename all `.jpg` files in a folder to `holiday_1.jpg`, `holiday_2.jpg`, etc.”
- “Send an email with today’s attendance file every day at 6 PM.”

---

##  Goals Break-up :
| Goals | Task |
|------|------|
| 1    | Set up project environment and UI |
| 2    | Integrate LLM for goal-to-subtask parsing |
| 3    | Implement basic desktop automation features |
| 4    | Add support for scheduled tasks |
| 5    | Improve task execution and logging |
| 6    | Final testing, documentation, and GitHub push |

---

## Deliverables:
- Working Python code with sample tasks.
- `README.md` with usage instructions.
- Documented code and comments.

---

## Evaluation Criteria:
- Completeness and accuracy of task execution.
- Code quality and documentation.
- Creative use of automation features.
- Overall usability and modular design.

---
