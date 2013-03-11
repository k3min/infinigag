# InfiniGAG API

Right now, the API is very basic, but it should hopefully retrieve what you’re looking for.

I love it when services provide API's. It allows people to play around and make cool apps, and so I did not want to take the fun away from you.

## Resource URL

http://infinigag.eu01.aws.af.cm/2/:section/:id.json

## Parameters

Parameter                 | Description
------------------------- | -----------
**section**<br>*required* | The section to return results from.<br>**Example Values**: `trending`
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
			"id": 6761033,
			"from": {
				"name": "patri011",
				"link": "http:\/\/9gag.com\/patri011"
			},
			"caption": "You can't kill this guy",
			"images": {
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/img\/nsfw-mask_v2.jpg",
				"normal": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/img\/nsfw-mask_v2.jpg",
				"large": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/img\/nsfw-mask_v2.jpg"
			},
			"link": "http:\/\/9gag.com\/gag\/6761033",
			"actions": {
				"like": "http:\/\/9gag.com\/vote\/like\/id\/6761033",
				"dislike": "http:\/\/9gag.com\/vote\/dislike\/id\/6761033",
				"unlike": "http:\/\/9gag.com\/vote\/unlike\/id\/6761033"
			},
			"votes": {
				"count": 0
			}
		}, {
			"id": 6762482,
			"from": {
				"name": "33558899",
				"link": "http:\/\/9gag.com\/33558899"
			},
			"caption": "Stay away monday",
			"images": {
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6762482_220x145_v1.jpg",
				"normal": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6762482_460s_v1.jpg",
				"large": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6762482_700b_v1.jpg"
			},
			"link": "http:\/\/9gag.com\/gag\/6762482",
			"actions": {
				"like": "http:\/\/9gag.com\/vote\/like\/id\/6762482",
				"dislike": "http:\/\/9gag.com\/vote\/dislike\/id\/6762482",
				"unlike": "http:\/\/9gag.com\/vote\/unlike\/id\/6762482"
			},
			"votes": {
				"count": 0
			}
		}, {
			"id": 6763417,
			"from": {
				"name": "belggleb",
				"link": "http:\/\/9gag.com\/belggleb"
			},
			"caption": "Warm kitty , soft kitty , little bar of fur",
			"images": {
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6763417_220x145_v2.jpg",
				"normal": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6763417_460s_v2.jpg",
				"large": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6763417_700b_v2.jpg"
			},
			"link": "http:\/\/9gag.com\/gag\/6763417",
			"actions": {
				"like": "http:\/\/9gag.com\/vote\/like\/id\/6763417",
				"dislike": "http:\/\/9gag.com\/vote\/dislike\/id\/6763417",
				"unlike": "http:\/\/9gag.com\/vote\/unlike\/id\/6763417"
			},
			"votes": {
				"count": 761
			}
		}, {
			"id": 6762459,
			"from": {
				"name": "jimmyswinningma",
				"link": "http:\/\/9gag.com\/jimmyswinningma"
			},
			"caption": "London baby!",
			"images": {
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6762459_220x145.jpg",
				"normal": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6762459_460s.jpg",
				"large": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6762459_700b.jpg"
			},
			"link": "http:\/\/9gag.com\/gag\/6762459",
			"actions": {
				"like": "http:\/\/9gag.com\/vote\/like\/id\/6762459",
				"dislike": "http:\/\/9gag.com\/vote\/dislike\/id\/6762459",
				"unlike": "http:\/\/9gag.com\/vote\/unlike\/id\/6762459"
			},
			"votes": {
				"count": 0
			}
		}, {
			"id": 6760036,
			"from": {
				"name": "maelastam",
				"link": "http:\/\/9gag.com\/maelastam"
			},
			"caption": "Wtf math?",
			"images": {
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6760036_220x145.jpg",
				"normal": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6760036_460s.jpg",
				"large": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6760036_700b.jpg"
			},
			"link": "http:\/\/9gag.com\/gag\/6760036",
			"actions": {
				"like": "http:\/\/9gag.com\/vote\/like\/id\/6760036",
				"dislike": "http:\/\/9gag.com\/vote\/dislike\/id\/6760036",
				"unlike": "http:\/\/9gag.com\/vote\/unlike\/id\/6760036"
			},
			"votes": {
				"count": 0
			}
		}, {
			"id": 6763322,
			"from": {
				"name": "leonardbankmeme",
				"link": "http:\/\/9gag.com\/leonardbankmeme"
			},
			"caption": "My friend texted me that this morning",
			"images": {
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6763322_220x145.jpg",
				"normal": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6763322_460s.jpg",
				"large": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6763322_700b.jpg"
			},
			"link": "http:\/\/9gag.com\/gag\/6763322",
			"actions": {
				"like": "http:\/\/9gag.com\/vote\/like\/id\/6763322",
				"dislike": "http:\/\/9gag.com\/vote\/dislike\/id\/6763322",
				"unlike": "http:\/\/9gag.com\/vote\/unlike\/id\/6763322"
			},
			"votes": {
				"count": 1200
			}
		}, {
			"id": 6764264,
			"from": {
				"name": "thomaska231",
				"link": "http:\/\/9gag.com\/thomaska231"
			},
			"caption": "Kimi Raikkonen",
			"images": {
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6764264_220x145.jpg",
				"normal": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6764264_460s.jpg",
				"large": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6764264_700b.jpg"
			},
			"link": "http:\/\/9gag.com\/gag\/6764264",
			"actions": {
				"like": "http:\/\/9gag.com\/vote\/like\/id\/6764264",
				"dislike": "http:\/\/9gag.com\/vote\/dislike\/id\/6764264",
				"unlike": "http:\/\/9gag.com\/vote\/unlike\/id\/6764264"
			},
			"votes": {
				"count": 1183
			}
		}, {
			"id": 6763415,
			"from": {
				"name": "charlesthebug",
				"link": "http:\/\/9gag.com\/charlesthebug"
			},
			"caption": "Gift my girlfriend gave me for my birthday",
			"images": {
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6763415_220x145.jpg",
				"normal": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6763415_460s.jpg",
				"large": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6763415_700b.jpg"
			},
			"link": "http:\/\/9gag.com\/gag\/6763415",
			"actions": {
				"like": "http:\/\/9gag.com\/vote\/like\/id\/6763415",
				"dislike": "http:\/\/9gag.com\/vote\/dislike\/id\/6763415",
				"unlike": "http:\/\/9gag.com\/vote\/unlike\/id\/6763415"
			},
			"votes": {
				"count": 1246
			}
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
