🚀 GitHub Repo Specialist
A specialized terminal-based tool built in Python to discover the latest and most relevant repositories on GitHub. This tool helps you hunt for high-quality code in specialized categories.

✨ Features
Secure Authentication: Uses GitHub Personal Access Tokens (PAT) for reliable API access

Smart Category Filters: Instant search for AI, Cybersecurity, Darkweb, Databases, and Networking

Real-Time Data: Fetches the most recently updated repositories to ensure you find active projects via the GitHub Search API

Terminal-to-Browser: Open any repository link in your default browser directly from the terminal

🛠️ Installation & Setup
1. Prepare the Environment
Run these commands in your terminal to set up the project:

powershell
# Create project folder
mkdir repo-specialist && cd repo-specialist

# Set up virtual environment
python -m venv venv
.\venv\Scripts\Activate.ps1

# Install dependencies
pip install requests
2. Authentication
When you launch the script, it will provide a link to generate a token. Paste your token when prompted (it will remain hidden for security).

🚀 How to Use
Launch the Tool
Run the main script:

powershell
python hunt.py
Choose a Category
Select a pre-defined category by typing its number, or press 'S' to perform a custom keyword search.

Explore Results
View the top 10 matches including their star count, description, and link.

Open & Learn
Type the number (1-10) of the repository you want to visit, and it will open instantly in your web browser.

📂 Project Structure
hunt.py: The core Python engine

.gitignore: Prevents the venv folder from being uploaded to GitHub

README.md: Project documentation

🛡️ Requirements
Python 3.x

GitHub Personal Access Token (Classic) - Generate one here

Internet Connection

Created by Tarunjit
