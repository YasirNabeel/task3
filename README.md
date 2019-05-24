# task3

## Requirements
* One Activity
* One RecyclerView
* One CardView show's trip details
* Use MVP
* Use Retrofit
* Take care of UI&UX
* Take care of codes desgin and apply comments
* ***time frame 3 days start from today 24/5/2019***

## please reply to us by sending APK file and a github link to your code to this email "yasserdghx@gmail.com"


### GET tickets Data For One Way
Link:[/api/orders/oneway?from=BGW&to=BEY&data=2019-02-30&adt=1&type=e&chd=0&Infant=0](https://favorite-holiday.herokuapp.com/api/orders/oneway?from=BGW&to=BEY&data=2019-05-30&adt=1&type=e&chd=0&Infant=0)
<br><br>
Method: GET  
<br><br>
params: from =BGW ,to=BEY ,data=2019-05-30,type=e,chd=0 adt=1,Infant=0
<br><br>
example :
<br><br> 
```
https://favorite-holiday.herokuapp.com/api/orders/oneway?from=BGW&to=BEY&data=2019-05-30&adt=1&type=e&chd=0&Infant=0
```
<br><br>
Response:
<br><br>
```
{
        "id": "737778b0-3d23-11e9-82fe-57461c118f6f",
        "price": "550.14",
        "totalDuration": "21 hrs 50 min",
        "stops": 2,
        "airlineLogo": [
            "https://static.flyinstatic.com/img/flights/1x/airline-logos/FZ.png",
            "https://static.flyinstatic.com/img/flights/1x/airline-logos/FZ.png",
            "https://static.flyinstatic.com/img/flights/1x/airline-logos/ME.png"
        ],
        "departingAirportName": [
            "Baghdad Intl."
        ],
        "arrivalAirportName": [
            "Beirut Rafic Hariri International Airport"
        ],
        "logoCover": "https://static.flyinstatic.com/common/themes/v2/img/multiAirline.png",
        "depCityName": [
            "Baghdad",
            "Dubai",
            "Amman"
        ],
        "arrCityName": [
            "Dubai",
            "Amman",
            "Beirut"
        ],
        "depDateAndTime": [
            "2019-03-13T19:35:00",
            "2019-03-14T06:55:00",
            "2019-03-14T15:15:00"
        ],
        "arrDateAndTime": [
            "2019-03-13T19:35:00",
            "2019-03-14T06:55:00",
            "2019-03-14T15:15:00"
        ],
        "airlineName": [
            "Flydubai Airways",
            "Flydubai Airways",
            "Middle East Airlines"
        ],
        "flightNumber": [
            "212",
            "147",
            "315"
        ],
        "layOverTime": [
            "8h:0m",
            "6h:45m",
            "0h:0m"
        ],
        "layOverMinutes": [
            "8h:0m",
            "6h:45m",
            "0h:0m"
        ],
        "layOverCity": [
            "Dubai",
            "Amman",
            "Beirut"
        ],
        "arrAirportName": [
            "Dubai International Airport",
            "Queen Alia International Airport",
            "Beirut Rafic Hariri International Airport"
        ],
        "flightModel": [
            "null",
            "null",
            "null"
        ]
    }
```
