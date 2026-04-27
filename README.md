# Discord Bot Monitor
A Python script that watches for your bots status to change

# IMPORTANT!
You **NEED** to have an extra bot/bot token for this to work!

**YOUR MONITER BOT AND THE BOT YOUR MONITERING _MUST_ BE IN THE SAVE SERVER/GUILD**

# How To Configure!
1. Open `DiscordBotMoniter.py` with any text or code editor
2. you should see tese under "config"
<img width="782" height="174" alt="image" src="https://github.com/user-attachments/assets/b6e6d17b-c55b-4a75-80e1-df203314a8aa" />
edit them with what they say to put

(If you dont know how to get a Webhook URL or bot token the tutorials are below)

# How To Setup!
**MAKE SURE YOU CONFIGURED IT!!!**

1. make sure you have python (if not get it [HERE](https://python.org)
2. get the `DiscordBotMoniter.py` file
3. open terminal (hit `Windows` + `R` and type cmd)
4. **MAKE SURE YOUR IN THE FOLDER YOU HAVE THE FILE AT**

   (so type in terminal `cd (whereever you have it saved)

   PS. This may not be necessary but it didnt build unless i did so
6. then put `py -m PyInstaller --onefile --windowed --name "[whatever you want the file name as]" DiscordBotMoniter.py`
7. then there should be a new `dist` folder, your application will be in there

# How To Get Webhook URLS Ect.
--BOT TOKENS--

To get a bot token you need to go to the [Discord Dev Portal](discord.com/developers/applications/) then oncce you have your app go to "Bot"
<img width="1831" height="918" alt="image" src="https://github.com/user-attachments/assets/373ab07a-26fa-4727-a35f-b2f157b9633a" />
Once you have done so click "Reset Token"
<img width="727" height="108" alt="image" src="https://github.com/user-attachments/assets/85e0af67-95fc-4be8-8358-965ffde2d811" />
**DO _NOT_ SHARE YOUR TOKEN WITH _ANYONE_ THEY WILL HAVE ACCESS TO YOUR BOT AND IF THEY GET THE BOT BANNED IT CAN LEAD TO YOUR ACCOUNT GETTING BANNED. AND REMEMBER DISCORD EMPLOYEES WILL _NEVER_ ASK FOR YOUR TOKEN**

--WEBHOOK URLS--

To get a webhook url go to the channel you want the webhook at and hit settings (the gear icon)
<img width="240" height="26" alt="image" src="https://github.com/user-attachments/assets/d120f873-d87a-4d33-a6a2-4bc3b5a8f2f3" />
=> Integrations
<img width="237" height="211" alt="image" src="https://github.com/user-attachments/assets/95067d7b-7b89-4cfc-a91e-256fc0b1a3da" />
=> Wehooks
<img width="672" height="337" alt="image" src="https://github.com/user-attachments/assets/bd11f2b3-2bd6-46c8-be88-249216730fe7" />
you should see this (minus the CR7T Status thing)
<img width="687" height="330" alt="image" src="https://github.com/user-attachments/assets/24fe0b0a-d917-4e97-b3d5-8a1c4566fdcc" />
CLick "New Webhook" name it whatever then hit "Copy Webhook URL"

**DO _NOT_ SHARE YOUR WEBHOOK URL WITH ANYONE THEY CAN SPAM YOUR SERVER IF YOU DO SO**
