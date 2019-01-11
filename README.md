i3-tall-layout
=====================

Experimental script to open new windows in i3wm using a layout similar to the
Tall layout in XMonad.
The script is based on [i3-alternating-layout](https://github.com/olemartinorg/i3-alternating-layout)
by [olemartinorg](https://github.com/olemartinorg).


Installation
------------

### Ubuntu

```
sudo apt-get install x11-utils python-pip git
sudo pip install i3-py
git clone https://github.com/hanschen/i3-tall-layout
```

And add `tall_layout.py` to your `~/.i3/config` autostart:

```
exec --no-startup-id /path/to/tall_layout.py
```


### Arch Linux

```
git clone https://github.com/hanschen/i3-tall-layout
```

Install `python-i3-py` and `xorg-util-macros`, then add

```
exec --no-startup-id /path/to/tall_layout.py
```

to your `~/.i3/config`.
