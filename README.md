# shpot (shell spotify)

Control spotify from bash and view current song

## Dependencies

* [D-Bus](https://www.freedesktop.org/wiki/Software/dbus/)

## Install

```sh
sudo sh -c "curl https://raw.githubusercontent.com/kubejm/shpot/master/shpot \
       -o /usr/local/bin/shpot && \
       chmod +x /usr/local/bin/shpot"
```

## Usage

```sh
usage: shpot [command]

commands:
  play     -- resume playing
  stop     -- stop playing
  next     -- play next song
  previous -- play previous song
  current  -- print song playing
```
