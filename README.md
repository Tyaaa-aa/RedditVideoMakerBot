# Reddit Video Maker Bot ++🎥

https://user-images.githubusercontent.com/6053155/170525726-2db23ae0-97b8-4bd1-8c95-00da60ce099f.mp4

All done WITHOUT video editing or asset compiling. Just pure ✨programming magic✨.

Created by Lewis Menelaws & [TMRRW](https://tmrrwinc.ca) modified by [Tya](https://tya.design/)

This is my first time using python and I tried adding a couple features.

## New Features✨

- Change [accent](https://gtts.readthedocs.io/en/latest/module.html?highlight=accent)
- Change background video (random list)
- Change video speed (default voice is really slow)
- Better naming scheme for output videos in `final` folder

[<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/6053155/170528535-e274dc0b-7972-4b27-af22-637f8c370133.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/6053155/170528582-cb6671e7-5a2f-4bd4-a048-0e6cfa54f0f7.png">
  <img src="https://user-images.githubusercontent.com/6053155/170528582-cb6671e7-5a2f-4bd4-a048-0e6cfa54f0f7.png" width="350">
</picture>](https://tmrrwinc.ca)

## Motivation 🤔

These videos on TikTok, YouTube and Instagram get MILLIONS of views across all platforms and require very little effort. The only original thing being done is the editing and gathering of all materials...

... but what if we can automate that process? 🤔

## Disclaimers 🚨

- This is purely for fun purposes.
- **At the moment**, this repository won't attempt to upload this content through this bot. It will give you a file that you will then have to upload manually. This is for the sake of avoiding any sort of community guideline issues.

## Requirements

- Python 3.6+
- Playwright (this should install automatically during installation)

## Installation 👩‍💻

1. Clone this repository
2. Rename `.env.template` to `.env` and replace all values with the appropriate fields. To get Reddit keys (**required**), visit [the Reddit Apps page.](https://www.reddit.com/prefs/apps) TL;DR set up an app that is a "script". Copy your keys into the `.env` file, along with whether your account uses two-factor authentication.
3. Install [FFmpeg](https://ffmpeg.org/download.html) and include the path of the `ffmpeg.exe` into the `.env` file. A guide for installing FFmpeg on windows can be found [here](https://www.wikihow.com/Install-FFmpeg-on-Windows)
4. Run `pip3 install -r requirements.txt`
5. Run `playwright install` and `playwright install-deps`.
6. Make any configurations you want to change in the `main.py` file
7. Run `python3 main.py`
8. ...
9. Enjoy 😎

## Contributing & Ways to improve 📈

In its current state, this bot does exactly what it needs to do. However, lots of improvements can be made.

I have tried to simplify the code so anyone can read it and start contributing at any skill level. Don't be shy :) contribute!

- [ ] Allowing users to choose a reddit thread instead of being randomized.
- [x] Allowing users to choose a background that is picked instead of the Minecraft one.
- [x] Allowing users to choose between any subreddit.
- [x] Allowing users to change voice.
- [ ] Creating better documentation and adding a command line interface.
