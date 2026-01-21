# PerVerBot

Welcome to PerVerBot! A gaming Discord bot that uses various AI models to generate content and stats about your games, featuring unique personalities. The bot tracks user activity, analyzes and comments on your CS2 and LoL matches, tracks BF6 stats, generates podcasts, and offers custom profile features.

## Table of Contents
- [What can PerVerBot do?](#what-can-perverbot-do)
- [Commands](#commands)
  - [General Commands](#general-commands)
  - [Admin Commands](#admin-commands)
    - [Notification](#notification)
    - [Personality](#personality)
    - [Podcast Config](#podcast-config)
    - [Language](#language)
    - [Word Limits](#word-limits)
    - [Current Status](#current-status)
- [Profile Setup](#profile-setup)
  - [Description](#description)
  - [Personality (DM)](#personality-dm)
  - [Language (DM)](#language-dm)
  - [Game Related Settings](#game-related-settings)
  - [Delete Profile](#delete-profile)
- [Privacy](#privacy)

## What can PerVerBot do?

- **AI-Powered Chat**: Mention the bot (`@PerVerBot`) with a message, and it will reply using its unique, chosen personality.
- **Game Activity Tracking**: The bot automatically detects when you start and stop playing a game and will often share a humorous comment about it in the server.
- **CS2 & League of Legends Match Analysis**: Get detailed analysis of your gameplay with clips, commentary, a deep stats report, and a two-voice podcast.
- **BF6 Global and Session Stats Comments**: Receive commentary on your global and session stats for BF6.
- **Custom Profiles**: Create your own user profile to enable match analysis and other personalized features.
- **CS2 Statistics Chat (BETA)**: In the dedicated stats channel (if configured by admins), you can chat with the bot about your CS2 performance and receive detailed statistics.

> **Note**: For CS2 and LoL analysis you need a profile. See the [Profile Setup](#profile-setup) section below.

## Commands

### General Commands
- `/help`: Shows a list of available commands.
- `/profile`: Create and manage your user profile. A profile is necessary to use features like CS2 and League of Legends match analysis.
- `@PerVerBot <message>`: Chat directly with the bot. Ask it anything!
- `/cs2analysis`: Trigger CS2 analysis view for your recent matches (requires CS2 profile setup).
- `/lolanalysis`: Trigger LoL match view for your recent matches (requires LoL profile setup).
- `/Bf6_stats`: Trigger BF6 stats embed with PerVerBot commentary.
- `/historical_report`: Generate a CS2 stats-based report for a chosen period.

### Admin Commands
- `/config`: (For server admins) Configure bot settings for the server.

<img width="575" height="200" alt="image" src="https://github.com/user-attachments/assets/55c6fb1b-004e-4ded-bf07-6db3b501dd3d" />

#### Notification
<img width="626" height="279" alt="image" src="https://github.com/user-attachments/assets/b762a193-f005-4cd3-bc91-9ebfb48ba726" />

- **Game Notification:** Tracks users' game activity. Every time a server user starts or stops a game, PerVerBot reacts with a comment. **Disabled by default**. (Can be spammy, especially on populated servers).
- **Game related notifications (CS2, LoL, BF6)**: In this channel, you will receive analysis requests and game comments. You can disable this kind of notification in the dropdown menu.
- **Update channel:** In this channel, you will receive PerVerBot App update notes.
- **Welcome:** When a new user enters your server, PerVerBot greets them in the selected channel. You can disable this in the dropdown menu.

#### Personality  
You can set PerVerBot's personality. This personality will be used in **EVERY** server interaction (DM interactions have their own separate personality settings).

<img width="630" height="125" alt="image" src="https://github.com/user-attachments/assets/4f4326df-871c-49ce-8f80-1e453eff676c" />

#### Podcast Config
You can change the default podcast voices. You can find available voices here: 

<img width="1062" height="539" alt="image" src="https://github.com/user-attachments/assets/2e7d2b00-5e77-4235-ac15-7924d173c334" />

#### Language
You can set PerVerBot's language for the server.

#### Word Limits
You can set word limits for PerVerBot's answers.

#### Current Status
Displays the current server configuration.

## Profile Setup

Here you can set up your profile:


<img width="575" height="314" alt="image" src="https://github.com/user-attachments/assets/93fa71a5-f647-48a9-a121-e823fec371fc" />

### Description
You can write a brief description of yourself. This is what PerVerBot knows about you, and it will use this information to interact with you.

### Personality (DM)
You can set PerVerBot's personality. This personality applies **ONLY** to DM messages with the bot; for server-related interactions, the personality is set by admins.

### Language (DM)
You can set the language PerVerBot speaks. This language will be used **ONLY** in DM messages; for server-related interactions, the language is set by admins.

### Game Related Settings
**Steam & CS2:**
To let PerVerBot analyze your CS2 games, you need to set up Steam and CS2 settings:

<img width="482" height="605" alt="image" src="https://github.com/user-attachments/assets/86ad8a4e-9687-4be8-b6db-2f796a666dc3" />

1. **SteamID**: Copy the numbers after `profiles/` from your Steam profile URL.
   - Example: `https://steamcommunity.com/profiles/123456789` → Use `123456789`

2. **Steam Auth Code**: Get this from [Steam Help](https://help.steampowered.com/en/wizard/HelpWithGameIssue/?appid=730&issueid=128) (ACCESS MATCH HISTORY).

<img width="978" height="148" alt="Steam auth code help page" src="https://github.com/user-attachments/assets/bb3703b4-21e8-4771-bfbd-96a570460d93">

3. **Match Share Code**: From your CS2 match history, use only the "CSGO-" part.
   - The bot can only see matches played AFTER the share code you select (matches must not be older than 30 days).

<img width="1600" height="900" alt="CS2 match history with share codes" src="https://github.com/user-attachments/assets/0399635f-6764-4334-ab23-e0f0216f66ab">

<img width="515" height="133" alt="CS2 share code format" src="https://github.com/user-attachments/assets/29239bf0-266b-4e0e-b661-0a3ec1984b3d">


4. **Faceit Nickname:**
   - If you wanna analyze even your faceit matches, add your faceit nickname here. **The matches will be AUTO SYNCED with leetify!**

**Riot & LoL:**
For League of Legends, you need:
- **Riot ID**: Your in-game username.
- **Region**: Your server region.

<img width="478" height="395" alt="image" src="https://github.com/user-attachments/assets/fe2cc123-bca6-4c60-9aea-2f326c49671c" />

**BF6**:
For BF6 you just need your EA ID:

<img width="475" height="311" alt="image" src="https://github.com/user-attachments/assets/b4c8a390-0fc3-46ab-a150-fb2aa22cbbf9" />


### Delete Profile
Permanently delete your profile and data.

## Privacy
For more information, please read our [Privacy Policy](PRIVACY_POLICY_EN.md) and [Terms of Service](TERMS_OF_SERVICE_EN.md).
