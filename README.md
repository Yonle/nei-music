

![nei-music](https://cdn.glitch.com/1a3dfe50-5648-4538-9499-d5a39ac7b798%2FUntitled71_20200720095138.png?v=1595213533503)
> Play your Cool Song at This bot. Free for remix...

## Requirements

1. Discord Bot Token **[Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)**
2. YouTube Data API v3 Key **[Guide](https://developers.google.com/youtube/v3/getting-started)**
 2.1 Soundcloud Client ID **[Guide](https://github.com/zackradisic/node-soundcloud-downloader)**
3. Node.js v12.0.0 or latest

## Getting started
```javascript
git clone https://github.com/yonle/nei-music
cd nei-music
npm i
```


## Configuration

Copy or Rename config.json.example to config.json and fill out the values:
Note: Never commit or share your token or api keys publicly ⚠️
```json
{
  "TOKEN": "",
  "YOUTUBE_API_KEY": "",
  "SOUNDCLOUD_CLIENT_ID": "",
  "MAX_PLAYLIST_SIZE": 10,
  "PREFIX": "!",
  "PRUNING": false
}
```
# 🌟New!
You can also use `.env` as your configure for musicbots! For do this, Go to [This Reposity](https://github.com/nekunei/nei-music) for using `.env` configure !

## Features & Commands

> Note: The default prefix is '!'

* 🎶 Play music from YouTube via url
  * `!play https://www.youtube.com/watch?v=GLvohMXgcBo`
* 🔎 Play music from YouTube via search query
  * `!play under the bridge red hot chili peppers`
* 📃 Play youtube playlists via url
  * `!playlist https://www.youtube.com/watch?v=YlUKcNNmywk&list=PL5RNCwK3GIO13SR_o57bGJCEmqFAwq82c`
* 🔎 Play youtube playlists via search query
  * `!playlist linkin park meteora`
* Command Handler from [discordjs.guide](https://discordjs.guide/)
* Queue system (!queue)
* Toggle Loop / Repeat (!loop)
* Volume control (!volume)
* Pause (!pause)
* Resume (!resume)
* Skip (!skip)
* Toggle pruning of bot messages (!pruning)
* Help (!help)
* Media Controls via Reactions
![reactions](https://cdn.glitch.com/1a3dfe50-5648-4538-9499-d5a39ac7b798%2FIMG_20200720_094549.JPG?v=1595213171592)

## By @Yonle & @nekunei. 
Powered by <a href="https://glitch.com/@nekunei-team">@nekunei-team</a>
Inspired by: [eritislami/evobot](https://github.com/eritislami/evobot) and Improved by @nekunei and @yonle !
Support Our <a href="https://discord.gg/FJwXgEF">Discord Server</a>
# ChangeLog

* 1.2.1
   - Added for `config.json` file for configuring Token which `.env` doesn't support at some Software

* 1.2.0 
 * Added:
   - Soundcloud Support
   - Search Command
   - Lyrics Command 
   - Remove command
   - SkipTo Command
   - NowPlaying Command
   - And Few Some Cool command Added!
   - Bug Fixes

* 1.1.2 
  * Making .env For Securing Your TOKEN.
