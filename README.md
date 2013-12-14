InfiniGAG API
=============

Right now, the API is very basic, but it should hopefully retrieve what you're looking for.

I love it when services provide API's. It allows people to play around and make cool apps, and so I did not want to take the fun away from you.

Resource URL
------------

http://infinigag.eu01.aws.af.cm/:section/:id

Parameters
----------

Parameter                 | Description
------------------------- | -----------
**section**<br>*required* | The section to return results from (`hot`, `trending` or `vote`/`fresh`).<br>**Example Values**: `trending`
     **id**<br>*required* | Specifies the page ID to retrieve results from. `0` gives you the most recent page.<br>**Example Values**: `6548695`

Example Request
---------------

**GET** `http://infinigag.eu01.aws.af.cm/trending/0`

	{
		"data": [
			{
				"id": 6763189,
				"from": {
					"name": "orhnbyrk"
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
			},
			...
		],
		"paging": {
			"next": "6761235"
		}
	}

Voting?
-------

Each item in the `data` object has an `actions` object with three URLs: `like`, `dislike` and `unlike`. What these do are self-explanatory.

The method is a bit hacky:

	<ul>
		<li><a target="vote" href="http://9gag.com/vote/like/id/6763189">Like</a></li>
		<li><a target="vote" href="http://9gag.com/vote/dislike/id/6763189">Dislike</a></li>
	</ul>
	...
	<iframe name="vote" hidden>

The catch is that the voter needs to be logged in on the 9GAG website.

Uses
----

- [9GAG (Unofficial)](http://apps.microsoft.com/windows/app/9gag-unofficial/846be2db-a72a-47b7-9507-e81ce0d2dd5b)
- [GagBook](http://github.com/dicksonleong/GagBook)