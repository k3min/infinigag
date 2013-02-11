# InfiniGAG API

Right now, the API is very basic, but it should hopefully retrieve what you’re looking for.

I love it when services provide API's. It allows people to play around and make cool apps, and so I did not want to take the fun away from you.

## Resource URL

http://infinigag.eu01.aws.af.cm/

## Parameters

Parameter   | Description                                | Example Values | Default Values
----------- | ------------------------------------------ | -------------- | --------------
**section** | The section to return results from.        | *hot*          | *trending*
   **page** | Specifies the page of results to retrieve. | *6548695*      | Newest page

## Example Request

**GET** http://infinigag.eu01.aws.af.cm/?section=hot

	{
		"attributes": {
			"url": "http:\/\/9gag.com\/hot\/",
			"next": 6514942
		},
		"images": [{
			"id": 6545283,
			"title": "Teens Next Door",
			"url": "http:\/\/9gag.com\/gag\/6545283",
			"votes": 10876,
			"image": {
				"thumb": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6545283_220x145.jpg",
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6545283_460s.jpg",
				"big": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6545283_700b.jpg"
			}
		}, {
			"id": 6541691,
			"title": "Holland is below sea level...",
			"url": "http:\/\/9gag.com\/gag\/6541691",
			"votes": 2831,
			"image": {
				"thumb": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6541691_220x145.jpg",
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6541691_460s.jpg",
				"big": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6541691_700b.jpg"
			}
		}, {
			"id": 6545866,
			"title": "This is how Chuck Norris gets to\ufeff work in the morning",
			"url": "http:\/\/9gag.com\/gag\/6545866",
			"votes": 5084,
			"image": {
				"thumb": "http:\/\/img.youtube.com\/vi\/FT8tpGHa6Y4\/0.jpg",
				"small": "http:\/\/img.youtube.com\/vi\/FT8tpGHa6Y4\/0.jpg",
				"big": "http:\/\/img.youtube.com\/vi\/FT8tpGHa6Y4\/0.jpg"
			}
		}, {
			"id": 6542187,
			"title": "Doesn't matter free foot",
			"url": "http:\/\/9gag.com\/gag\/6542187",
			"votes": 15279,
			"image": {
				"thumb": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6542187_220x145_v1.jpg",
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6542187_460s_v1.jpg",
				"big": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6542187_700b_v1.jpg"
			}
		}, {
			"id": 6294487,
			"title": "People who care about Facebook relationships",
			"url": "http:\/\/9gag.com\/gag\/6294487",
			"votes": 11284,
			"image": {
				"thumb": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6294487_220x145.jpg",
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6294487_460s.jpg",
				"big": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6294487_700b.jpg"
			}
		}, {
			"id": 6507476,
			"title": "Housekeeping loves this",
			"url": "http:\/\/9gag.com\/gag\/6507476",
			"votes": 13628,
			"image": {
				"thumb": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6507476_220x145.jpg",
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6507476_460s.jpg",
				"big": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6507476_700b.jpg"
			}
		}, {
			"id": 6534144,
			"title": "Stores know what men go through!",
			"url": "http:\/\/9gag.com\/gag\/6534144",
			"votes": 11634,
			"image": {
				"thumb": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6534144_220x145.jpg",
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6534144_460s.jpg",
				"big": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6534144_700b.jpg"
			}
		}, {
			"id": 6515046,
			"title": "Trust me! I m an engineer!",
			"url": "http:\/\/9gag.com\/gag\/6515046",
			"votes": 8142,
			"image": {
				"thumb": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6515046_220x145.jpg",
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6515046_460s.jpg",
				"big": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6515046_700b.jpg"
			}
		}, {
			"id": 6532555,
			"title": "The King",
			"url": "http:\/\/9gag.com\/gag\/6532555",
			"votes": 12767,
			"image": {
				"thumb": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6532555_220x145.jpg",
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6532555_460s.jpg",
				"big": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6532555_700b.jpg"
			}
		}, {
			"id": 6514942,
			"title": "Revenge after million years",
			"url": "http:\/\/9gag.com\/gag\/6514942",
			"votes": 13298,
			"image": {
				"thumb": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6514942_220x145.jpg",
				"small": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6514942_460s.jpg",
				"big": "http:\/\/d24w6bsrhbeh9d.cloudfront.net\/photo\/6514942_700b.jpg"
			}
		}]
	}
