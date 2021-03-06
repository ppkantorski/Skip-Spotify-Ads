# SkipSpotifyAds (macOS)
This program will restart Spotify in the background whenever ads come up for seamless streaming as well as log the songs that you listen to.

![alt-text](https://i.imgur.com/iP0k7or.png)
![alt-text](https://i.imgur.com/KyiWWA9.png)

## Installation
1. Extract the repository to `/Users/{user_name}/Documents/SkipSpotifyAds/`.
2. Run `build.py` to install the necessary dependencies and build `SkipSpotifyAds.app`.
3. You can now move the application into your Applications folder, but keep the repository within the folder you extracted it to.


## Python Script (still used, but now within the app)
![alt-text](https://i.imgur.com/YFOjnpl.png)

1. Dependencies
```
pip3 install SwSpotify
pip3 uninstall werkzeug
pip3 install werkzeug==2.0.3
```

2. Deploy using the `deploy.zsh` or by running `python3 skip_spotify_ads.py`.  You will need to keep both the .py and .zsh script within the same directory.
3. If using the .zsh script, SkipSpotifyAds will be launched on Screen GNU.  To attach/re-attach to the process run the following command:
```
screen -r skip_spotify_ads
```
To detach, press:
```CTRL+A, CTRL+D```
