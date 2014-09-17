# Euro Truck Radio API Documentation

## Get current playing song

You can get the currently playing song by GETing ```api.ets2mpstats.com/etr/nowplaying``` or ```api.ets2mpstats.com/etr/nowplaying/text```, this will return respectively a JSON reply or a plain text reply.

## Get the Top played tracks

You can get the top n tracks where n is a number between 1 and 100 by GETing ```api.ets2.mpstats.com/etr/top/n``` or get only the top played track by getting ```api.ets2.mpstats.com/etr/top```. This API call *only* replies as JSON at the moment.