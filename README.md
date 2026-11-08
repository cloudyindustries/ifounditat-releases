# I Found It At releases

`binaries.json` names the tested version of each helper program the app
keeps in its bin folder: yt-dlp, gallery-dl, ffmpeg, python and ollama.
Every running copy of the app reads this file twice a day and installs
what differs. Change a version here only after the nightly checks have
passed with it.

The app itself lives in a private repository. This one holds only what a
running install has to read without a login.
