[![Stars](https://img.shields.io/github/stars/kaif-00z/AutoAnimeBot?style=flat-square&color=yellow)](https://github.com/kaif-00z/AutoAnimeBot/stargazers)
[![Forks](https://img.shields.io/github/forks/kaif-00z/AutoAnimeBot?style=flat-square&color=orange)](https://github.com/kaif-00z/AutoAnimeBotfork)
[![Python](https://img.shields.io/badge/Python-v3.10.4-blue)](https://www.python.org/)
[![CodeFactor](https://www.codefactor.io/repository/github/kaif-00z/autoanimebot/badge/main)](https://www.codefactor.io/repository/github/kaif-00z/autoanimebot/overview/main)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/kaif-00z/AutoAnimeBot/graphs/commit-activity)
[![Contributors](https://img.shields.io/github/contributors/kaif-00z/AutoAnimeBot?style=flat-square&color=green)](https://github.com/kaif-00z/AutoAnimeBot/graphs/contributors)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://makeapullrequest.com)
[![License](https://img.shields.io/badge/license-GPLv3-blue)](https://github.com/kaif-00z/AutoAnimeBot/blob/main/LICENSE)   
[![Sparkline](https://stars.medv.io/kaif-00z/AutoAnimeBot.svg)](https://stars.medv.io/kaif-00z/AutoAnimeBot)

## Description Of Latest Update

- Fixed All Torrent Related Issue As Well As Stuck Issue Caused By It.

## Contributing

- Any Sort of Contributions are Welcomed!
- Try To Resove Any Task From ToDo List!

## How to deploy?
<p><a href="https://youtu.be/n1yG6HabW28"> <img src="https://img.shields.io/badge/See%20Video-black?style=for-the-badge&logo=YouTube" width="160""/></a></p>

## Developer Note

- If You Don't Have High End VPS like 8vcpu or 32GiB RAM So Don't Deploy This Bot.
- You Can Customize FFMPEG Code If You Know What You Are Doing.

## Environmental Variable

### REQUIRED VARIABLES

- `BOT_TOKEN` - Get This From @Botfather In Telegram.

- `REDIS_URI` - Get This From redis.com

- `REDIS_PASSWORD` - Get This From redis.com

- `MAIN_CHANNEL` - ID of Channel Where Anime Will Upload.

- `CLOUD_CHANNEL` - ID of Channel Where Samples And Screenshots Of Anime Will Be Uploaded.

- `LOG_CHANNEL` - ID of Channel Where Status Of Proccesses Will Be Shown.

- `OWNER` - ID of Owner.

### OPTIONAL VARIABLES

- `BACKUP_CHANNEL` - ID of Channel Where Anime Will Be Saved As BackUP.

- `THUMBNAIL` - JPG/PNG Link of Thumbnail FIle.

- `FFMPEG` - You Can Set Custom Path Of ffmpeg if u want, default is `ffmpeg`.

- `SEND_SCHEDULE` - `True/False` Send Schedule of Upcoming Anime of that day at 00:30 **IST**, default is `False`.

- `RESTART_EVERDAY` - `True/False` It Will Restart The Bot Everyday At 00:30 **IST**, default is `True`.

## Deployment In VPS

`git clone https://github.com/kaif-00z/AutoAnimeBot.git`

`nano .env` configure env as per [this](https://github.com/kaif-00z/AutoAnimeBot/blob/main/.sample.env) or  using [this](https://github.com/kaif-00z/AutoAnimeBot/blob/main/auto_env_gen.py).

`bash pkg.sh`

`bash run.sh`

## Commands

- `/opt` - Its A Toggle Command Which Will enable and disable compression.

- `/logs` - Its Will Give You Log File.

- `/restart` - To Restart The Bot.

- `/skipul <no.>` - Sometimes When Webhook Got 2 Anime in Same Time, it will skip one, you can use this command to upload that skipped anime. ex - `/skipul 1`.

**Uploading of Ongoing Animes Is Automatic**

## About

- This Bot Is Currently Running In [This Channel](https://telegram.dog/Ongoing_Animes_Flares) .

## Donate

- [Contact me on Telegram](t.me/kaif_00z) if you would like to donate me for my work!
