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

- **AI-Powered Chat**: Mention the bot (`@PerVerBot`) with a message and it will talk back to you with its unique, sassy personality powered by Google Gemini.
- **Game Activity Tracking**: The bot automatically detects when you start and stop playing a game and will often share a humorous comment about it in the server.
- **CS2 & League of Legends Match Analysis**: Get detailed analysis of your gameplay.
  - For **Counter-Strike 2**, add your SteamID and a match share code to your profile.
  - For **League of Legends**, simply add your Riot ID to your profile to get your recent matches analyzed.
- **Custom Profiles**: Create your own user profile to enable match analysis and other personalized features.
- **CS2 Statistics Chat**: In the dedicated stats channel (if configured by admins), you can chat with the bot about your CS2 performance and get detailed statistics.
- **CS2 Detailed Dinamic Report**: At the end of the analysis you can ask for a deep report of the match with a **2d demo viewer**, allstar.gg squad hightlights, detailed stats of the match and historical leetify stats for every player and a round by round comment

> **Note**: For CS2 and LoL analysis you need a profile. See the [Profile Setup](#profile-setup) section below.

## Commands

### General Commands
- `/help`: Shows a list of available commands.
- `/profile`: Create and manage your user profile. A profile is necessary to use features like CS2 and League of Legends match analysis. You have to go through both profile sections to create it, even if you leave some field empty.

<img width="503" height="692" alt="Profile command example" src="https://github.com/user-attachments/assets/5d2aa1d7-149f-484f-a89b-93c22392bfe8">

- `@PerVerBot <message>`: Chat directly with the bot. Ask it anything!
- `/cs2analysis`: Trigger CS2 analysis view for your recent matches (requires CS2 profile setup).

### Admin Commands
- `/config`: (For server admins) Configure bot settings for the server.

<img width="700" height="178" alt="Config command example" src="https://github.com/user-attachments/assets/ba2d2d22-332e-47fe-8476-2e0dfdadb7c8">

## Profile Setup

### CS2 Profile
To set up your CS2 profile, you need three pieces of information:

1. **SteamID**: Copy the numbers after `profiles/` from your Steam profile URL
   - Example: `https://steamcommunity.com/profiles/123456789` → Use `123456789`

2. **Steam Auth Code**: Get this from [Steam Help](https://help.steampowered.com/en/wizard/HelpWithGameIssue/?appid=730&issueid=128) (ACCESS MATCH HISTORY)

<img width="978" height="148" alt="Steam auth code help page" src="https://github.com/user-attachments/assets/bb3703b4-21e8-4771-bfbd-96a570460d93">

3. **Match Share Code**: From your CS2 match history, use only the "CSGO-" part
   - The bot can only see matches played AFTER the share code you select (not older than 30 days)

<img width="1600" height="900" alt="CS2 match history with share codes" src="https://github.com/user-attachments/assets/0399635f-6764-4334-ab23-e0f0216f66ab">

<img width="515" height="133" alt="CS2 share code format" src="https://github.com/user-attachments/assets/29239bf0-266b-4e0e-b661-0a3ec1984b3d">

### LoL Profile
For League of Legends, you need:
- **Riot ID**: Your in-game username
- **Region**: Your server region

<img width="501" height="517" alt="LoL profile setup example" src="https://github.com/user-attachments/assets/83a5ba4c-f7ed-4374-ae9b-55b9d3d45139">

## Admin Configuration

The `/config` command allows server admins to configure:

- **Custom API Keys**: Set personal API keys for Gemini and TTS
- **Notifications**: Enable/disable notifications and set up channels
- **Personality**: Choose the bot's personality
- **Podcast Config**: Select voices for the podcast from [Google AI Studio](https://aistudio.google.com/generate-speech?hl=it&_gl=1*1hb5yj8*_ga*ODcwNzAwODQzLjE3NDUwMTQ2OTc.*_ga_P1DBVKWT6V*czE3NTY3NTgyNjgkbzU0JGcwJHQxNzU2NzU4Mjc0JGo1NCRsMCRoMTc1MDgxMDA2NQ..)
- **Admin Tools**: Manage user profiles, clear chat history, change language and word limits

## Privacy
For more information, please read our [Privacy Policy](PRIVACY_POLICY_EN.md) and [Terms of Service](TERMS_OF_SERVICE_EN.md).
