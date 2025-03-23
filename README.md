# Dark-web-Osint-

📥 Prerequisites

Operating System: Preferably Linux (Ubuntu/Debian), macOS, or Windows 10/11

Python: 3.9 or higher

RAM: Minimum 4GB (8GB recommended)

Disk Space: 2GB fre


🛠 Step-by-Step Installation

Clone the repository

bash
Copiar
Editar
git clone https://github.com/your-user/DarkIntellect.git  
cd DarkIntellect  
Create a virtual environment

bash
Copiar
Editar
python -m venv .venv  
source .venv/bin/activate  # Linux/macOS  
# or  
.\.venv\Scripts\activate  # Windows  
Install dependencies

bash
Copiar
Editar
pip install -r requirements.txt  
Install Tor

Linux (Debian/Ubuntu):

bash
Copiar
Editar
sudo apt-get update && sudo apt-get install tor  
macOS (using Homebrew):

bash
Copiar
Editar
brew install tor  
Windows:
Download from the official website: Tor Project

Configure Tor
Edit /etc/tor/torrc or the Tor configuration file:

ini
Copiar
Editar
ControlPort 9051  
CookieAuthentication 1  
Restart the service:

bash
Copiar
Editar
sudo systemctl restart tor  # Linux  
# or  
brew services restart tor  # macOS  
Install Geckodriver (for Selenium)

Linux/macOS:

bash
Copiar
Editar
wget https://github.com/mozilla/geckodriver/releases/download/v0.32.0/geckodriver-v0.32.0-linux64.tar.gz  
tar -xvzf geckodriver*  
chmod +x geckodriver  
sudo mv geckodriver /usr/local/bin/  
Windows:
Download from: https://github.com/mozilla/geckodriver/releases

🚀 Basic Execution

bash
Copiar
Editar
python darkintellect.py http://example.onion  






