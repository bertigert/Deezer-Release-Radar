# Deezer-Release-Radar
A script to view new releases of artist you follow, not the ones Deezer thinks you like. Deezers Release Playlist does not feature small artists and features artists you heard 2 times. This radar features only all artists you follow. Designed for the Desktop Browser version, supports both dark and white mode. Tested on Chrome/Firefox with Violentmonkey/Tampermonkey and Desktop Application on Windows.\

![image](https://github.com/user-attachments/assets/8c2ea203-a649-42ca-950d-f6447af104af)

## Now also supported for the desktop application
Thanks to the [DeezMod](https://github.com/bababoi-2/DeezMod) project we can now easily use scripts within the desktop application. You can download the version for that script [here](https://github.com/bababoi-2/DeezMod/blob/main/plugins/release_radar.js)

## Note
Due to a bug in the Deezer API, some artists are bugged and dont return releases when having the "Features" checkbox enabled. This will hopefully be fixed on the server side, if not I will implement a fix manually, which would drastically reduce performance though.

## Functionality
- Adds a menu item right besides the notifications icon
- Allows you to limit the amount of releases by amount or age (highly recommended as the higher the age limit, the more requests we need to make)
- Lets you choose if you want to include Features, Singles, EPs, Albums
- Allows you to add new songs to a specified playlist (by ID), features a blacklist using regex to filter out songs with a specific name
- Allows you to seperate/hide Upcoming Releases
- Allows you to blacklist releases using regex
- Allows you to blacklist artists using their ID
- Allows you to open the releases in the desktop app
- Highly configurable
- Scans for new artists every day, songs on deezer get released at midnight UTC
- Allows you to play songs directly from within the radar, view the cover images in 1920x1920 resolution, supports ajax loading of releases
- Note: When launching for the first time, all songs are considered new

## Links
[Greazyfork](https://greasyfork.org/en/scripts/510955-deezer-release-radar)\
[GitHub](https://github.com/bababoi-2/Deezer-Release-Radar)

## Thanks
https://github.com/doubouil for helping me improve this script
