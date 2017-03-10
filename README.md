# VpV
Search for videos in YouTube and play them directly in VLC

## Requirements
* GNU Linux
* wget (out of the box in almost all distros)
* sed (out of the box in almost all distros)
* VLC (if you haven't it installed you should)

## How to "install"
Just download [vpv](../blob/master/vpv) script file and place it somewhere.

If you want to have a launcher you can also download [vpv.desktop](../blob/master/vpv.desktop).

## How to use
Just call it on command line like this:
```bash
./vpv "shaun the sheep"
```
to play all links in order
or
```bash
./vpv --random "shaun the sheep"
```
to play them at random

You can join more then one search in the playlist, like this:
```bash
./vpv --random "shaun the sheep" "pink panther"
```
Search results are cached for 5 days in a `.vpv/` directory (in the same directory the script is).


`vpv.desktop` file is just a (working) example. Change it at your need.
You can install it on you launch bar. If you right click it, you can choose which ~~cartoon~~ videos to search and play.

## Motivation
Just wrote this script to quickly play some cartoons for my kid. As a bonus I got videos without ads...

## Where does this name came from?
It's just from "Vídeos pró Vasco", which is something like "Videos for Vasco". Vasco is my son.

## Notice
This script was written just as a proof of concept. It should not be used for any other propose then study the involved technologies.
It searches YouTube using common requests to it's search page. It doesn't use it's API. It hasn't any app key.
I'm not sure if "they" live happy with that... use it at your own risk. Don't abuse...
