step by step
```
$ sudo apt install mpd ncmpcpp
```
configure  mpd
```
$ mkdir -p ~/.mpd/playlists
$ touch ~/.mpd/mpd.conf
```
<a href="https://github.com/skandyns/mpd/blob/master/mpd.conf" target="_blank"><button class="button-link button-small pure-button">mpd.conf (pulseaudio)</button></a>
```
$ nano ~/.mpd/mpd.conf
```
configure ncmpcpp
```
$ mkdir ~/.ncmpcpp
$ touch ~/.ncmpcpp/config
```
<a href="https://github.com/skandyns/ncmpcpp/blob/master/config" target="_blank"><button class="button-link button-small pure-button">config</button></a>
```
$ nano ~/.ncmpcpp/config
```
disable automatic mpd startup at login (optional)
```
$ sudo systemctl disable mpd
$ sudo rm /etc/xdg/autostart/mpd.desktop
```
start
```
$ ncmpcpp
```
or (mpd disabled)
```
$ mpd
$ ncmpcpp
```
key u - update database

<img src="https://skandyns.github.io/img/ncmpcpp.png"/>

keys
```
1 - playlist
2 - browse
3 - search engine
4 - media library
5 - playlist editor
6 - tag editor
7 - outputs
8 - music visualizer
p - play/pause
s - stop
c - clear playlist
q - quit
> - next song
< - previous track
\ - classic and alternative view
l - song lyrics for current song
= - clock
+ - increase volume 2%
- - decrease volume 2%
```
<a href="https://github.com/skandyns/ncmpcpp/blob/master/ncmpcpp.png" target="_blank"><button class="button-link button-small pure-button">my ncmpcpp</button></a>
