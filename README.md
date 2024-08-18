# lm-reborn v0.1

Based on https://github.com/RedRise/lm, updated for new opensubtitles API and with Qt interface.

List movies on your disk.
GPLv3

# MANUAL

## 1. What is it

lm lists movie files, getting information on IMDb, allowing you to:

- display metadata from IMDB in terminal
- or in qt with --qt

- Will scan (not recursively) the current working directory if you don't pass any arguments.

## 2. Usage

You need a ~/.config/osd/osd.conf with your opensubtitles API key. Create it for free. I can't share mine.
The OSD button runs osd : https://github.com/druidamix/Opensubtitles-downloader 
this is why lm reuses its config file, for simplicity

Pass --qt for Qt interface, -l for normal interface. Many other features are broken/never worked too well.
--confirm is half-working, well enough for my purposes.






