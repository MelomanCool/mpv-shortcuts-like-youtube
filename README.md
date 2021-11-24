# mpv-shortcuts-like-youtube

Add to `~/.config/mpv/input.conf`:

```
RIGHT osd-msg seek  5 exact
LEFT  osd-msg seek -5 exact
UP   add volume  5
DOWN add volume -5

d osd-msg seek  5 exact
a osd-msg seek -5 exact
w add volume  5
s add volume -5

0 seek 00 absolute-percent
1 seek 10 absolute-percent
2 seek 20 absolute-percent
3 seek 30 absolute-percent
4 seek 40 absolute-percent
5 seek 50 absolute-percent
6 seek 60 absolute-percent
7 seek 70 absolute-percent
8 seek 80 absolute-percent
9 seek 90 absolute-percent

j osd-msg seek -10 exact
k cycle pause
l osd-msg seek  10 exact
```
