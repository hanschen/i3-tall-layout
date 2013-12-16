i3-alternating-layout
=====================

Scripts to open new windows in i3wm using alternating layouts (splith/splitv) for each new window. These scripts were made for [/u/ke7ofi](http://www.reddit.com/user/ke7ofi) after she/he asked a question on how to do this [you can read the question here](http://www.reddit.com/r/i3wm/comments/1sdc39/alternating_horizontal_and_vertical_splitting/).

Installation
---------------

```
pip install i3-py
git clone https://github.com/olemartinorg/i3-alternating-layout
```
And add ```alternating_layouts.sh``` to your ```~/.i3/config``` autostart:
```
exec --no-startup-id /path/to/alternating_layouts.sh
```
