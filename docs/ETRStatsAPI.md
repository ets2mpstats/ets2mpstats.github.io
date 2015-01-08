# Euro Truck Radio API Documentation

## Get current playing song

You can get the currently playing song by GETing ```ets2mpstats.com/api/etr/nowplaying```, this will return a plaintext response unless you explicitly specify ```application/json``` in your accept headers.

## Get the current listener count

You can get the current listener count GETing ```ets2mpstats.com/api/etr/listenercount``` , this will return a plaintext response unless you explicitly specify ```application/json``` in your accept headers.

## Get the current DJ

You can get the current DJ by GETing ```ets2mpstats.com/api/etr/dj``` , this will return a plaintext response unless you explicitly specify ```application/json``` in your accept headers.

## Make a new request to ETR

You can post a new reqeust to ETR by GETing ```ets2mpstats.com/api/etr/request/<url encoded request>/<url encoded name>```, This will return ```Thank you $name, $song as been requested```. This is primarily targeted for using with bots that have no concept of posting dat. This is primarily targeted for using awth bots that have no concept of posting data.
