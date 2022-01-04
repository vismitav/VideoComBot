---

## 🌀 Video Compressor Bot   Product by BINARY Tech

[![videocombot](https://telegra.ph/file/9ba00f90939c4134d5629.png)](https://t.me/ab_binary)


#### Deploy to Heroku

  [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Silentzlk/VideoComBot)

#### The Hard Way

```sh
virtualenv -p python3 VENV
. ./VENV/bin/activate
pip install -r requirements.txt
# <Create config.py with variables as given below>
python bot.py
```

An example `config.py` file could be:

**Not All of the variables are mandatory**

```python3
from sample_config import Config

class Development(Config):
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
  TG_BOT_TOKEN = ""
  AUTH_USERS = [
    7351948
  ]
```

### [@BotFather](https://telegram.dog/BotFather) Commands

```
start - Checking bot live.
compress - To compress the video.
cancel - Stop the process.
log - Get log
help - To know about bot
```
## CREDITS

[@SpEcHide](https://github.com/spechide/publicleech) and [@jijinividcombot](https://github.com/Jijinr/VidComBot)

#### LICENSE
- GPLv3
