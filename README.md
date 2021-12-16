# Kontak
Simple bot to receive feedback,same as livegram bot but with more features &amp; full control over bot

<a href="https://heroku.com/deploy?template=https://github.com/XenonTheInertG/Kontak">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>

- Go to  [my.telegram.org](https://my.telegram.org/)
     - And get your `API ID`
     - And `API_HASH`

- Paste the below `API_HASH` and `API_ID` respectively.

- Give a password for your bot to login to recive feedbacks
**NOTE:** You will recive feedbacks only 24hrs if you login. So better add your Name in `OWNER_ID`

- Enter Some rules.

- Type the start message which should be visible to other when anyone start the bot.

- Give your ID in `OWNER_ID` for receiving feedbacks.

- Get the Bot Father Token from [@BotFather](https://telegram.dog/botfather)

- Paste the token below `TG_BOT_TOKEN`


- Deploy to VPS
```bash
git clone https://github.com/XenonTheInertG/Kontak
cd Kontak
virtualenv -p python3 VENV
. ./VENV/bin/activate
pip install -r requirements.txt
cp config.py
python kontak.py
```

# Open-sourced it to celebrate hacktoberfest
