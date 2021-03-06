# reddit-dl
![loc](https://tokei.rs/b1/github.com/The-Eye-Team/reddit-dl)
[![license](https://img.shields.io/github/license/The-Eye-Team/reddit-dl.svg)](https://github.com/The-Eye-Team/reddit-dl/blob/master/LICENSE)
[![discord](https://img.shields.io/discord/302796547656253441.svg)](https://discord.gg/the-eye)
[![circleci](https://circleci.com/gh/The-Eye-Team/reddit-dl.svg?style=svg)](https://circleci.com/gh/The-Eye-Team/reddit-dl)
[![goreportcard](https://goreportcard.com/badge/github.com/The-Eye-Team/reddit-dl)](https://goreportcard.com/report/github.com/The-Eye-Team/reddit-dl)

Downloader for submissions to reddit.com. Supports both subreddits and users. Currently does not grab comments.

## Installing
```sh
$ go get -v -u github.com/The-Eye-Team/reddit-dl
```

## Usage
```sh
    --concurrency int   Maximum number of simultaneous downloads. (default 10)
    --save-dir string   Path to a directory to save to.
-r, --subreddit string  The name of a subreddit to archive. (ex. AskReddit, unixporn, CasualConversation, etc.)
-u, --user string       The name of a user to archive. (ex. spez, PoppinKREAM, Shitty_Watercolour, etc.)
```
The flags `-r` and `-u` may be passed multiple times to download many reddits at once.

## License
MIT
