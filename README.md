# SoundCloud-dl

Easily download any SoundCloud track even if a download link is not provided.

## Requirements

- This script uses **Python 3**.

- You will also need to have a **Client ID from SoundCloud.** To receive one you need to create an app [here](http://soundcloud.com/you/apps/new). Once you have created an app and received your Client ID, download the source code and edit the code so your Client ID is used along with the folder location of where you want the files saved to.

    › _Unfortunately SoundCloud for Developers **is not accepting new registrations** currently (August/2020)._

## Usage

First make:
  
    pip install -r requirements.txt

Then from the Terminal run the following:
  
    python3 soundcloud_dl.py [soundcloud url]

  Only one SoundCloud url can be provided at a time. If you wish to download more tracks, simply run the script with a different url!

## In Development

- [x] Check if link provided is a valid SoundCloud link
- [x] Add proper mp3 tags and artwork that is provided via SoundCloud
- [x] Allow for a playlist to be downloaded
- [x] Progress bar of download

----

_This was developed entirely **for educational** purposes and I am not responsible for anyone that chooses to use this._