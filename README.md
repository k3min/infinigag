# InfiniGAG API

Right now, the API is very basic, but it should hopefully retrieve what you're looking for.

I love it when services provide API's. It allows people to play around and make cool apps, and so I did not want to take the fun away from you.

## API

- [GET /:section/:id](#get-sectionid)
- [POST /token](#post-token)
- [POST /vote/:type/:id](#post-votetypeid)

### GET /:section/:id

#### Resource URL

`http://infinigag.k3min.eu/:section/:id`

#### Parameters

Parameter                      | Description
---------                      | -----------
     **section**<br>*required* | The section (or subsection) to return results from (`hot`, `trending`, `fresh`, etc.)<br>**Example Values**: `design/fresh`
          **id**<br>*optional* | Specifies the page ID to retrieve results from.<br>**Example Values**: `V8eFpqG`
**access_token**<br>*optional* | Token obtained from [POST /token](#post-token).<br>**Example Values**: `9125faf1dda6c7d3fe5cc5574e5ff79158208918955275753b4e1d58efecdf9d`

#### Example Request

##### Request URL:

GET `http://infinigag.k3min.eu/design/fresh`

##### Response:

```json
{
	"status": 200,
	"message": "OK",
	"data": [
		{
			"id": "EyVtjpq",
			"caption": "Example",
			"images": {
				"small": "http:\/\/img-9gag-fun.9cache.com\/photo\/EyVtjpq_220x145.jpg",
				"cover": "http:\/\/img-9gag-fun.9cache.com\/photo\/EyVtjpq_460c.jpg",
				"normal": "http:\/\/img-9gag-fun.9cache.com\/photo\/EyVtjpq_460s.jpg",
				"large": "http:\/\/img-9gag-fun.9cache.com\/photo\/EyVtjpq_700b.jpg"
			},
			"media": {
				"mp4": "http:\/\/img-9gag-fun.9cache.com\/photo\/EyVtjpq_460sv.mp4",
				"webm": "http:\/\/img-9gag-fun.9cache.com\/photo\/EyVtjpq_460svwm.webm"
			},
			"link": "http:\/\/9gag.com\/gag\/EyVtjpq",
			"votes": {
				"count": 0
			},
			"comments": {
				"count": 0
			}
		}
	],
	"paging": {
		"next": "V8eFpqG"
	}
}
```

### POST /token

#### Resource URL

`http://infinigag.k3min.eu/token`

#### Parameters

Parameter                  | Description
---------                  | -----------
**username**<br>*required* | End-user username.<br>**Example Values**: `hi@k3min.eu`
**password**<br>*required* | End-user password.<br>**Example Values**: `secret`

#### Example Request

##### Request URL:

POST `http://infinigag.k3min.eu/token`

##### Request POST Body:

`username=hi%40k3min.eu&password=secret`

##### Response:

```json
{
	"status": 200,
	"message": "OK",
	"access_token": "9125faf1dda6c7d3fe5cc5574e5ff79158208918955275753b4e1d58efecdf9d"
}
```

### POST /vote/:type/:id

#### Resource URL

`http://infinigag.k3min.eu/vote/:type/:id`

#### Parameters

Parameter                      | Description
---------                      | -----------
        **type**<br>*required* | Vote type (`like`, `dislike` or `unlike`).<br>**Example Values**: `like`
          **id**<br>*required* | The gag ID.<br>**Example Values**: `EyVtjpq`
**access_token**<br>*required* | Token obtained from [POST /token](#post-token).<br>**Example Values**: `9125faf1dda6c7d3fe5cc5574e5ff79158208918955275753b4e1d58efecdf9d`

#### Example Request

##### Request URL:

POST `http://infinigag.k3min.eu/vote/like/EyVtjpq?access_token=9125faf1dda6c7d3fe5cc5574e5ff79158208918955275753b4e1d58efecdf9d`

##### Request POST Body:

*N/A*

##### Response:

```json
{
	"status": 200,
	"message": "OK",
	"id": "EyVtjpq",
	"score": 1
}
```

## Uses

- [stormzhang/9GAG](http://github.com/stormzhang/9GAG)
- [Mixiaoxiao/9GAG](http://github.com/Mixiaoxiao/9GAG)
- [dicksonleong/GagBook](http://github.com/dicksonleong/GagBook)
- [vinceyuan/Demo9GAG](http://github.com/vinceyuan/Demo9GAG)
