# Dark-web-Osint-

📥 Prerequisites

Operating System: Preferably Linux (Ubuntu/Debian), macOS, or Windows 10/11

Python: 3.9 or higher

RAM: Minimum 4GB (8GB recommended)

Disk Space: 2GB fre

🛠 Step-by-Step Installation
git clone https://github.com/mrrobot588/Dark-web-Osint-.git
cd Dark-web-Osint-


Create a virtual environment

python -m venv .venv  
source .venv/bin/activate  # Linux/macOS  
.\.venv\Scripts\activate  # Windows  

Install dependencies

pip install -r requirements.txt

Install Tor

Linux (Debian/Ubuntu)

sudo apt-get update && sudo apt-get install tor  

Configure Tor
Edit /etc/tor/torrc or the Tor configuration file:
ControlPort 9051
CookieAuthentication 1

Restart the service:
sudo systemctl restart tor


Install Geckodriver (for Selenium)

Linux/macOS:
wget https://github.com/mozilla/geckodriver/releases/download/v0.32.0/geckodriver-v0.32.0-linux64.tar.gz  
tar -xvzf geckodriver*  
chmod +x geckodriver  
sudo mv geckodriver /usr/local/bin/  

PATH

🚀 Basic Execution
python darkintellect.py http://example.onion  
