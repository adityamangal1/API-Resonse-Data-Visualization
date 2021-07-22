
![images](https://challengepost-s3-challengepost.netdna-ssl.com/photos/production/challenge_photos/001/600/320/datas/full_width.png)

## Introduction
The Star Wars API! This documentation should help you familiarise yourself with the resources available and how to consume them with HTTP requests. If you're after a native helper library then I suggest you scroll down and check out what's available. Read through the getting started section before you dive in. Most of your problems should be solved just by reading through it.

```
http swapi.dev/api/people
```

## Rate limiting
Swapi has rate limiting to prevent malicious abuse (as if anyone would abuse Star Wars data!) and to make sure our service can handle a potentially large amount of traffic. Rate limiting is done via IP address and is currently limited to 10,000 API requests per day. This is enough to request all the data on the website at least ten times over. There should be no reason for hitting the rate limit.

## Screenshot 🛠️

![Screenshot (347)](https://user-images.githubusercontent.com/68494604/126661578-676eadbb-f8b2-45a0-a719-14d395547e0a.png)



## Authentication
Swapi is a completely open API. No authentication is required to query and get data. This also means that we've limited what you can do to just GET-ing the data. If you find a mistake in the data, then tweet the author or email him.


## JSON Schema
All resources support JSON Schema. Making a request to /API/<resource>/schema will give you the details of that resource. This will allow you to programmatically inspect the attributes of that resource and their types.

## Encodings
SWAPI provides two encodings for you to render the data with:


## JSON
JSON is the standard data format provided by SWAPI by default.


<p align="center">
  <img alt="Sloan, the sloth mascot" width="250px" src="https://user-images.githubusercontent.com/68494604/120436157-39627380-c39c-11eb-89cf-58089fb1032d.gif">
   <br>
</p>
