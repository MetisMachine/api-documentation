# Service Data

## GET `/service/:service`
Returns JSON array of Service Data rows.

### Resource URL
_ht<span>tps://</span>dev.argus.metismachine.io/v1/service/:service_

### Parameters
Name | Required | Description | Default | Example
| --- | --- | --- | --- | --- |
`limit` | optional | positive number of items to return, after `offset` is processed | 100 | _20_
`offset` | optional | used for pagination, specify the positive number of rows to skip | 0 | _200_

### Example Request
_ht<span>tps://</span>dev.argus.metismachine.io/v1/service/twitter?limit=3&offset=0_

### Example Response
```json
[
    {
        "created_on": "2017-05-28T11:28:36.998329Z",
        "id": 10556084,
        "payload": {
            "contributors": null,
            "coordinates": null,
            "created_at": "Sun May 28 11:28:36 +0000 2017",
            "display_text_range": [
                13,
                19
            ],
            "entities": {
                "hashtags": [],
                "symbols": [],
                "urls": [],
                "user_mentions": [
                    {
                        "id": 3490102397,
                        "id_str": "3490102397",
                        "indices": [
                            0,
                            12
                        ],
                        "name": "wooks81",
                        "screen_name": "aidanellis4"
                    }
                ]
            },
            "favorite_count": 0,
            "favorited": false,
            "filter_level": "low",
            "geo": null,
            "id": 868791110113660928,
            "id_str": "868791110113660928",
            "in_reply_to_screen_name": "aidanellis4",
            "in_reply_to_status_id": 868790828797505536,
            "in_reply_to_status_id_str": "868790828797505536",
            "in_reply_to_user_id": 3490102397,
            "in_reply_to_user_id_str": "3490102397",
            "is_quote_status": false,
            "lang": "tl",
            "place": null,
            "retweet_count": 0,
            "retweeted": false,
            "source": "<a href=\"http://twitter.com/download/iphone\" rel=\"nofollow\">Twitter for iPhone</a>",
            "text": "@aidanellis4 Haha !",
            "timestamp_ms": "1495970916666",
            "truncated": false,
            "user": {
                "contributors_enabled": false,
                "created_at": "Mon Nov 11 15:11:47 +0000 2013",
                "default_profile": true,
                "default_profile_image": false,
                "description": "Just another antidoping troll...",
                "favourites_count": 3984,
                "follow_request_sent": null,
                "followers_count": 5841,
                "following": null,
                "friends_count": 71,
                "geo_enabled": false,
                "id": 2188546224,
                "id_str": "2188546224",
                "is_translator": false,
                "lang": "en",
                "listed_count": 163,
                "location": null,
                "name": "Ufe",
                "notifications": null,
                "profile_background_color": "C0DEED",
                "profile_background_image_url": "http://abs.twimg.com/images/themes/theme1/bg.png",
                "profile_background_image_url_https": "https://abs.twimg.com/images/themes/theme1/bg.png",
                "profile_background_tile": false,
                "profile_banner_url": "https://pbs.twimg.com/profile_banners/2188546224/1461593746",
                "profile_image_url": "http://pbs.twimg.com/profile_images/717728920095817728/eNZ1BV6e_normal.jpg",
                "profile_image_url_https": "https://pbs.twimg.com/profile_images/717728920095817728/eNZ1BV6e_normal.jpg",
                "profile_link_color": "1DA1F2",
                "profile_sidebar_border_color": "C0DEED",
                "profile_sidebar_fill_color": "DDEEF6",
                "profile_text_color": "333333",
                "profile_use_background_image": true,
                "protected": false,
                "screen_name": "oufeh",
                "statuses_count": 6012,
                "time_zone": "Amsterdam",
                "url": null,
                "utc_offset": 7200,
                "verified": false
            }
        },
        "service": "twitter"
    },
    {
        "created_on": "2017-05-28T11:28:37.048873Z",
        "id": 10556094,
        "payload": {
            "contributors": null,
            "coordinates": null,
            "created_at": "Sun May 28 11:28:36 +0000 2017",
            "entities": {
                "hashtags": [],
                "symbols": [],
                "urls": [],
                "user_mentions": [
                    {
                        "id": 2953435328,
                        "id_str": "2953435328",
                        "indices": [
                            3,
                            14
                        ],
                        "name": "Projeto Follow Trick",
                        "screen_name": "mainfriday"
                    }
                ]
            },
            "favorite_count": 0,
            "favorited": false,
            "filter_level": "low",
            "geo": null,
            "id": 868791110121828354,
            "id_str": "868791110121828354",
            "in_reply_to_screen_name": null,
            "in_reply_to_status_id": null,
            "in_reply_to_status_id_str": null,
            "in_reply_to_user_id": null,
            "in_reply_to_user_id_str": null,
            "is_quote_status": false,
            "lang": "en",
            "place": null,
            "retweet_count": 0,
            "retweeted": false,
            "retweeted_status": {
                "contributors": null,
                "coordinates": null,
                "created_at": "Sun May 28 11:27:26 +0000 2017",
                "entities": {
                    "hashtags": [],
                    "symbols": [],
                    "urls": [],
                    "user_mentions": []
                },
                "favorite_count": 14,
                "favorited": false,
                "filter_level": "low",
                "geo": null,
                "id": 868790817498025984,
                "id_str": "868790817498025984",
                "in_reply_to_screen_name": null,
                "in_reply_to_status_id": null,
                "in_reply_to_status_id_str": null,
                "in_reply_to_user_id": null,
                "in_reply_to_user_id_str": null,
                "is_quote_status": false,
                "lang": "en",
                "place": null,
                "retweet_count": 68,
                "retweeted": false,
                "source": "<a href=\"https://ifttt.com\" rel=\"nofollow\">IFTTT</a>",
                "text": "follow everyone who retweets this🌶",
                "truncated": false,
                "user": {
                    "contributors_enabled": false,
                    "created_at": "Wed Dec 31 10:28:13 +0000 2014",
                    "default_profile": false,
                    "default_profile_image": false,
                    "description": "Turn my notifications on for daily gain tweets 🌝🌙",
                    "favourites_count": 2155,
                    "follow_request_sent": null,
                    "followers_count": 55258,
                    "following": null,
                    "friends_count": 47689,
                    "geo_enabled": true,
                    "id": 2953435328,
                    "id_str": "2953435328",
                    "is_translator": false,
                    "lang": "en",
                    "listed_count": 559,
                    "location": "turn on my notifications ",
                    "name": "Projeto Follow Trick",
                    "notifications": null,
                    "profile_background_color": "000000",
                    "profile_background_image_url": "http://pbs.twimg.com/profile_background_images/593818607542374401/n62Jb8tp.png",
                    "profile_background_image_url_https": "https://pbs.twimg.com/profile_background_images/593818607542374401/n62Jb8tp.png",
                    "profile_background_tile": true,
                    "profile_banner_url": "https://pbs.twimg.com/profile_banners/2953435328/1489340453",
                    "profile_image_url": "http://pbs.twimg.com/profile_images/858670378134102018/RteDdT5S_normal.jpg",
                    "profile_image_url_https": "https://pbs.twimg.com/profile_images/858670378134102018/RteDdT5S_normal.jpg",
                    "profile_link_color": "1B95E0",
                    "profile_sidebar_border_color": "000000",
                    "profile_sidebar_fill_color": "000000",
                    "profile_text_color": "000000",
                    "profile_use_background_image": true,
                    "protected": false,
                    "screen_name": "mainfriday",
                    "statuses_count": 10394,
                    "time_zone": "Pacific Time (US & Canada)",
                    "url": "https://www.facebook.com/mainfriday",
                    "utc_offset": -25200,
                    "verified": false
                }
            },
            "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
            "text": "RT @mainfriday: follow everyone who retweets this🌶",
            "timestamp_ms": "1495970916668",
            "truncated": false,
            "user": {
                "contributors_enabled": false,
                "created_at": "Fri Apr 14 04:28:00 +0000 2017",
                "default_profile": false,
                "default_profile_image": false,
                "description": "im ur hope, im ur angel 😇  \n\nPh",
                "favourites_count": 2642,
                "follow_request_sent": null,
                "followers_count": 977,
                "following": null,
                "friends_count": 1612,
                "geo_enabled": false,
                "id": 852740193253597185,
                "id_str": "852740193253597185",
                "is_translator": false,
                "lang": "en-gb",
                "listed_count": 1,
                "location": null,
                "name": "호페 👑",
                "notifications": null,
                "profile_background_color": "000000",
                "profile_background_image_url": "http://abs.twimg.com/images/themes/theme1/bg.png",
                "profile_background_image_url_https": "https://abs.twimg.com/images/themes/theme1/bg.png",
                "profile_background_tile": false,
                "profile_banner_url": "https://pbs.twimg.com/profile_banners/852740193253597185/1493544779",
                "profile_image_url": "http://pbs.twimg.com/profile_images/858722939402727425/8ubK9bRs_normal.jpg",
                "profile_image_url_https": "https://pbs.twimg.com/profile_images/858722939402727425/8ubK9bRs_normal.jpg",
                "profile_link_color": "F58EA8",
                "profile_sidebar_border_color": "000000",
                "profile_sidebar_fill_color": "000000",
                "profile_text_color": "000000",
                "profile_use_background_image": false,
                "protected": false,
                "screen_name": "zxdeexxx",
                "statuses_count": 3360,
                "time_zone": null,
                "url": null,
                "utc_offset": null,
                "verified": false
            }
        },
        "service": "twitter"
    },
    {
        "created_on": "2017-05-28T11:28:37.788056Z",
        "id": 10556104,
        "payload": {
            "contributors": null,
            "coordinates": null,
            "created_at": "Sun May 28 11:28:37 +0000 2017",
            "entities": {
                "hashtags": [],
                "symbols": [],
                "urls": [
                    {
                        "display_url": "du3a.org",
                        "expanded_url": "http://du3a.org",
                        "indices": [
                            66,
                            89
                        ],
                        "url": "https://t.co/LghWEBpyr0"
                    }
                ],
                "user_mentions": [
                    {
                        "id": 2481231653,
                        "id_str": "2481231653",
                        "indices": [
                            3,
                            14
                        ],
                        "name": "بحه’ة آﻟـمً ☇ ♡̨ ",
                        "screen_name": "So_Alameer"
                    }
                ]
            },
            "favorite_count": 0,
            "favorited": false,
            "filter_level": "low",
            "geo": null,
            "id": 868791114291175425,
            "id_str": "868791114291175425",
            "in_reply_to_screen_name": null,
            "in_reply_to_status_id": null,
            "in_reply_to_status_id_str": null,
            "in_reply_to_user_id": null,
            "in_reply_to_user_id_str": null,
            "is_quote_status": false,
            "lang": "ar",
            "place": null,
            "possibly_sensitive": false,
            "retweet_count": 0,
            "retweeted": false,
            "retweeted_status": {
                "contributors": null,
                "coordinates": null,
                "created_at": "Sun May 28 11:07:35 +0000 2017",
                "entities": {
                    "hashtags": [],
                    "symbols": [],
                    "urls": [
                        {
                            "display_url": "du3a.org",
                            "expanded_url": "http://du3a.org",
                            "indices": [
                                50,
                                73
                            ],
                            "url": "https://t.co/LghWEBpyr0"
                        }
                    ],
                    "user_mentions": []
                },
                "favorite_count": 0,
                "favorited": false,
                "filter_level": "low",
                "geo": null,
                "id": 868785821234733056,
                "id_str": "868785821234733056",
                "in_reply_to_screen_name": null,
                "in_reply_to_status_id": null,
                "in_reply_to_status_id_str": null,
                "in_reply_to_user_id": null,
                "in_reply_to_user_id_str": null,
                "is_quote_status": false,
                "lang": "ar",
                "place": null,
                "possibly_sensitive": false,
                "retweet_count": 1,
                "retweeted": false,
                "source": "<a href=\"http://du3a.org\" rel=\"nofollow\">تطبيق دعـــــــــــاء</a>",
                "text": "أستغفر الله والحمدلله ولا إله إلا الله والله أكبر https://t.co/LghWEBpyr0",
                "truncated": false,
                "user": {
                    "contributors_enabled": false,
                    "created_at": "Sun Apr 13 10:39:30 +0000 2014",
                    "default_profile": true,
                    "default_profile_image": false,
                    "description": "ما زلتُ حيّا في مكان ما،وأعرفُ ما أريدُ سأصيرُ يوما ما أريدُ .....ضحكــتي رأس مالي ♡̨ ",
                    "favourites_count": 53,
                    "follow_request_sent": null,
                    "followers_count": 1690,
                    "following": null,
                    "friends_count": 2085,
                    "geo_enabled": true,
                    "id": 2481231653,
                    "id_str": "2481231653",
                    "is_translator": false,
                    "lang": "ar",
                    "listed_count": 1,
                    "location": " Saudia Arabia::Al Dammam",
                    "name": "بحه’ة آﻟـمً ☇ ♡̨ ",
                    "notifications": null,
                    "profile_background_color": "C0DEED",
                    "profile_background_image_url": "http://abs.twimg.com/images/themes/theme1/bg.png",
                    "profile_background_image_url_https": "https://abs.twimg.com/images/themes/theme1/bg.png",
                    "profile_background_tile": false,
                    "profile_banner_url": "https://pbs.twimg.com/profile_banners/2481231653/1410358475",
                    "profile_image_url": "http://pbs.twimg.com/profile_images/706180807090696192/ULDsxdSe_normal.jpg",
                    "profile_image_url_https": "https://pbs.twimg.com/profile_images/706180807090696192/ULDsxdSe_normal.jpg",
                    "profile_link_color": "1DA1F2",
                    "profile_sidebar_border_color": "C0DEED",
                    "profile_sidebar_fill_color": "DDEEF6",
                    "profile_text_color": "333333",
                    "profile_use_background_image": true,
                    "protected": false,
                    "screen_name": "So_Alameer",
                    "statuses_count": 19602,
                    "time_zone": null,
                    "url": null,
                    "utc_offset": null,
                    "verified": false
                }
            },
            "source": "<a href=\"http://twitter.com/download/android\" rel=\"nofollow\">Twitter for Android</a>",
            "text": "RT @So_Alameer: أستغفر الله والحمدلله ولا إله إلا الله والله أكبر https://t.co/LghWEBpyr0",
            "timestamp_ms": "1495970917662",
            "truncated": false,
            "user": {
                "contributors_enabled": false,
                "created_at": "Sat Nov 01 14:00:07 +0000 2014",
                "default_profile": true,
                "default_profile_image": false,
                "description": "‏‏عساني من الحسد اسلم وعساهم من الغيره يموتون . \n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\nشاعره يابعدي💖\nالقلب محجوز يلي علی البال يطري",
                "favourites_count": 176,
                "follow_request_sent": null,
                "followers_count": 2890,
                "following": null,
                "friends_count": 4085,
                "geo_enabled": false,
                "id": 2886402649,
                "id_str": "2886402649",
                "is_translator": false,
                "lang": "ar",
                "listed_count": 1,
                "location": "الخاص ممنووووع ❌",
                "name": "💜سلطانه الغرام💜",
                "notifications": null,
                "profile_background_color": "C0DEED",
                "profile_background_image_url": "http://abs.twimg.com/images/themes/theme1/bg.png",
                "profile_background_image_url_https": "https://abs.twimg.com/images/themes/theme1/bg.png",
                "profile_background_tile": false,
                "profile_banner_url": "https://pbs.twimg.com/profile_banners/2886402649/1420645652",
                "profile_image_url": "http://pbs.twimg.com/profile_images/766578143717097472/1-4oHL5i_normal.jpg",
                "profile_image_url_https": "https://pbs.twimg.com/profile_images/766578143717097472/1-4oHL5i_normal.jpg",
                "profile_link_color": "1DA1F2",
                "profile_sidebar_border_color": "C0DEED",
                "profile_sidebar_fill_color": "DDEEF6",
                "profile_text_color": "333333",
                "profile_use_background_image": true,
                "protected": false,
                "screen_name": "bayoon__22",
                "statuses_count": 3780,
                "time_zone": null,
                "url": null,
                "utc_offset": null,
                "verified": false
            }
        },
        "service": "twitter"
    }
]
```