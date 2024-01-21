#+title: Youtube Dowwnload script that will automatically orginize your downloads into a folder structure according to Video and Music Genres, Music Artist, Music Video types (Concerts, Live...) etc.

* Description
:PROPERTIES:
:ID:       280135a0-2cff-4e93-8679-7d1a6d56b7b2
:END:
After many years of using ytdl I managed to come up with this simple script that will perfectly orginize all of my downloads into a desired folder structure. This is an alternative to software like youtube archivist, tubesync and the latest one I started using ytdl-sub which provides much more advanced usage of yt-dlp, but for noobs or just a simple download of youtube content this script is perfect. Enjoy!

* Before running
:PROPERTIES:
:ID:       1c609bfc-4e6e-4fd8-8129-1b722fd7cda8
:END:
Before installing, make sure you have:
[[https://github.com/yt-dlp/yt-dlp]YT-DLP]


* To install
:PROPERTIES:
:ID:       a0417c61-3fd8-40a0-9385-6c5aaed37337
:END:

#+begin_src bash
$mkdir /home/$USER/Youtube
$ cd Youtube
$ git clone https://github.com/RogueGhost93/youtube-download
$ chmod +x ytdl.sh


* Usage
:PROPERTIES:
:ID:       9e995141-b386-4962-9842-7209bedc5651
:END:
# Open ytdl.sh in order to define your channels you would like to download.
# You can also change any variable in ytdl.sh file such as download or config location.
$ cd /home/$USER/Youtube
$ ./ytdl.sh
#+end_src
