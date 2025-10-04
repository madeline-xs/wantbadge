================================ PRE-REQUISITES ================================
1. Download Node.js from the official website: https://nodejs.org/en
2. Install Node.js
3. If you are using a Windows computer, open PowerShell. If you are using a Mac
   or running a Unix-based OS, open Terminal.
4. In your PowerShell/Terminal window, navigate to the folder where you'd like
   to save your Bot.
   Windows example:
   cd C:\Users\your-username\Documents
   mkdir DiscordBot
   cd DiscordBot

   Mac/Unix example:
   cd ~/
   mkdir DiscordBot
   cd DiscordBot

5. Type and enter the command "npm init -y". A file called "package.json" will
   appear in the folder.
6. Type and enter the command "npm install discord.js"
7. Open your package.json file and make the following changes:
   Under "scripts", add "start": "node index.js --no-warnings --no-deprecation"
   Add "type": "commonjs" before the final "}"
   Your package.json file should now look like the one in this github
   repository.

=============================== CREATE YOUR BOT ================================
1. Go to https://discord.com/developers/applications
2. Click "New Application"
3. Name your application, read the Terms of Service, and click Create
4. Select your application
5. Choose "Bot" from the menu options
6. Click "Reset Token"
7. Copy and paste the new token into your config.json file.
   NEVER SHARE THIS TOKEN WITH ANYONE.
8. Click "OAuth2" from the menu options
9. Copy your Client ID and paste it into your config.json file

================================= FINISHING UP =================================
1. Open PowerShell/Terminal again and return to the folder where your bot is
   located.
2. Type "npm start".
3. If you completed all steps correctly, you should see a message that says
   "Connected to Discord. Logged in as [your bot's username and tag]."
4. Add your bot to any Discord server (the installation link can be found in the
   Developer Portal), then run the command /badge
5. Click "Claim".

6. Wait up to 24 hours for your badge to appear.
