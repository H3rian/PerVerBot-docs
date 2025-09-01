# PerVerBot

Welcome to PerVerBot! A gaming Discord bot that uses Google Gemini to generate sarcastic and witty responses based on the choosen personality. The bot tracks user games, analyse and comment your CS2 and LOL mathches and offers custom profile features.

## What can PerVerBot do?

- **AI-Powered Chat**: Mention the bot (`@PerVerBot`) with a message and it will talk back to you with its unique, sassy personality powered by Google Gemini.
- **Game Activity Tracking**: The bot automatically detects when you start and stop playing a game and will often share a humorous comment about it in the server.
- **CS2 & League of Legends Match Analysis**: Get detailed analysis of your gameplay.
  - For **Counter-Strike 2**, add your SteamID and a match share code to your profile.
  - For **League of Legends**, simply add your Riot ID to your profile to get your recent matches analyzed.
- **Custom Profiles**: Create your own user profile to enable match analysis and other personalized features.
- **CS2 Statistics Chat**: In the dedicated stats channel (if configured by admins), you can chat with the bot about your CS2 performance and get detailed statistics.

For cs2 and lol analysis you need a profile, see the profile commands details below

## Commands

Here are the main commands you can use:

### General Commands
- `/help`: Shows a list of available commands.
- `/profile`: Create and manage your user profile. A profile is necessary to use features like CS2 and League of Legends match analysis.
<img width="503" height="692" alt="image" src="https://github.com/user-attachments/assets/5d2aa1d7-149f-484f-a89b-93c22392bfe8">

  For CS2 you need a valid SteamID, steam auth code and match share code. You can easily get your steam_id directly througt steam client clicking on your profile and coping the url, you have to insert ONLY the numbers after profiles/ (like this https://steamcommunity.com/profiles/123456789).
  
  You can get the steam auth code from here https://help.steampowered.com/en/wizard/HelpWithGameIssue/?appid=730&issueid=128 (ACCESS MATCH HISTORY) <img width="978" height="148" alt="image" src="https://github.com/user-attachments/assets/bb3703b4-21e8-4771-bfbd-96a570460d93" />

  You can get the match share code inside the cs2 client in your match history. The bot can see only matches played AFTER the share code you select (not older then 30 days). YOU NEED TO INSERT ONLY THE "CSGO-" PART in the profile <img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/0399635f-6764-4334-ab23-e0f0216f66ab" /> <img width="515" height="133" alt="image" src="https://github.com/user-attachments/assets/29239bf0-266b-4e0e-b661-0a3ec1984b3d" />


  For LOL you need a valid riot ID and your region
  
  <img width="501" height="517" alt="image" src="https://github.com/user-attachments/assets/83a5ba4c-f7ed-4374-ae9b-55b9d3d45139" />
 


- `@PerVerBot <message>`: Chat directly with the bot. Ask it anything!
- `/cs2analysis`: Trigger CS2 analysis view for your recent matches (requires CS2 profile setup).


### Admin Commands
- `/config`: (For server admins) Configure bot settings for the server, like setting up a specific channel for game activity notifications, choosing the bot's personality or custom api keys.
    <img width="700" height="178" alt="image" src="https://github.com/user-attachments/assets/ba2d4922-332e-47fe-8476-2e0dfdadb7c8" />
  - custom and optional api keys
      You can set your personal api keys to use instead of the default one for Gemini and TTS (is always based on gemini so you can use the same one)
  - Notifications
      You can enable/disable the notifications and set up the relative channels
   - Personality
      You can choose the bot's personality
   -  Pocast config
       You can choose the voices for the podcast. You can change the default ones, choosing from here https://aistudio.google.com/generate-speech?hl=it&_gl=1*1hb5yj8*_ga*ODcwNzAwODQzLjE3NDUwMTQ2OTc.*_ga_P1DBVKWT6V*czE3NTY3NTgyNjgkbzU0JGcwJHQxNzU2NzU4Mjc0JGo1NCRsMCRoMTc1MDgxMDA2NQ..
   - Admin tools
       You can manage users profiles, clear the chat or the stats_chat history (useful when you note strange behaviour from the bot or you wanna wipe all the old conversations), change the language and the words limit of the bot answers


## Privacy
For more information, please read our [Privacy Policy](PRIVACY_POLICY_EN.md) and [Terms of Service](TERMS_OF_SERVICE_EN.md).
