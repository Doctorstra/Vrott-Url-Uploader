## Vrott-Url-Uploader
If you find any bugs, report at @Dads_links

**My Features**:

👉 Upload as file/video from any NON-DRM Vrott link

👉 Permanent thumbnail support.

### Installation


#### Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://www.heroku.com/deploy?template=https://github.com/Doctorstra/Vrott-Url-Uploader)

#### Run in your VPS

* Install requirements

```sh
sudo apt install python3-pip
sudo apt install ffmpeg
```

* Create config.py appropriately (Refer Configs section)

* Run the app

```sh
git clone https://github.com/Doctorstra/Vrott-Url-Uploader
cd Vrott-Url-Uploader
pip3 install -r requirements.txt
python3 bot.py
```

## Configs

* TG_BOT_TOKEN  - Get bot token from @BotFather
* APP_ID        - From my.telegram.org (or @UseTGXBot)
* API_HASH      - From my.telegram.org (or @UseTGXBot)
* DB_URI        - PostgreSQL DB URL

## Commands

* /start             - Check if bot is alive
* /help              - To know how the bot works
* /upgrade           - Nothing much here
* /showthumb         - Shows saved thumbnail
* /delthumb          - Clear saved thumbnail


## Credits, and Thanks to Beloved Developers ;

* [Doctorstra](https://github.com/Doctorstra)
