# PerVerBot

Welcome to PerVerBot! A gaming Discord bot that uses Google Gemini to generate sarcastic and witty responses based on the chosen personality. The bot tracks user games, analyzes and comments your CS2 and LoL matches and offers custom profile features.

## Table of Contents
- [What can PerVerBot do?](#what-can-perverbot-do)
- [Commands](#commands)
  - [General Commands](#general-commands)
  - [Admin Commands](#admin-commands)
- [Profile Setup](#profile-setup)
  - [CS2 Profile](#cs2-profile)
  - [LoL Profile](#lol-profile)
- [Privacy](#privacy)

## What can PerVerBot do?

- **AI-Powered Chat**: Mention the bot (`@PerVerBot`) with a message and it will talk back to you with its unique, choosen personality
- **Game Activity Tracking**: The bot can automatically detects when you start and stop playing a game and will often share a humorous comment about it in the server.
- **CS2 & League of Legends Match Analysis**: Get detailed analysis of your gameplay with clips, comment, a deep stats report and a 2 voices podcast.
  - For **Counter-Strike 2**, add your SteamID and a match share code to your profile.
  - For **League of Legends**, simply add your Riot ID to your profile to get your recent matches analyzed.
- **BF6 global and session stats comments**
- **Custom Profiles**: Create your own user profile to enable match analysis and other personalized features.
- **CS2 Statistics Chat (BETA)**: In the dedicated stats channel (if configured by admins), you can chat with the bot about your CS2 performance and get detailed statistics.

> **Note**: For CS2 and LoL analysis you need a profile. See the [Profile Setup](#profile-setup) section below.

## Commands

### General Commands
- `/help`: Shows a list of available commands.
- `/profile`: Create and manage your user profile. A profile is necessary to use features like CS2 and League of Legends match analysis. 

<img width="575" height="314" alt="image" src="https://github.com/user-attachments/assets/93fa71a5-f647-48a9-a121-e823fec371fc" />


- `@PerVerBot <message>`: Chat directly with the bot. Ask it anything!
- `/cs2analysis`: Trigger CS2 analysis view for your recent matches (requires CS2 profile setup).

### Admin Commands
- `/config`: (For server admins) Configure bot settings for the server.
- 
<img width="575" height="200" alt="image" src="https://github.com/user-attachments/assets/55c6fb1b-004e-4ded-bf07-6db3b501dd3d" />

### Notification
<img width="626" height="279" alt="image" src="https://github.com/user-attachments/assets/b762a193-f005-4cd3-bc91-9ebfb48ba726" />

**Game Notification:** user's games activity tracking. Everytime a server's user starts or stops a game, perverbot reacts with a comment. **Disabled by default**. Can be spammy, especially on populated servers.
**Game related notifications (Cs2, Lol, Bf6)**: in this channel you will receive analysis request and game comments. You can disable this kind of notification in the dropdown menu.
**Update channel:** in this channel you will receive Perberbot App updates notes.
**Weclome:** when a new user enter your server, Perverbot greets him in the selected channel. You can disable it in the dropdown menu.     

### Personality  
You can set Perverbot personality. This personality will be used in **EVERY** server interaction (DM interactions has his own personality)

<img width="630" height="125" alt="image" src="https://github.com/user-attachments/assets/4f4326df-871c-49ce-8f80-1e453eff676c" />

### Podcast config
You can change the default podcast voices. You can find available voices here: 

<img width="1062" height="539" alt="image" src="https://github.com/user-attachments/assets/2e7d2b00-5e77-4235-ac15-7924d173c334" />

### Clear History and Clear Stats History
You can delete the server chat context (for normal interactions and stats interactions). When you do this, the next message will be the first interaction with the bot. Use this when you face strange behaviour, repetitive answers or if you change personality.

## Profile Setup

Here you can set your profile:
### Description
You can write a brief description of yourself. This is what Perverbot knows about you, he will use it to interact with you.

### Personality
You can set Perverbot personality. This personality ONLY in DM messages with the bot, for server related interaction the personality is set by admins

### Language
You can set the language with Perverbot speaks. This language will be used ONLY in DM message, for server related interaction the language is set by admins

### Game related settings
- **Steam & CS2:**
To let Perverbot analyze your CS2 games, you need to set up steam and cs2 settings:

<img width="482" height="605" alt="image" src="https://github.com/user-attachments/assets/86ad8a4e-9687-4be8-b6db-2f796a666dc3" />


1. **SteamID**: Copy the numbers after `profiles/` from your Steam profile URL
   - Example: `https://steamcommunity.com/profiles/123456789` → Use `123456789`

2. **Steam Auth Code**: Get this from [Steam Help](https://help.steampowered.com/en/wizard/HelpWithGameIssue/?appid=730&issueid=128) (ACCESS MATCH HISTORY)

<img width="978" height="148" alt="Steam auth code help page" src="https://github.com/user-attachments/assets/bb3703b4-21e8-4771-bfbd-96a570460d93">

3. **Match Share Code**: From your CS2 match history, use only the "CSGO-" part
   - The bot can only see matches played AFTER the share code you select (not older than 30 days)

<img width="1600" height="900" alt="CS2 match history with share codes" src="https://github.com/user-attachments/assets/0399635f-6764-4334-ab23-e0f0216f66ab">

<img width="515" height="133" alt="CS2 share code format" src="https://github.com/user-attachments/assets/29239bf0-266b-4e0e-b661-0a3ec1984b3d">

**Riot & Lol:**
For League of Legends, you need:
- **Riot ID**: Your in-game username
- **Region**: Your server region

<img width="478" height="395" alt="image" src="https://github.com/user-attachments/assets/fe2cc123-bca6-4c60-9aea-2f326c49671c" />

**Bf6**:
For Bf6 you need just your EA Id:
<img width="475" height="311" alt="image" src="https://github.com/user-attachments/assets/b4c8a390-0fc3-46ab-a150-fb2aa22cbbf9" />

### Clear DM History
You can delete your DM chat history with perverbot. When you do this, the next message will be the first interaction that the bot has knowledge with him. Use this when you face strange behaviour, repetitive answers or if you change personality.


### Delete profile

## Privacy
For more information, please read our [Privacy Policy](PRIVACY_POLICY_EN.md) and [Terms of Service](TERMS_OF_SERVICE_EN.md).
