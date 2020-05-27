# Watora
This is a Fork of the official repository of Watora, the discord music bot.

Head over to the official repository **https://github.com/Zenrac/Watora**

## Requirements: <br>
- [Python3.6+ with pip](https://www.python.org/downloads/)<br>
- [mongodb](https://www.mongodb.com/download-center/community) <br>
- [Java](https://www.java.com/fr/download/) <br>
- [Watora Translations](https://github.com/Zenrac/watora-translations)

## Installation
```
git clone https://github.com/Zenrac/Watora
cd Watora
```
Install or update all dependencies with `update.bat` on Windows, or `update.sh` on Linux.<br>

## Get Started
- Fill your credentials and tokens in `config/tokens.json` and `settings.json`, you can use the examples as a base.<br>
- Start a mongo server in a terminal with `mongod`.<br>
- Make sure that you have at least one [Lavalink server](https://github.com/Frederikam/Lavalink) running to use music features.<br>
- [Watora Translations](https://github.com/Zenrac/watora-translations) are supposed to go into `config/i18n/`<br>
- You may have to delete the `cogs/web.py` cog has it will not be useful in any point for a local bot.<br>
- Start Watora with `run.bat` on Windows, or `run.sh` on Linux.<br>

## Get Token and API Keys

- WEEB (WEEB_API) -> https://weeb.sh/ 
```
weeb.sh currently is an invite only based service for discord bot creators wanting to enhance their bots with awesome and easy to use features.<br>
If you think that you should also be a part of weeb.sh, feel free to write them at devs@weeb.sh<br>
```
<br>
- GENIUS (LYRICS_API) -> https://genius.com/developers
`Create an API Client and generate and copy your Client Accsess Token`
<br>
- SPOTIFY ID & SECRET -> https://developer.spotify.com/dashboard/
`Login/Sign Up and create an APP and get your Client ID & Secret.`
<br>
- YT_KEY (YOUTUBE_API) -> https://developers.google.com/youtube/v3/getting-started
`Login and have fun with the linked guide from Google`
<br>

- KSOFT (KSOFT_API) -> https://api.ksoft.si/
```
Login and create an application
If your application was created successfully a green message will appear. After that please wait patiently for administrators to approve your application, when your app is approved you'll receive a ping in the official server and the token will appear in your dashboard. 
```
<br>
- MEMER (MEMER_API) -> https://dankmemer.services/
```
Login, go to Dashboard and make a Request.
ATM:
❌ New applications have been closed for the time being. We apologize for the inconvenience.
```


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

[![Discord Bots](https://discordbots.org/api/widget/220644154177355777.svg)](https://discordbots.org/bot/220644154177355777)
