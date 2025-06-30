# OpenAgent---Lite
OpenAgent-Lite is a lightweight desktop automation tool powered by Large Language Models (LLMs). It allows users to automate tasks like web search, file management, email sending, and PDF downloads using natural language instructions.


## Features
- Voice Input Command – Speak your tasks naturally.
- LLM Agent Integration – Converts natural language into function calls.
- Web Automation using `selenium`
  - Search on Google / YouTube
  - Download PDFs / Images
- File Management
  - Rename files
  - Delete temporary files
- Send Emails with or without attachments
- Screenshot Capture
- Write to Text Files
- Scheduled Tasks Execution
- Web Scraping basic sites

  
## Tech Stack
 Component        -        Technology                  
---------------------------------------------------------------------
 Language         -         Python  
 
 LLM          -            [Ollama](https://ollama.com/) (`phi3` model) 
 
 Voice Recognition       -       `speech_recognition`   
 
 Web Automation        -       `selenium`, `webdriver_manager` 
 
 Email Sending         -       `smtplib`, Gmail SMTP  
 
 Scheduling          -       `schedule`, `time` 
 
 Screenshot Tool        -      `pyautogui`                 


## Tech Stack
1. Python
2. Ollama (local LLM backend)
3. Phi3:3.8b-mini-128k-instruct model


## Usage
1. Clone the repository.
2. Install required Python packages.
3. Ensure Ollama is installed and running with the Phi3 model pulled.
4. Run main.py to start.


## Sample Commands (LLM or Voice)

1. Open YouTube
2. Search Google for cat 
3. Take screenshot
4. Send an email with subject Report, body Please find attached, to example@gmail.com
5. Download PDFs from https://example.com
6. Rename files in C:/Users/YourName/Downloads
7. Delete temp files in C:/Temp

## Author
Twinkle Ghodki /
3rd year /
Btech CSE CORE

