# Reddit Video Maker Bot 🎥

All done WITHOUT video editing or asset compiling.

## Disclaimers 🚨

- **At the moment**, this repository won't attempt to upload this content through this bot. It will give you a file that
  you will then have to upload manually. This is for the sake of avoiding any sort of community guideline issues.

## Requirements

- Python 3.9 +
- Playwright (this should install automatically in installation)

## Installation 👩‍💻

1. Clone this repository
2. Run `pip install -r requirements.txt`

3. Run `python -m playwright install` and `python -m playwright install-deps`

3.1. If you have a problem running `python main.py`, then you need to download first ffmpeg using homebrew: `brew install ffmpeg`

3.2. For any problem running using pip, python. Use `pip3` and `python3`.

4. Run `python main.py`
5. Visit [the Reddit Apps page.](https://www.reddit.com/prefs/apps), and set up an app that is a "script".
6. The bot will ask you to fill in your details to connect to the Reddit API, and configure the bot to your liking
7. Enjoy 
8. If you need to reconfigure the bot, simply open the `config.toml` file and delete the lines that need to be changed. On the next run of the bot, it will help you reconfigure those options.

(Note if you got an error installing or running the bot try first rerunning the command with a three after the name e.g. python3 or pip3)

## Video

https://user-images.githubusercontent.com/66544866/173453972-6526e4e6-c6ef-41c5-ab40-5d275e724e7c.mp4

## Contributing & Ways to improve 📈

In its current state, this bot does exactly what it needs to do. However, lots of improvements can be made.

I have tried to simplify the code so anyone can read it and start contributing at any skill level. Don't be shy :) contribute!
