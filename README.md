# Discord Auto Send Message Bot
Discord Auto Send Message Bot is a simple Python3 script designed to automate the sending of messages through your Discord account at regular intervals without the need for manual intervention.

## Requirement
- Computer with the following specification

| Name | Second Header |
| ------------- | ------------- |
| Operating System  | Ubuntu 22.04 LTS  |
| CPU  | 1 Cores  |
| RAM  | 1 GB  |
| SSD  | 25 GB  |
- Python3  

## Features
- Ease of Use: Set it up easily by filling out the configuration in the config.json file.
- Automation: The script continuously sends messages based on the specified time interval.

## Setup
1. **Fill Out The Config**:
- Open the config.json file and provide your [Discord token](##How-To-Get-Discord-Token)
2. **Run the Script:**
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

