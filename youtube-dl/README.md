youtube-dl
==========

[`youtube-dl`][1] is a small command-line program to download videos from
<https://www.youtube.com/> and a few more sites.

## Tutorial

```
# create a alias
$ alias yt='docker run --rm -v `pwd`:/data vimagick/youtube-dl'

# list all formats
$ yt -F nVjsGKrE6E8

# download it
$ yt nVjsGKrE6E8

# play it
$ vlc *-nVjsGKrE6E8.mp4
```

[1]: https://rg3.github.io/youtube-dl/