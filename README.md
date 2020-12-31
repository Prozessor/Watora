# Watora
This is a Fork of the official repository of Watora, the discord music bot.

Head over to the official repository **https://github.com/Zenrac/Watora**

## Requirements: <br>
- [Python3.6+ with pip](https://www.python.org/downloads/)<br>
- [mongodb](https://www.mongodb.com/download-center/community) <br>
- [Watora Translations](https://github.com/Zenrac/watora-translations) <br>
- [Lavalink](https://github.com/Frederikam/Lavalink) <br>
- **Needs Java 11+ for Lavalink** Use: [OpenJDK](https://jdk.java.net/archive/) or [AdoptOpenJDK](https://adoptopenjdk.net/releases.html?variant=openjdk13&jvmVariant=hotspot) <br>
> *Java 11 appears to have some issues with Discord's TLS 1.3. Java 14 has other undiagnosed HTTPS problems. Use Java 13. Docker images have been updated. See #258, #260

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

#### WEEB (WEEB_API) -> https://weeb.sh/ 
> weeb.sh currently is an invite only based service for discord bot creators wanting to enhance their bots with awesome and easy to use features.<br>If you think that you should also be a part of weeb.sh, feel free to write them at devs@weeb.sh


#### GENIUS (LYRICS_API) -> https://genius.com/developers <br>
> Create an API Client and generate and copy your Client Access Token


#### SPOTIFY ID & SECRET -> https://developer.spotify.com/dashboard/ <br>
> Login/Sign Up and create an APP and get your Client ID & Secret.


#### YT_KEY (YOUTUBE_API) -> https://developers.google.com/youtube/v3/getting-started <br>
> Login and have fun with the linked guide from Google


#### KSOFT (KSOFT_API) -> https://api.ksoft.si/
> Login and create an application<br>If your application was created successfully a green message will appear. After that please wait patiently for administrators to approve your application, when your app is approved you'll receive a ping in the official server and the token will appear in your dashboard.


#### MEMER (MEMER_API) -> https://dankmemer.services/ 
> Login, go to Dashboard and make a Request.



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
