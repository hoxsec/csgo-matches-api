# CS:GO MATCHES API

*this is still a work in progress, except more really soon!*


## How To


Upcomming CS:GO matches<br/>
Example: `<a href="https://cdnx.amsterdam/csgo/api/v1/matches/upcomming/">cdnx.amsterdam/csgo/api/v1/matches/upcomming</a>` would return
```
{
    "id": "22073", 
    "matchid": "22824",
    "matchwhen": "2018-05-16 00:50:00.000000",
    "a": "NRG",
    "b": "MVPPK",
    "winner": "",
    "closed": "0",
    "event": "ESL",
    "format": "3" 
}
```

Finished CS:GO matches<br/>
Example: `<a href="https://cdnx.amsterdam/csgo/api/v1/matches/finished/">cdnx.amsterdam/csgo/api/v1/matches/finished</a>` would return
```
{
    "id": "22072",
    "matchid": "22822",
    "matchwhen": "2018-05-15 21:20:00.000000",
    "a": "Cloud9",
    "b": "Sharks",
    "winner": "a",
    "closed": "1",
    "event": "ESL",
    "format": "3"
}
```


## Please Note
As I stated before this is still a work in progress. However, feel free to edit and commit new changes to improve the quality of the API. You may also take the code, work with it, and even profit from it as long as some credit is clearly given. 
