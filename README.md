# YouTube Playlist Mass-Uploader

Add YouTube videos to your playlist by id.

## Dependencies


* Python 2.x
* `easy_install httplib2`
* `easy_install ConfigParser`
* `easy_install argparse`
* `easy_install logging`
* `easy_install --upgrade google-api-python-client`

## Usage

- Register your app on [Google Developers Console](https://developers.google.com/youtube/registering_an_application) and choose *installed application*
- Download secrets JSON file from Google Developers Console and put it in `etc/client_secrets.json`
- Configure target YouTube playlist ID in `etc/youtube-playlist.conf`
- Create a list of YouTube video IDs in `input/videos.txt`: one video ID per line
- Run `./youtube-playlist`
- Enjoy!

## License

This software is released under the [MIT License](http://opensource.org/licenses/MIT).

- Copyright (c) 2014 vst42
