# Discord Auto Send Message Bot
Discord Auto Send Message Bot is a simple Python3 script designed to automate the sending of messages through your Discord account at regular intervals without the need for manual intervention.

## Requirement
- Computer with the following specification

| Name | Minimum |
| ------------- | ------------- |
| Operating System  | Ubuntu 22.04 LTS  |
| CPU  | 1 Cores  |
| RAM  | 1 GB  |
| SSD  | 25 GB  |
- Python3

> It is adviced to use a VPS. We use Digital Ocean with the following specifications ```Singapore/ 1 Core/ 1 GB RAM/ 25 GB SSD```. If you need a VPS, we have a free link for a $200 DigitalOcean VPS credit. Enough to run the bot for full year. Register now with the [main link](https://m.do.co/c/497333605c2e) / [backup link](https://m.do.co/c/6bce9210eb7) to get it.

<a href="https://www.digitalocean.com/?refcode=497333605c2e&utm_campaign=Referral_Invite&utm_medium=Referral_Program&utm_source=badge"><img src="https://web-platforms.sfo2.cdn.digitaloceanspaces.com/WWW/Badge%201.svg" alt="DigitalOcean Referral Badge" /></a>

## Features
- Ease of Use: Set it up easily by filling out the configuration in the config.json file.
- Automation: The script continuously sends messages based on the specified time interval.

## Preparation
1. **Install Screen:**
```
sudo apt-get install screen
```
2. **Download the repo**
```
git clone https://github.com/nmluthfi/Discord-Auto-Send-Message-Bot && cd Discord-Auto-Send-Message-Bot
```

## Run the Bot
1. **Fill Out The Config**:
- Open the config.json file
```
  nano config.json
```
- Provide your [Discord token](#How-To-Get-Discord-Token) and save the file ```Control + X```
2. **Create a Screen:**
```
screen -Rd discord_auto_send_message
```
3. **Run the Script:**
- Execute the command python3 main.py in your terminal.
  
![image](https://github.com/nmluthfi/Discord-Auto-Send-Message-Bot/assets/33769324/03101b10-2cf4-4246-8b8a-031fe5d806ae)


## How To Get Discord Token

1. **Access Discord Web:**
- Open Discord in your web browser.
2. **Open Console:**
-  Right-click anywhere on the page and select 'Inspect' or press Ctrl + Shift + I to open the Developer Tools. Go to the 'Console' tab.

### Method 1
3.1. **Run Command:**
- Paste the following command in the console:
```js
webpackChunkdiscord_app.push([[""],{},req=>copy(Object.values(req.c).find(x => x?.exports?.default?.getToken).exports.default.getToken())])
```
4.1. **Token Retrieval:**
- Your Discord token should now be copied to your clipboard, ready to be pasted into the config.json file.

### Method 2
3.2. **Manually: **
- Navigate to the "Application" tab
- Within the Application tab, find the Storage section, and click the down arrow next to Local storage.
- Locate the Discord URL and click on it.
- In the Filter field, type token.
- Click the Toggle device toolbar button.
  
4.2. **Token Retrieval:**
- Your Discord token will be displayed. You can copy and paste it using (CTRL+C, CTRL+V) or note it down for future reference.
![image](https://github.com/nmluthfi/Discord-Auto-Send-Message-Bot/assets/33769324/958df214-cd89-4dd1-b356-8af2c67d3504)

