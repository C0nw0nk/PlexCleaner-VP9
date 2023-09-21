# PlexCleaner-VP9
VP9 Encode your entire plex/emby library

This will check to see if media is already VP9 encoded if it is it will skip that file so you don't have to worry about loss of quality / editing already VP9 encoded media files.

# Usage

Run `VP9_LargestFileFirst.cmd` and enjoy It will start with the largest video files in your library want to claim back that disk space as fast as we can after all :)


# How to change settings

Edit `plexcleaner.json` this line specificly https://github.com/C0nw0nk/PlexCleaner-VP9/blob/main/win-x64/PlexCleaner.json#L141

For example you will see by default `"Video": "VP9_10bit` i use CPU for VP9 encoding you can change it to AMD VAAPI CPU what ever you prefer.

Here is the list of options

## CPU Encoding

```
VP9
VP9_10bit
```

## Nvidia GPU Encoding

```
N/A nothing yet
```

## AMD GPU Encoding

```
N/A nothing yet
```
