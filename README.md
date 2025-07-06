# 1. Update Termux packages and upgrade all
pkg update && pkg upgrade -y

# 2. Fix permissions for Termux storage access (if needed)
termux-setup-storage

# 3. Download your bot’s code from GitHub
git clone https://github.com/Leshzn/Bot-test

# 4. Go to your bot’s folder
cd /MAOCHAN_MD_V1.4 
or 

cd /secar/MAOCHAN_MD_V1.4

# 5. Start Run Bot
npm start
