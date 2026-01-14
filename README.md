# 🚀 GitHub Repo Specialist

A specialized terminal-based tool built in Python to discover the latest and most relevant repositories on GitHub. This tool helps you hunt for high-quality code in specialized categories.

---

## ✨ Features
* **Secure Authentication**: Uses GitHub Personal Access Tokens (PAT) for reliable API access.
* **Smart Category Filters**: Instant search for AI, Cybersecurity, Darkweb, Databases, and Networking.
* **Real-Time Data**: Fetches the most recently updated repositories to ensure you find active projects via the GitHub Search API.
* **Terminal-to-Browser**: Open any repository link in your default browser directly from the terminal.

---

## After Launching the tool it look like this 
   Now Paste your GitHub Token and it will be hidden and hit enter - Then select ripo catagory and hit enter , it will shows u the top 10 best ripos on that catagory - select the number and hit enter it will take    u directly to that ripo
<img width="796" height="227" alt="Screenshot 2026-01-14 143052" src="https://github.com/user-attachments/assets/054e9ba7-ce6c-4695-b9cb-773e5ba6e57e" />
<img width="683" height="246" alt="Screenshot 2026-01-14 143114" src="https://github.com/user-attachments/assets/ac34acc9-ff7c-4eb9-9d0e-b447cfb06d99" />
<img width="1361" height="649" alt="Screenshot 2026-01-14 143144" src="https://github.com/user-attachments/assets/ba2c680d-74e7-4772-81e6-a0dc621e3f05" />
<img width="1458" height="402" alt="Screenshot 2026-01-14 143208" src="https://github.com/user-attachments/assets/0892ab2c-cbed-4b15-9991-0cbb97761417" />



## 🛠️ Installation & Setup & launch

### Prepare the Environment & Launching
Run these commands in your terminal to set up the project:
```powershell
# Create project folder
mkdir repo-specialist && cd repo-specialist

# Set up virtual environment
python -m venv venv
.\venv\Scripts\Activate.ps1

# Install dependencies
pip install requests

# Launch the Tool
python hunt.py

