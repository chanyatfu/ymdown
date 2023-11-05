# ymdown
A utility build on top of ytmusicapi and yt-dlp for easy search-and-download in YouTube Music.

## Installation
`pip install ymdown`

## Usages
`ymdown <input_song_list_path> <output_directory_path>`
The input song list is a plain .txt file containing song names, delimited by newline.

You can change the format by using `-f`, the default format is .mp3.
`ymdown -f wav <input_song_list_path> <output_directory_path>`
