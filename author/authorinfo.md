## 作者信息

GET `https://api.acgmx.com/public/search/users/details?id=xxx`

### 请求参数
| 字段  | 类型  | 描述  |
| :------------: | :------------: | :------------: |
| id  | Integer  | 作者ID  |


### 请求参数案例
`https://api.acgmx.com/public/search/users/details?id=2188232`

### 返回结果
```json
{
	"user": {
		"id": 2188232,
		"name": "wlop",
		"account": "wlop",
		"profile_image_urls": {
			"medium": "https:\/\/i.pximg.net\/user-profile\/img\/2016\/01\/20\/14\/32\/29\/10408877_978587c10c1ac2b02bca0caea6519c97_170.jpg"
		},
		"comment": "\u4e2d\u56fd\u4eba\u3067\u3059\u3001\u65e5\u672c\u8a9e\u304c\u3067\u304d\u307e\u305b\u3093\u304c\u3001\u3069\u3046\u305e\u3088\u308d\u3057\u304f\u304a\u9858\u3044\u3057\u307e\u3059\u3002PSD\u6e90\u6587\u4ef6\uff0c\u4f5c\u753b\u8fc7\u7a0b\u89c6\u9891: https:\/\/www.patreon.com\/wlop\r\n\u5fae\u535a\uff1ahttp:\/\/www.weibo.com\/wlop",
		"is_followed": false
	},
	"profile": {
		"webpage": "http:\/\/weibo.com\/wlop",
		"gender": "",
		"birth": "",
		"birth_day": "06-05",
		"birth_year": 0,
		"region": "China",
		"address_id": 48,
		"country_code": "CN",
		"job": "IT\u5173\u8054",
		"job_id": 1,
		"total_follow_users": 53,
		"total_mypixiv_users": 4,
		"total_illusts": 151,
		"total_manga": 0,
		"total_novels": 0,
		"total_illust_bookmarks_public": 1,
		"total_illust_series": 0,
		"total_novel_series": 0,
		"background_image_url": "https:\/\/i.pximg.net\/c\/1200x600_90_a2_g5\/background\/img\/2019\/05\/01\/11\/51\/20\/2188232_8b42f08d3c390d92807772a864a8c1b7_master1200.jpg",
		"twitter_account": "wlopwangling",
		"twitter_url": "https:\/\/twitter.com\/wlopwangling",
		"pawoo_url": "https:\/\/pawoo.net\/oauth_authentications\/2188232?provider=pixiv",
		"is_premium": true,
		"is_using_custom_profile_image": true
	},
	"profile_publicity": {
		"gender": "public",
		"region": "public",
		"birth_day": "public",
		"birth_year": "public",
		"job": "public",
		"pawoo": true
	},
	"workspace": {
		"pc": "",
		"monitor": "",
		"tool": "",
		"scanner": "",
		"tablet": "",
		"mouse": "",
		"printer": "",
		"desktop": "",
		"music": "",
		"desk": "",
		"chair": "",
		"comment": "",
		"workspace_image_url": null
	}
}
```
