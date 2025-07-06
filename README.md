# 1. Update Termux packages to latest versions
pkg update && pkg upgrade -y

# 2. Install Git (to download your bot), Python (to run your bot), and Figlet (for cool fonts)
pkg install git python figlet -y

# 3. Download your bot’s code from GitHub
git clone https://your-bot-link.git

# 4. Go to your bot’s folder
cd your-bot-folder

# 5. Install required Python libraries for your bot
pip install -r requirements.txt

# 6. Show a stylish startup message
figlet -f slant "Starting ★ Bot"

# 7. Run your bot with a special character argument
python bot.py ★
