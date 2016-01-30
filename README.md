# InfiniGAG API

Right now, the API is very basic, but it should hopefully retrieve what you're looking for.

I love it when services provide API's. It allows people to play around and make cool apps, and so I did not want to take the fun away from you.

## Resource URL

- http://infinigag.k3min.eu/:section/:id

## Parameters

Parameter                 | Description
------------------------- | -----------
**section**<br>*required* | The section to return results from (`hot`, `trending` or `fresh`).<br>**Example Values**: `trending`
     **id**<br>*optional* | Specifies the page ID to retrieve results from.<br>**Example Values**: `V8eFpqG`

## Example Request

**GET** [`http://infinigag.k3min.eu/trending`](http://infinigag.k3min.eu/trending)

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
			},
			...
		],
		"paging": {
			"next": "V8eFpqG"
		}
	}

## Uses

- [9GAG (Unofficial)](http://apps.microsoft.com/windows/app/9gag-unofficial/846be2db-a72a-47b7-9507-e81ce0d2dd5b)
- [GagBook](http://github.com/dicksonleong/GagBook)
