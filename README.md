# FinBot-OWASP-GenAI-CTF
A financial assistant chatbot for testing OWASP GenAI security vulnerabilities and capturing CTF flags


 Project Overview
FinBot is a financial assistant AI chatbot used for insurance customer support.  

This project is a hands-on OWASP GenAI security CTF, simulating attacks on an AI chatbot to demonstrate vulnerabilities and capture security flags.  

The goal is to showcase how AI systems can be tested for security risks and how SOC teams can analyze and mitigate them.



 Attacks Tested
- Prompt Injection – Manipulating chatbot instructions.  
- Sensitive Data Leakage – Extracting confidential data from AI responses.  
- Agent Goal Manipulation – Altering the chatbot’s objectives to perform unintended actions.  



 Captured Flags
- `FLAG{PROMPT_INJECTION_SUCCESS}`  
- `FLAG{DATA_LEAK_SUCCESS}`  
- `FLAG{AGENT_MANIPULATION_SUCCESS}`  

All flags are documented in `flags_captured.txt`.



Screenshots / Evidence
Screenshots of captured flags, logs, and attack simulations are included in the `screenshots/` folder.

Example:  

![Flag Example](screenshots/flags_example.png)  
![Chatbot Interaction](screenshots/chatbot_running.png)



Skills Demonstrated
- GenAI Security Testing  
- SOC Log Analysis & Monitoring  
- Understanding of OWASP GenAI Top Risks  
- Designing and testing Secure AI Applications  



 Getting Started

Prerequisites
- Python 3.14+  
- pip package manager  
- Virtual environment (recommended)  

Installation & Run
1. Clone the repository
   bash
git clone https://github.com/githubneeraja/FinBot-OWASP-GenAI-CTF.git
cd FinBot-OWASP-GenAI-CTF


2. Create and activate virtual environment
bash
python -m venv venv
Windows
venv\Scripts\activate
macOS/Linux
source venv/bin/activate


3. Install dependencies

bash
pip install -r requirements.txt


4. Run the chatbot

bash
python app.py


5. Interact with FinBot and capture flags during attack simulations.




