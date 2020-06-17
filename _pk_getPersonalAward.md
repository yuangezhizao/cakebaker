```
POST https://api.m.jd.com/client.action?functionId=cakebaker_pk_getPersonalAward HTTP/1.1
Host: api.m.jd.com
Connection: keep-alive
Content-Length: 79
Accept: application/json, text/plain, */*
Origin: https://bunearth.m.jd.com
User-Agent: <rm>
Content-Type: application/x-www-form-urlencoded
Referer: https://bunearth.m.jd.com/babelDiy/Zeus/3xAU77DgiPoDvHdbXUZb95a7u71X/index.html?babelChannel=fc1&lng=<rm>
Accept-Encoding: gzip, deflate, br
Accept-Language: zh-CN,en-US;q=0.9
Cookie: pt_pin=<rm>
X-Requested-With: com.jingdong.app.mall

functionId=cakebaker_pk_getPersonalAward&body={}&client=wh5&clientVersion=1.0.0

HTTP/1.1 200
Date: Wed, 17 Jun 2020 14:39:46 GMT
Content-Type: application/json;charset=utf-8
Connection: keep-alive
Access-Control-Allow-Origin: https://bunearth.m.jd.com
Access-Control-Allow-Credentials: true
Access-Control-Expose-Headers: X-API-Request-Id
X-API-Request-Id: 186316234-10172-1592404786378
X-API-Wl-Message: 0
vary: accept-encoding
Server: jfe
Strict-Transport-Security: max-age=86400
Content-Length: 974

{
    "code": 0,
    "data": {
        "bizCode": 0,
        "bizMsg": "success",
        "result": {
            "groupList": [
                {
                    "personalAward": "5.58",
                    "userImage": "http://storage.360buyimg.com/i.imageUpload/6a645f3732356130376561666339323231343536303538303535383431_big.jpg",
                    "userName": "鸿****意"
                },
                {
                    "myself": 1,
                    "personalAward": "4.43",
                    "userImage": "http://storage.360buyimg.com/i.imageUpload/77644e716e7461704f634f7a72794531343531303136373231303036_big.jpg",
                    "userName": "远**造"
                },
                {
                    "personalAward": "0.91",
                    "userImage": "http://storage.360buyimg.com/i.imageUpload/7764525548784743754e4a6d717931353733303132383935383437_big.jpg",
                    "userName": "c****2"
                },
                {
                    "personalAward": "0.59",
                    "userImage": "https://m.360buyimg.com/babel/jfs/t1/113771/5/6684/15278/5ebbc3ffE50c4c882/23a69500af15b8a2.png",
                    "userName": "j****1"
                },
                {
                    "personalAward": "0.46",
                    "userImage": "http://storage.360buyimg.com/i.imageUpload/6a645f3563633534653861346164326531343931333737343433313736_big.jpg",
                    "userName": "N****l"
                }
            ],
            "groupName": "害怕"
        },
        "success": true
    },
    "msg": "调用成功"
}
```
