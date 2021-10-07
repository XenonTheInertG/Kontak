# Kontak
Simple bot to receive feedback,same as livegram bot but with more features &amp; full control over bot

<a href="https://heroku.com/deploy?template=https://github.com/XenonTheInertG/Kontak">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>


- Deploy to VPS
```bash
git clone https://github.com/XenonTheInertG/Kontak
cd Kontak
virtualenv -p python3 VENV
. ./VENV/bin/activate
pip install -r requirements.txt
cp configs.py
(Edit variables in config.py)
python kontak.py
```
