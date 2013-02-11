# InfiniGAG API

I love it when services provide API's. It allows people to play around and make cool apps, and so I did not want to take the fun away from you.

## Resource URL

http://infinigag.eu01.aws.af.cm/

## Parameters

Parameter   | Description                                | Example Values | Default Values
----------- | ------------------------------------------ | -------------- | --------------
**section** | The section to return results from.        | *hot*          | *trending*
   **page** | Specifies the page of results to retrieve. | *6548695*      | Newest page

## Example Request

**GET** http://infinigag.eu01.aws.af.cm/?section=trending&page=6548695

	{
		"attributes": {
			"url": "http:\/\/9gag.com\/trending\/id\/6548695",
			"next": 6550985
		},
		"images": [{
			"id": 6553659,
			"title": "Internet Bullying",
			"url": "http:\/\/9gag.com\/gag\/6553659",
			"votes": 2446,
			"image": {
				"thumb": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6553659_220x145.jpg",
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6553659_460s.jpg",
				"big": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6553659_700b.jpg"
			}
		}, {
			"id": 6551593,
			"title": "How I felt when my gf asked if her butt had gotten bigger",
			"url": "http:\/\/9gag.com\/gag\/6551593",
			"votes": 1924,
			"image": {
				"thumb": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6551593_220x145.jpg",
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6551593_460s.jpg",
				"big": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6551593_700b.jpg"
			}
		}, {
			"id": 6549585,
			"title": "Silly prince",
			"url": "http:\/\/9gag.com\/gag\/6549585",
			"votes": 3320,
			"image": {
				"thumb": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6549585_220x145.jpg",
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6549585_460s.jpg",
				"big": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6549585_700b.jpg"
			}
		}, {
			"id": 6553650,
			"title": "Found a dead snowman.",
			"url": "http:\/\/9gag.com\/gag\/6553650",
			"votes": 1931,
			"image": {
				"thumb": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6553650_220x145.jpg",
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6553650_460s.jpg",
				"big": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6553650_700b.jpg"
			}
		}, {
			"id": 6542709,
			"title": "Nobody's home...",
			"url": "http:\/\/9gag.com\/gag\/6542709",
			"votes": 2409,
			"image": {
				"thumb": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6542709_220x145.jpg",
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6542709_460s.jpg",
				"big": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6542709_700b.jpg"
			}
		}, {
			"id": 6551676,
			"title": "I FOUND HER",
			"url": "http:\/\/9gag.com\/gag\/6551676",
			"votes": 3381,
			"image": {
				"thumb": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6551676_220x145.jpg",
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6551676_460s.jpg",
				"big": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6551676_700b.jpg"
			}
		}, {
			"id": 6553649,
			"title": "Ellen DeGeneres gets a good look at Katy Perry.",
			"url": "http:\/\/9gag.com\/gag\/6553649",
			"votes": 3647,
			"image": {
				"thumb": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6553649_220x145.jpg",
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6553649_460s.jpg",
				"big": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6553649_700b.jpg"
			}
		}, {
			"id": 6551257,
			"title": "The best calendar EVER!",
			"url": "http:\/\/9gag.com\/gag\/6551257",
			"votes": 2420,
			"image": {
				"thumb": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6551257_220x145.jpg",
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6551257_460s.jpg",
				"big": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6551257_700b.jpg"
			}
		}, {
			"id": 6549498,
			"title": "Worship this guy",
			"url": "http:\/\/9gag.com\/gag\/6549498",
			"votes": 3015,
			"image": {
				"thumb": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6549498_220x145_v1.jpg",
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6549498_460s_v1.jpg",
				"big": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6549498_700b_v1.jpg"
			}
		}, {
			"id": 6550985,
			"title": "Me before exam",
			"url": "http:\/\/9gag.com\/gag\/6550985",
			"votes": 3318,
			"image": {
				"thumb": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6550985_220x145.jpg",
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6550985_460s.jpg",
				"big": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6550985_700b.jpg"
			}
		}]
	}
