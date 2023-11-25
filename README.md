# Rime Input Method Engine

First of all, I love Rime.

Here is a wubi table I modified from jidian-wubi.

If you want to type simplified and output tranditional words, please install `opencc`.

## Install Rime for IBus

```
sudo apt install ibus-rime opencc

mkdir -p ~/.config/ibus/rime
cp -r * ~/.config/ibus/rime/
```

## Install Rime for Fcitx

```
sudo apt install fcitx-rime opencc

mkdir -p ~/.local/share/fcitx5/rime
cp -r * ~/.local/share/fcitx5/rime/
```

## Restart IBus Rime

```
ibus-daemon -xdr
```

## Rime on MacOS

```
brew cask install squirrel

cp -r * ~/Library/Rime/
```

Avoid period with double-space: `System -> Keyboard -> Text -> unselect Add period with double-space`

## Rime on Windows

```
cp -r * /mnt/c/Users/zhiwei/AppData/Roaming/Rime/
```

## References

* 雾凇拼音: https://github.com/iDvel/rime-ice
* 极点五笔：https://github.com/KyleBing/rime-wubi86-jidian
