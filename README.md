# Conky configuration wth calendar and current weather #

## Install ##

Copy the files to `~/.config/conky`

## Configure ##

Edit `weather.lua` and set the city id, api key and cf variables

In order for "now playing" information to show up, you need to use mpd.

## Run ##

conky -c ~/.config/conky.config

## Screenshot ##

![calendar and weather information on a black background](screenshot.png "Calendar shows the current day and weather is the current conditions")
