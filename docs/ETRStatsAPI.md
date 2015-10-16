# Euro Truck Radio API Documentation

The api supports both HTTP and HTTPS schemes.

**ETR APIs are going to be depricated November 1st**

## Get current playing song

You can get the currently playing song by GETing ```ets2mpstats.com/api/etr/nowplaying/<site>```, this will return a plaintext response unless you explicitly specify ```application/json``` in your accept headers. You must specify ```site``` in your url, currently only ```en``` and ```pl``` is supported.

## Get the current listener count

You can get the current listener count GETing ```ets2mpstats.com/api/etr/listenercount/<site>``` , this will return a plaintext response unless you explicitly specify ```application/json``` in your accept headers. You must specify ```site``` in your url, currently only ```en``` and ```pl``` is supported.

## Get the current DJ

You can get the current DJ by GETing ```ets2mpstats.com/api/etr/dj/<site>``` , this will return a plaintext response unless you explicitly specify ```application/json``` in your accept headers. You must specify ```site``` in your url, currently only ```en``` and ```pl``` is supported.

## Make a new request to ETR

You can post a new reqeust to ETR by GETing ```ets2mpstats.com/api/etr/request/<site>/<url encoded name>/<url encoded request>```, This will return ```Thank you $name, $song as been requested```. This is primarily targeted for using with bots that have no concept of HTTP POST. ```site``` can be either ```en``` or ```pl``` This is primarily targeted for using awth bots that have no concept of posting data.
