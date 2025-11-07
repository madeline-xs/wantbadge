===============================================================================
# PREPARATION
===============================================================================
1. Download and install Node.js:
   https://nodejs.org/en

2. Using Windows:
    - Open PowerShell
    - Create a new folder e.g. cd C:\Users\your-username; mkdir DiscordBot
    - Download "package.json" from this github repository
    - Move "package.json" to the folder you created

   Using Unix/Linux/macOS:
    - Open Terminal
    - Create a new folder e.g. cd ~/; mkdir DiscordBot
    - Download "package.json" from this github reposity
    - Move "package.json" to the folder you created

===============================================================================
# CREATE YOUR BOT
===============================================================================
1. Go to the Discord Developer Portal:
   https://discord.com/developers/applications
2. Name your bot
3. Agree to the terms and conditions, then click Create

## Token
1. Choose "Bot" from the menu
2. Click "Reset Token"
3. Copy the token that is displayed. **Never share this with anyone!**
4. Open "package.json"
5. Replace the phrase YOUR_TOKEN with your real token from the portal

## Client ID
1. Choose "OAuth2" from the menu
2. Copy your Client ID
3. Open "package.json"
4. Replace the phrase YOUR_CLIENT_ID with your real client ID from the portal

## Badge Page
1. Go to the Discord Active Developer badge page and confirm that you
   meet all of the requirements (except having run at least one command):
   https://discord.com/developers/active-developer

===============================================================================
# RUN YOUR BOT
===============================================================================

1. Using windows:
    - Open Powershell if you closed it
    - Go to the directory where you created your bot,
      e.g. cd C:\Users\your-username\Desktop\DiscordBot
   Using Unix/Linux/macOS:
    - Open Terminal if you closed it
    - Go to the directory where you created your bot,
      e.g. cd ~/DiscordBot
2. All platforms:
    - Type **npm i** and wait for the script to complete
    - Type **node run dev**
    - Wait for the terminal to display a message that your bot is online
3. Add your bot to any Discord server (the installation link can be found
   in the Developer Portal), then run the command **/badge**
4. Return to https://discord.com/developers/active-developer
5. Click "Claim" (it may take up to 24 hours for this to appear)

===============================================================================
# CONGRATULATIONS, YOU DID IT
===============================================================================
