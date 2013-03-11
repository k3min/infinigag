# InfiniGAG API

Right now, the API is very basic, but it should hopefully retrieve what you’re looking for.

I love it when services provide API's. It allows people to play around and make cool apps, and so I did not want to take the fun away from you.

## Resource URL

http://infinigag.eu01.aws.af.cm/2/:section/:id.json

## Parameters

Parameter                 | Description
------------------------- | -----------
**section**<br>*required* | The section to return results from (`hot`, `trending` or `vote`).<br>**Example Values**: `trending`
     **id**<br>*required* | Specifies the page ID to retrieve results from. `0` gives you the most recent page.<br>**Example Values**: `6548695`

## Example Request

**GET** `http://infinigag.eu01.aws.af.cm/2/trending/0.json`

	{
		"data": [{
			"id": 6763189,
			"from": {
				"name": "orhnbyrk",
				"link": "http:\/\/9gag.com\/orhnbyrk"
			},
			"caption": "History",
			"images": {
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6763189_220x145.jpg",
				"normal": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6763189_460s.jpg",
				"large": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6763189_700b.jpg"
			},
			"link": "http:\/\/9gag.com\/gag\/6763189",
			"actions": {
				"like": "http:\/\/9gag.com\/vote\/like\/id\/6763189",
				"dislike": "http:\/\/9gag.com\/vote\/dislike\/id\/6763189",
				"unlike": "http:\/\/9gag.com\/vote\/unlike\/id\/6763189"
			},
			"votes": {
				"count": 0
			}
		}, {
			...
		}, {
			"id": 6761235,
			"from": {
				"name": "ahole666",
				"link": "http:\/\/9gag.com\/ahole666"
			},
			"caption": "Stupidity has reached a new level",
			"images": {
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6761235_220x145_v1.jpg",
				"normal": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6761235_460s_v1.jpg",
				"large": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6761235_700b_v1.jpg"
			},
			"link": "http:\/\/9gag.com\/gag\/6761235",
			"actions": {
				"like": "http:\/\/9gag.com\/vote\/like\/id\/6761235",
				"dislike": "http:\/\/9gag.com\/vote\/dislike\/id\/6761235",
				"unlike": "http:\/\/9gag.com\/vote\/unlike\/id\/6761235"
			},
			"votes": {
				"count": 1832
			}
		}],
		"paging": {
			"next": 6761235
		}
	}
